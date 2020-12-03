# 2.2 Utiliser une base de données 

## Que fait-on avec une base de données?

Lorsqu'une base de données a été complétée, on peut commencer à l'interroger. Les chercheur·se·s ont bel et bien créé la base de données avec des idées de ce qu'ils aimeraient en retirer une fois l'entrée des données terminées. Nous avons décider de remonter à la source pour retrouver, dans le rapport rédigé par Françoise Boudon et Werner Szambien en 1990, un certain nombre de requêtes qu'ils souhaitaient effectuer. Ils étaient encore au début de l'étape de création de la base de données, mais l'engouement pour les potentiel d'utilisation de CONBAVIL est déjà présent. "On pourra établir à volonté en quelques minutes la liste :

1. [dépôts de mendicité créés par Napoléon](http://192.168.0.144:8080/viz/BoudonSzambien/#q1)
2. [églises transformées en école dans le département de la Nièvre entre 1802 et 1810](http://192.168.0.144:8080/viz/BoudonSzambien/#q2)
3. [rapports confiés à Chalgrin dès son retour "au pouvoir" sous le Directoire](http://192.168.0.144:8080/viz/BoudonSzambien/#q3)
4. [le nombre et la nature des chantiers dirigés par l'architecte Boissonnade en Aveyron dans les années 1830](http://192.168.0.144:8080/viz/BoudonSzambien/#q4)
5. [le pourcentage des dossiers de construction et de réparation présentés au conseil pendant dix ans](http://192.168.0.144:8080/viz/BoudonSzambien/#q5)
6. [le pourcentage de ceux qu'il rejette et ceux qu'il adopte](http://192.168.0.144:8080/viz/BoudonSzambien/#q6)
7. [l'activité de Rondelet comme auteur de projets et comme rapporteur de dossiers](http://192.168.0.144:8080/viz/BoudonSzambien/#q7)           

etc..." (Szambien et Boudon, 1990: 10)

Nous allons utiliser ces questions pour démontrer par l'exemple comment utiliser la base de données CONBAVIL.

## Les requêtes SQL

Du point de vue informatique, l'interrogation d'une base de données se fait par le moyen de requêtes dans un langage structuré, SQL (Structured Query Language). Lorsqu'on apprend à créer une base de données, on apprend donc également comment faire une requête SQL. On effectue ces requêtes sur l'ordinateur qui contient la base de données, soit dans le terminal, soit dans l'interface du gestionnaire de base de données utilisé. Une requête SQL est une instruction informatique textuelle dont les trois instructions débutent par des mots-clefs et se terminent par un retour à la ligne. La première, "SELECT", concerne l'information à afficher comme résultat de la requête. L'élément complet se désigne par l'astérisque, sinon il faut lister les propriétés que l'on veut afficher.  La deuxième, "FROM", sélectionne la table. dans la base de données, dans laquelle est stockée l'information. Puisque CONBAVIL est une base de données dite "à plat" et non pas relationnelle, elle ne contient qu'une seule table. Nous allons donc toujours chercher l'information dans la table "conbavil" avec l'instruction "FROM conbavil". La dernière instruction, "WHERE", contient les conditions pour retourner un élément dans le résultat. On choisit donc des valeurs souhaitées pour certains champs dans la base de données. Nous avons sélectionné deux questions qui correspondent à des requêtes types comme exemples. [^1]

### Q2

Pour connaître le nombre d'églises transformées en école dans le département de la Nièvre entre 1802 et 1810 (question 2), ou pour effectuer toute requête, il faut commencer par identifier les éléments dans la question qui correspondent à des champs de la base de données. Dans cette requête, on identifie "église" et "école", qui sont des types d'édifices. "Nouvelle affectation" correspond à un type d'intervention. Puis on a un département, la Nièvre, ainsi qu'une fourchette de dates "entre 1802 et 1810".

Nous voulons donc interroger la base de données pour savoir s'il existe des fiches qui correspondent aux critères suivants: la date (DAR) de la fiche doit être comprise entre 1802 et 1810 ─ '1802-01-01' et '1810-12-31' . Le département doit correspondre à la Nièvre; on peut l'écrire en toutes lettres 'AL = "Nièvre" ' mais si l'on veut éviter des problèmes d'orthographe et d'accents, on peut également utiliser le numéro de département (L), '59'. Le type d'intervention(PJT) doit être une nouvelle affectation et le type d'édifice (DES) soit une église, soit une école, ou les deux. Dans les cas de nouvelles affectations, les chercheur·se·s ont tenté de documenter les deux fonctions de l'édifice, c'est-à-dire le type d'édifice avant (église) et après (école) le changement. Cependant, ce n'était pas toujours possible. Dans ces situations, il est recommandé de "viser large" au début ─ le type d'édifice est soit une église, soit une école─ puis de choisir une façon de trier les résultats s'il y en a trop.

`SELECT *`
`FROM conbavil`
`WHERE (DAR BETWEEN '1802-01-01' AND '1810-12-31') AND L='58' AND (DES='église'|'école') AND PJT='nouvelle affectation'`

Lorsqu'on effectue une telle requête, on a en tête une hypothèse concernant le nombre de résultats. Dans ce cas-ci, on commence avec les 27'000 fiches contenues dans CONBAVIL. Par un simple calcul de probabilité (qui ne prend pas en compte les spécificités de la base), on peut estimer que la fourchette de date en élimine environs les 4/5èmes (8 ans sur 45). Dans le cas d'une répartition égale à travers le temps, il nous en reste un cinquième, donc environ 5000 fiches. Le choix du département de la Nièvre exclut tous les autres (plus d'une centaine, surtout avec les régions annexées à l'époque). À nouveau, même en faisant l'hypothèse d'une répartition égale des fiches entre les départements (on sait que n'est pas le cas, mais nous visons large), il resterait un centième donc 500 fiches. De plus, en ne considérant que les nouvelles affectations, on élimine toutes les nouvelles constructions ainsi que les réparation. on peut ainsi se douter qu'on aura peu de résultats pour cette requête. Finalement, si l'on spécifie les deux types d'édifices, église et école, en restera-t-il? 

Ces hypothèses issues des probabilités peuvent être enrichies par des connaissances historiques et la familiarité avec les données. Travailler ses hypothèses n'est toutefois pas forcément nécessaire car c'est très rapide de lancer une requête, le résultat est quasi-immédiat. On peut simplement fonctionner par essais-erreurs et ajuster le tir au fur et à mesure de la lecture des résultats obtenus. On peut même aller contre l'instinct, faire une recherche "même si on y croit pas trop"; la facilité et la rapidité d'obtention des résultats invite même à élargir ses questionnements.

### Q4

Comme second exemple, nous avons choisi le nombre et la nature des chantiers dirigés par l'architecte Boissonnade en Aveyron dans les années 1830 (q4). On cherche des fiches dont l'auteur est un architecte (PAUT = "architecte") et dont le nom est "Boissonnade", au cours des années 1830 (DAR BETWEEN '1830-01-01' AND '1839-12-31')[^2]. Il faudra ensuite les regrouper par type d'intervention et compter les occurrences pour chaque type. Initialement, identifier les délibérations en Aveyron dont Boissonnade est l'architecte semble plutôt évident: AUT="Boissonnade". Il faut toutefois prendre en compte les problèmes d'orthographe, car les noms de personnes ont été mentionnées et orthographiées telles que les chercheur·se·s ont pu les lire (Boudon 2009: 20). En parcourant les données, nous avons remarqué qu'il y a deux orthographes employées: "Boissonnade" et "Boissonade". De plus, nous avons soulevé dans la partie 2.1 le problème de TEXTO, dont le fonctionnement à plat requiert d'entrer les cas avec de multiples auteurs dans les champs AUT, AUT1, AUT2, puis d'inclure une série de nom séparés par des virgules dans AUT2 s'il y en a encore plus, et il reste à savoir si les professions (PAUT2) sont renseignées de la même façon.

`SELECT PJT, Count(*)`
`FROM conbavil`
`WHERE Depart='12 AND (DAR BETWEEN '1830-01-01' AND '1839-12-31')(((AUT='Boissonnade' OR AUT='Boissonade) AND PAUT='architecte') OR ((AUT1='Boissonnade' OR AUT1='Boissonade) AND PAUT1='architecte') OR (Contains(AUT2, 'Boissonnade') OR Contains(AUT2, 'Boissonade')) AND Contains(PAUT2,'architecte'))`
`GROUP BY PJT` 

Afin d'identifier la nature et le nombre des projets, nous regroupons (Group by) par nature du projet (PJT) et sélectionnons le résultat en affichant chaque groupe et son nombre d'occurrences (Count). L'absence de normalisation dans les noms, en sus du problème des multiples champs auteurs, rend la requête complexe et touffue. Si on ne connaît pas les spécificités de la base, il y a un gros risque de ne pas penser à ces détails et d'ainsi passer à côté de plusieurs résultats. 

### L'accès à la base de données

La première et la plus "basique" façon d'utiliser une base de données consiste donc à l'interroger via le langage SQL. Ce langage est très puissant et permet d'effectuer des recherches complexes avec rapidité. Il faut non seulement connaître le langage des requêtes mais également être familier·ère avec le contenu de CONBAVIL, comme nous avons pu le voir avec l'exemple de la q4. Il s'agit là d'un niveau de littératie numérique peu commun parmi la majorité des chercheur·se·s qui étudient l'architecture publique en France durant la première moitié du XIXe siècle. 

Afin de faciliter l'utilisation de bases de données, l'informatique prévoit donc des interfaces, ou des vues, qui permettent à des utilisateurs qui ne connaissent pas le langage SQL ou même les détails de la base de données de données de s'en servir malgré tout. Ces interfaces sont plus visuelles que textuelles: plutôt que d'écrire la requête, on est dans un environnement "boîte à clics" où l'on sélectionne, dans des listes déroulantes par exemple, des critères pour filtrer la base de données. C'est un dispositif où l'on peut visualiser sa requête via les champs du formulaire. Il est interactif dans le sens où l'utilisateur peut agir via la sélection d'un élément dans une liste déroulante, le choix de cases à cocher ou en entrant des chaînes de caractères (du texte). L'interface sert d'intermédiaire, elle est programmée pour transformer l'équivalent d'un formulaire en une requête SQL. 

Cette interface peut être conçue au sein du logiciel de base de données, ce qui signifie qu'elle s'utilise localement, sur l'ordinateur où la base de données est installée. Cela signifie que qu'un·e chercheur·se ne peut y avoir accès que s'il·elle se rend au Centre André-Chastel afin d'utiliser les machines équipées à cet effet, après avoir obtenu les autorisations nécessaires [^6]. 

## Interface de l'INHA

Avec l'avènement du web, il a été question de rendre les bases de données accessibles en ligne. Cela signifie que la base de données se trouve sur un serveur connecté à internet. L'interface est un site web qui communique avec le serveur pour envoyer des requêtes et recevoir des résultats. Le langage utilisé change, mais le principe d'interface qui permet de créer des requête structurée et l'affichage des résultats reste identique. 

Il faut toutefois prendre note que la base de données "en ligne" est un export de la base de données "locale" qui se trouve au centre André-Chastel. Lorsque les chercheur·se·s apportent des changements à la base de données locale, ces modifications ne s'appliquent pas à la base en ligne si celle-ci n'est pas connectée dynamiquement. C'est donc un système de versions qu'il faut prendre en compte. Cela signifi que, par exemple, qu'après une étape de recherche qui enrichit le contenu de CONBAVIL, on effectue une mise à jour de la base de données en ligne pour l'aligner avec le  contenu [^15]. Ce faisant, il faut notamment prendre compte du fait que le contenu de la base peut changer. La version de la base de données que nous avons employée pour la rédaction de ce mémoire n'est donc pas tout à fait identitique ni à celle en ligne, ni à celle "maîtresse"[^16] au centre André-Chastel.

### Présentation du formulaire

À l'occasion de la complétion de la base de données en 2009, un outil d'interrogation en ligne a été créé pour faciliter son utilisation et augmenter son accessibilité. Il s'agit d'un formulaire disponible sur le site internet de l'INHA [^7]. L'interface de consultation de la base de données détermine ses utilisations possibles. Nous allons donc effectuer une analyse de cette interface afin d'identifier les moyens actuellement disponibles au public-chercheur·se·s pour se servir de CONBAVIL

Le formulaire se divise en trois sections. Tout d'abord, la section "Interrogation sur le projet" contient les informations relatives à l'architecture: fonction et emplacement de l'édifice, type d'intervention, intervenant et coût. La deuxième section "Interrogation sur le rapport issu de l'examen du projet" se réfère au fonctionnement du Conseil: date de la séance du conseil, rapporteur et contenu du rapport, décision, cote dans les archives et présence de dessins. Finalement, la dernière section est un choix de procédures administratives. Le formulaire contient des champs "plein texte", où l'utilisateur·rice peut écrire en toutes lettres ce qu'il·elle recherche, et des listes déroulantes, où il faut choisir un critère dans les options dans la liste. Les cases à cocher sont des critères booléen (oui/non), ce qui signifie que le critère concerné agit comme un filtre s'il est coché. 

Le résultat d'une recherche via le formulaire apparaît sous la forme d'une liste de fiches qui correspondent aux critères sélectionnés. Pour consulter les détails, le chercheur doit parcourir la liste de façon linéaire. Chaque fiche présente <!-- éditorialise? au sens minimal ---> le contenu d'une entrée dans la base de données. Nous avons testé cet outil d'interrogation en ligne, toujours avec la liste de question qui nous servent de cas d'utilisation [^10].

<!-- exemples avec le format Filemaker-->

### Cas d'utilisation (x)

#### Q1

Pour trouver les dépôts de mendicités créés par Napoléon, nous devons identifier la dénomination de façon hiérarchique. La liste déroulante suggère d'abord les catégories, nous sélectionnons "architecture hospitalière, d'assistance ou de protection sociale". Apparaissent alors les types d'édifices qui appartiennent à cette catégorie. Cela sous-entend que l'utilisateur doit être capable d'identifier la catégorie d'un type d'édifice ou y aller par "essai/erreur" puisque les types se mettent à jour en fonction de la sélection de la catégorie.

<img src="/home/lenamk/Documents/atlasNumerique/Redaction/img/BoudonSzambien/1-depotmendicite.png" alt="1-depotmendicite" style="zoom:45%;" />

Nous avons ensuite sélectionné "Napoléon" dans le contenu du rapport (car on peut exclure qu'il ait été architecte ou intervenant du projet). Puisque cocher élément remarquable pourrait éliminer les options plein texte, mais que si Napoléon est un élément remarquable, son nom est probablement contenu dans le rapport, nous n'avons pas coché cette option. On a également préféré inscrire Napoléon sans préciser "I" ou "Ier" dans le but d'inclure le plus de résultats possible. On ne peut malheureusement pas exclure la possibilité que d'autres graphies aient été employées.

<img src="/home/lenamk/Documents/atlasNumerique/Redaction/img/BoudonSzambien/1-napoleon.png" alt="1-napoleon" style="zoom:33%;" />

<img src="/home/lenamk/Documents/atlasNumerique/Redaction/img/BoudonSzambien/1-listeresultats.png" alt="1-listeresultats" style="zoom:33%;" />

Dans les trois résultats qui correspondent notre recherche, nous constatons que le nom de Napoléon est mentionné en référence à des articles du "code Napoléon", c'est-à-dire au code civil. En fait, en prenant du recul par rapport au formulaire pour se concentrer sur le contexte historique, on comprend que la question fait plutôt référence au décret impérial du 5 juillet 1808, où Napoléon prescrit la création de dépôts de mendicités dans chaque département (Peny, 2011: parag. 1-2). S'il en existait déjà certains avant, ce sont donc ceux créés après 1808 qui répondent à cette question.

En revenant au formulaire, on constate toutefois qu'on ne peut pas choisir un intervalle de dates, mais seulement sélectionner une date avec un degré de précision qui va de l'année, au mois puis au jour. Lorsqu'on lance la requête pour tous les dépôts de mendicités, on obtient un total de 930 enregistrements répartis sur 47 pages. La dernière entrée de la première page de résultats est datée de mars 1808, mais nous ne parvenons pas à afficher la page suivante [^8]. Outre ce problème, nous devrions ensuite compter les entrées manuellement, sachant que les délibérations peuvent concerner la même affaire. Pour exclure ce problème, il faudrait toutes les consulter et tenter d'établir lesquelles sont liées.

En conclusion, malgré l'indexation des dépôts de mendicités dans la base de données, l'interface n'assiste pas encore suffisamment les chercheur·se·s pour répondre à une telle question "en quelques clics". 

#### Q3

Pour identifier les rapports confiés à Chalgrin dès son retour "au pouvoir" sous le Directoire, il suffit de sélectionner "Chalgrin" comme rapporteur et l'on obtient effectivement 102 résultats en quelques clics. La date de son retour "au pouvoir" sous le Directoire est à déterminer pour le spécialiste qui se pose cette question. Il en est de même pour les résultats obtenus

<img src="./img/BoudonSzambien/3-Chalgrin.png" height="50px"><img src="./img/BoudonSzambien/3-102resultats.png" alt="3-103resultats" style="zoom: 33%;" />



#### Q4

Revenir à la question 4 (le nombre et la nature des chantiers dirigés par l'architecte Boissonnade en Aveyron dans les années 1830) nous permet d'identifier une série de limitations dans l'interface. Nous retrouvons la possibilité de sélectionner l'Aveyron mais pas l'intervalle de temps des années 1830. Ensuite, en ce qui concerne l'architecte, nous pouvons utiliser la troncature du nom, " Boisson* " pour inclure les deux graphies (Boissonnade et Boissonade) [^9]. 

<img src="/home/lenamk/Documents/atlasNumerique/Redaction/img/BoudonSzambien/4-Boisson-Aveyron.png" alt="4-Boisson-Aveyron" style="zoom: 67%;" />

Nous y avons trouvé des résultats "non justifiés", comme dans la troisième notice, où nous ne trouvons pas de mention de Boissonnade ni d'autre termes qui commenceraient par ces lettres. Nous ne savons pas pourquoi cette notice apparaît, mais cela signale un problème de transparence, car l'interface n'explicite pas les résultats pour l'utilisateur·rice.

### Observations critiques sur l'outil 

Le formulaire présente un avancement important dans le cycle de vie de la base de donnée <!-- terme plus linéaire, parcours? développement ? -->. Il offre un accès à CONBAVIL depuis n'importe quel ordinateur personnel connecté à internet. L'interface assiste la recherche au sein de ces archives et permet d'en consulter le contenu. Il en devient presque inimaginable de comparer l'interrogation de la base de données à un déplacement aux archives pour parcourir la dizaine de registre qui concerne la période à la recherche des délibérations qui concernent le travail de l'architecte Boissonnade en Aveyron (cf. Q4). Cela signifie notamment des chercheur·se·s qui n'avaient pas prévu ou ne pouvaient pas consulter les archives y ont désormais accès. Accessible en ligne, l'interface permet à un plus grand nombre de se pencher sur le contenu des archives du Conseil des bâtiments civils et facilite les recherches dans CONBAVIL.

Nous avons cependant constaté que l'interface présente plusieurs inconvénients pour la recherche. En sus des contraintes sur l'interrogation du contenu que nous avons révélées dans les cas d'utilisations, certains éléments de l'expérience utilisateur (UX) complexifient la recherche. 

Tout d'abord, on ne peut pas consulter la base sans sélectionner un critère de recherche. Lorsqu'on la découvre et qu'on ne connaît pas nécessairement son contenu, c'est impossible de l'explorer sans tout de suite devoir sélectionner des critères. Ensuite, lorsqu'on lance une recherche, on ne voit plus les critères sélectionnés, mais seulement la liste de résultats. On ne peut donc pas vérifier les critères et repérer une possible erreur. Lorsqu'on revient en arrière, il faut faire retour avec la fonction précédent du navigateur, il n'y a pas de boutons qui permette de retourner à la requête pour la modifier par exemple. En pesant retour, les critères précédents sont souvent encore présents mais ça ne se remarque pas facilement [^11]. On ne peut pas non plus enregistrer ou partager une recherche, ou les résultats, ce qui est problématique pour publier des résultats. 

Ensuite apparaît un problème classique en informatique: la confrontation entre la facilité et la flexibilité du logiciel employé. On peut "tout" faire avec des requêtes SQL, mais il faut savoir écrire ses requêtes. Il n'y a qu'à cliquer et à sélectionner des critères de recherche dans une interface comme le formulaire de l'INHA. Toutefois,ce type de "solution clef en main" est très restrictive. Il y a des requêtes qu'on pourrait faire très facilement et qui n'y sont pas prévues. On ne peut pas dévier des options prédéfinies. Tout type d'utilisation qui n'est pas prévu par les concepteur·rice·s de l'interface est donc impossible. Quels que soit la qualité de l'interface et les améliorations que l'on peut y apporter, les moyens d'interrogation sont fini (*finite*).

Nous avons également manqué de retours (*feedback* visuel) entre la recherche effectuée et les données. Cela a créé un doute constant: est-ce bien ça que je cherchais, est-ce que ce résultat correspond à ma recherche? On ne peut pas critiquer le résultat obtenu car les critères de sélection ne sont pas mis de l'avant lors de la consultation des fiches. L'interface étant composée de deux vues principales distinctes - le formulaire de recherche et la liste de résultats -, cela crée un effet "boîte noire" quant au processus d'interrogation de la base de données. On ne peut pas voir ses critères de recherche et les résultats obtenus en même temps. Lorsqu'il s'agit d'un critère "évident", comme un numéro de département ou la date d'un rapport, cela n'est pas forcément nécessaire. Toutefois, lorsqu'on effectue une recherche plein texte comme dans l'exemple précédet (q4), plus de transparence et de clarté parmi résultats obtenus seraient les bienvenus. 

Ensuite, un problème très important de l'interface apparaît: il s'agit de la dimension quantitative, quand on parle du nombre, puis dans q5 et q6 de pourcentages. Excepté pour le "nombre d'enregistrements qui correspondent à la recherche" dont nous avons démontré la validité relative, il n'y a pas moyen d'envisager une approche quantifiée dans l'interface.

<!-- transition ?  ces questions introduisent le problème, mais on veut clore la liste de questions avant d'entrer dans le vif du sujet-->

Au niveau de la consultation des fiches, leur format statique les limites à des "présentoirs". Le confort d'utilisation de cette mise en page est tout à fait supérieur à un résultat en "texte pur" affiché dans un terminal. Cependant, nous avons ressenti un limitation à ne pas pouvoir sélectionner un contenu pour naviguer dans la base, contrairement au principe web des liens hypertextes auquel nous sommes habitués lors de la consultation de Wikipédia par exemple. Cela est dû à la différence fondamentale entre une base de données et des données "hyper"-liées, dans le sens de reliées par des hyperliens [^18]. 

Par principe, une base de données est une boîte noire: une fois entrées, les données ne peuvent être ressorties de la base de données qu'avec une requête SQL. Il y a donc l'interface en surface, et les données sont stockées en profondeur. Au contraire, une page web est un contenu linéaire et "à plat". Tout est là, mais cela signifie que tout doit être déjà en place: un hyperlien n'existe que s'il a été entré dans la page et ne fonctionne que si la page reliée existe également. Il existe des solutions pour transposer le contenu d'une base de données en un système d'encyclopédie exploratoire où l'on navigue à travers le contenu via une série d'hyperliens. La décision de créer un formulaire nous semble due à la priorité d'outiller les chercheur·se·s pour qu'il·elle·s puissent interroger de la base de données.

Ainsi, pour se focaliser sur un contenu spécifique dans l'interface de l'INHA, il faut retenir le critère en question, revenir en arrière jusqu'au formulaire ou ouvrir un nouvel onglet pour effectuer sa recherche. Nous avons cependant régulièrement ouvert un très grand nombre d'onglets pour éviter de perdre les résultats d'une recherche. Cela a pour effet de créer une avalanche d'onglets ouverts, généralement difficiles à naviguer. Il s'agit là d'un environnement contraignant pour effectuer toute forme de comparaison. 

L'ensemble de ces éléments posent des défis majeurs pour faire de la recherche avec l'interface en ligne, surtout si l'on souhaite effectuer des comparaisons ou développer des approches statistiques. Pourtant, ce sont les qualités quantitatives de la base qui intéressent les chercheur·se·s. Les questions émises par Françoise Boudon et Werner Szambien en 1990 s'expriment en nombres et en pourcentages. "En traitant tous les rapports selon une analyse informatisée, on les a rendus, en bloc, supérieurs à ce qu'ils sont chacun dans leur individualité, c'est-à-dire comparables" (Boudon 2009: 13). L'intérêt de la base de donnée se situe au-delà de l'accès à la fiche individuelle,

## Conclusion 2.2

Dans l'objectif de mettre en valeur cette base de données, en même temps que pour ouvrir des horizons jusqu’ici non-exploités dans la recherche sur les actions du Conseil des bâtiments civils et donc sur l’histoire de l’architecture publique en France, nous faisons l'expérience de la conception d'une nouvelle interface utilisateur pour la base CONBAVIL. 

Dans la partie suivante, nous passerons en revue les enjeux épistémologiques intrinsèques à la création d'une nouvelle interface de recherche. Nous procéderons ensuite à une restructuration et un enrichissement des données de CONBAVIL.

___

## Notes

[^6]: À moins d'avoir un ordinateur personnel équipé du logiciel et d'une copie autorisée de la base.
[^7]: https://www.inha.fr/fr/ressources/outils-documentaires/conseil-des-batiments-civils-conbavil/interroger-conbavil.html
[^8]: Le problème semble être causé par le trop grand nombre de pages, car, pour une recherche qui comporte par exemple six pages de résultats, le bas de la page énumère les pages de résultats, cliquables pour leur consultation.
[^9]: Il y a également un "Boisson-Quincy" dans la base, mais sa seule mention est dans les Yvelines (conbavil26321), ça ne fausse pas cette requête. Toutefois, pour savoir cela, nous avons fait recherche plein texte dans le fichier de données. C'est difficile à vérifier pour un·e utilisateur·rice qui n'a que l'interface



[^10]: 
[^11]: C'était relativement inconsistant lors de nos essais. 
[^12]: On reste dépendant des technologies du web, un point important concerne notamment les navigateurs, nécessaires pour aller sur le web mais qui évoluent beaucoup... 
[^1]: Avertissement: n'ayant pas  accès à la base de données dans son format original, les proposition suivantes sont des exemples basés sur la [documentation](http://127.0.0.1:8080/viz/Structure/index.html) que nous avons réunie et inspirés par la requête à effectuer.<!-- exemples de requêtes: format TEXTO -->
[^2]: Pour écrire une requête, on prend souvent la question à reculons car la façon dont on tend à les formuler en français continent souvent les informations détaillées à la fin. On commence donc avec l'intervalle de temps et le département, puis on s'attaque aux questions de l'auteur, pour finalement décrire la forme sous laquelle on veut obtenir le résultat.
[^3]: pour la majorité des utilisateur·rice·s
[^16]: traduction libre du terme anglais couramment utilisé en informatique "master"
[^15]: L'alignement, en informatique, signifie une comparaison de deux versions d'un contenu. L'un est considéré "plus avancé" que l'autre, et l'alignement permet d'identifier les différences ainsi que la mise à jour du contenu neuf ou modifié.
[^18]: À ne pas confondre avec des données liées, une technologie beaucoup plus récente: LOD...