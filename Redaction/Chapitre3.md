#  Chapitre 3

Nous voulons désormais créer un espace de travail pour l'exploration et l'interprétation des données de CONBAVIL. Il s'agit de concevoir un dispositif exploratoire qui a pour source d'inspiration les questions de recherche évoquées par les chercheur·se·s impliqué·e·s dans la création de la base, l'historiographie des recherches sur le sujet, le contexte historique, c'est-à-dire la statistique, la cartographie thématique et la rationalisation administrative. Nous cherchons, dans un premier temps, des concordances entre ces questions et les moyens méthodologiques et technologiques à notre disposition. Nous expérimentons ensuite avec leur mise en pratique de façon isolée, avant de les rassembler dans un espace éditorial commun: l'atlas numérique de l'architecture publique en France (1795 - 1840). Cet atlas est à la fois un outil de réflexion théorique autour des enjeux d'éditorialisation et de conception d'interfaces de recherche, et un micro-prototype issu de l'application pratique de ces opérateurs théoriques. 

## 3.1 Espaces et interprétation des données 

Une interface donne forme aux données, elle dicte donc notre façon d'y réfléchir et les questions qu'on voudrait y poser. Les interfaces produisent des affordances épistémologiques parce qu'elles sont le cadre au sein duquel nous posons nos questions, nos observations, nos hypothèses et nos déductions à propos de la base de données.

Puisqu'il existe déjà un outil d'interrogation, nous voulons plutôt créer un instrument de recherche. Si le premier permet de chercher un contenu spécifique (heuristique) via des requêtes SQL ou l'outil d'interrogation, le second est pensé comme instrument de recherche et dispositif critique qui serait à l'origine de questionnements (herméneutique).

[à compléter]

produire de nouvelles connaissances. 

Interdisciplinarité --> cartographie & visualisation de données (sémiologie, graphisme, développement d'interface)



### 3.1.1 Analyse quantitative et statistique

Notre première piste pour la création de notre instrument de recherche est issue de l'historiographie de la base de données et des archives du Conseil des bâtiments civils. Nous souhaitons poursuivre et étendre les recherches quantitatives ou statistique, ainsi que la dimension spatialisée des travaux de Georges Teyssot et Bernard Lepetit (ch1.3.3), ce qui est désormais non seulement rendu possible mais aussi facilité par CONBAVIL. Les données sont géolocalisées et d'indexées en catégories et sous-catégories architecturales, il reste à décider de la méthode à employer. 

Nous puisons également dans le contexte de création de la base de données pour les méthodes de recherches encore inexploitées. Quand il introduit CONBAVIL à l'occasion de sa mise en ligne en 2009, l'historien de l'architecture Jean-Phlippe Garric détaille l'énorme potentiel de cette base de données pour la recherche. 

> Cette base de données [...] nous conduit à imaginer des enquêtes et des travaux jadis presque impossibles, ouvrant des
> perspectives inédites sur des analyses quantitatives, économiques ou typologiques, sur des comparaisons entre régions ou sur les rapports Paris-Province, sur le mouvement de codification des règlements et des marchés de travaux, sur les combats de l’art et de la nécessité, du local et du national. (Jean-Philippe Garric dans Boudon 2009: 5)



Le contexte de création de ces archives nous inspire également, car une véritable volonté de créer et d'utiliser des données qui émerge à l'époque (chapitre1.2). Si les moyens n'étaient pas encore disponibles, ni en statistique, ni en cartographie, nous pouvons aujourd'hui en faire l'exercice. Cela nous semble d'autant plus pertinent que l'objectif même des archives est de pouvoir retrouver, retracer et saisir le travail de l'administration qui l'a produite. Dans l'idéal de transparence et de traçabilité d'un état-nation dont l'administration est au service du public, les archives documentent les actions et sont mises à disposition pour permettre une sorte de vérification par le public. 

### 3.1.2 Cartographie critique, profanation et détournment 

Les approches quantitatives et spatiales se combinent aisément 



<!-- verhoeven? =/= utiliser les données pour montrer ce qu'on sait déjà, mais propose une approche critique -->

#### critique de la carto, miroir, inverser opération

l'administration comme une "opération d'objectivation [...] qui remplace des objets et le monde par des référentiels" (Sabatier)

contre-administration? comment inverser cette opération objectivation pour retrouver, sous une forme théorique, ces objets et le monde. 

Réflexion inspirée par la contre-cartographie: utiliser les instruments du pouvoir contre lui pour révéler son fonctionnement (invert), ses éventuels biais



#### Profanation, détournement et contre-cartographie: approche critique

les archives (et les données) sont le produit d'une administration --> un type de raisonnement

Utiliser ce dispositif pour développer une approche critique de l'action de cette administration via les traces qu'elles nous a laissées, c'est-à-dire ses archives



utiliser et s'approprier les dispositifs de l'administration et du gouvernement: cartographie et statistique, pour identifier ses critères, sa logique



### 3.1.3 De la cartographie à la visualisation de données

intérêt pour la cartographie --> pensée spatiale liée au côté topographique des données, mais aussi à une envie de percevoir les dynamiques et changements, à travers le temps et l'espace. 



Afin de parvenir à un tel résultat, il nous paraît d’abord nécessaire de « déconstruire » la carte, comme nous y invite le géographe et historien de la cartographie postmoderne Brian Harley (1989a). Ce processus a pour objectif de briser le lien entre réalité et représentation dans l’interprétation et l’analyse de la pratique cartographique. Il permet ainsi de révéler de nouvelles approches de la carte et de retracer les mécanismes sociaux liés à sa production. Nous prenons ici appui sur les réflexions du philosophe et historien Jean-Marc Besse, qui propose une conception pragmatique de la carte et, par extension, de l’acte cartographique :

> 1. Toute carte est en même temps une interprétation et un projet vis-à-vis du territoire auquel elle réfère, autrement dit toute carte se présente comme une version possible du territoire. 
> 2. Toute carte est la traduction et la condition d’un pouvoir qui cherche à s’exercer socialement et culturellement, et qui s’appuie sur la carte pour s’assurer une forme d’autorité. 
> 3. Toute carte développe sa stratégie par l’intermédiaire de la mise en œuvre d’un univers graphique au sein duquel elle construit son discours, un espace graphique qui n’est rien d’autre que la mise en forme d’un territoire de référence au sujet duquel le discours est construit. (Besse, 2006: 8)

Notre approche de la cartographie a donc pour but de rendre visibles les dimensions interprétatives et graphiques de la carte en investiguant le potentiel du format numérique et interactif. Il s’agit aussi d’essayer de présenter un modèle alternatif de production du savoir en histoire de l’art en usant du caractère visuel et spatial de la carte. L’utilisation de l’interactivité, dont il sera question dans la troisième partie de cet article, nous permet de contrer certains effets d’autorité causés par l’illusion d’une objectivité scientifique et cartographique (Harley, 1989b: 82). Il demeure toutefois essentiel, tout au long de ce processus, de tenir compte des formes de pouvoir impliquées par la création de l’interface et de situer le savoir ainsi produit.

Le traitement des données de Conbavil forme un espace cartographique composé de multiples épaisseurs. D’une part, il est constitué d’un territoire de référence physique, la France de la première moitié du XIXe siècle, sur lequel s’applique une politique architecturale. D’autre part, les archives administratives font partie intégrante du territoire et participent elles aussi à le construire. La cartographie fournit ainsi « une méthode pour unir dans une image le concept d’un territoire et une multitude d’informations dites empiriques livrées par la fréquentation du terrain » (Besse, 2006: 15). Aux informations « empiriques », nous substituons des données issues de sources archivistiques, lesquelles se trouvent enrichies par la géolocalisation que nous leur adjoignons. Notre processus cartographique vient ainsi réinscrire l’action du Conseil des bâtiments civils sur le territoire français et révéler son empreinte sur le pays. Au-delà de l’impact du patrimoine bâti sur le territoire, nous prenons aussi en compte les projets refusés ou inaboutis. Leur cartographie nous invite « à voir et à penser ce que l’on ne voit pas et ne pense pas quand on regarde l’espace réel » (Jacob, 1992: 50). L’imaginaire bâtisseur de l’époque se matérialise par ses archives et nous offre une autre facette de l’histoire de ce territoire. Nous cherchons ainsi à mettre en pratique la pensée de l’historien de l’art Dario Gamboni, selon qui,

> [p]our comprendre l’histoire d’un lieu, il importe de connaître non seulement ce qu’il a été possible d’y réaliser, mais encore ce qu’il était impossible d’y faire pour des raisons esthétiques et culturelles, techniques, sociales ou encore politiques. (2008: 9) 

L’historien Christian Jacob théorise la relation entre archives et cartographie dans son ouvrage majeur, *L’Empire des cartes* (1992). Il y présente un projet de recherche sur les prénoms mené par la *Rencontre des historiens du Limousin*[6](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote6_3hkkf7g). Dans le contexte d’un dépouillement massif d’archives, ces chercheur·se·s soulignent le potentiel épistémologique de l’usage de la cartographie pour « le quantitatif et l’étude de l’organisation spatiale des phénomènes » (Pérouas, 1984: 3). Dans le cadre d’un tel projet, la carte devient un instrument d’enquête pour l’historien·ne : elle « ne renvoie pas à une réalité visible sur le terrain — en revanche, elle permet de visualiser différemment des centaines d’archives dépouillées par les historiens » (Jacob, 1992: 32). Dans le cas du Conseil des bâtiments civils, plus de 26 000 affaires situées dans 4 200 lieux sont organisées selon une logique encore enfouie dans les sources. La cartographie de ces éléments nous permet de discerner leur organisation spatiale et de renouveler ainsi la compréhension de l’administration de l’architecture publique française au lendemain de la Révolution.

En outre, nous élargissons cette approche cartographique pour y inclure des formes visuelles qui ne sont pas spécifiquement topographiques, notamment des diagrammes. C’est pourquoi nous préférerons employer le terme « figuration » à celui de « représentation » pour parler de l’image produite par la cartographie : « [L]a figuration est le dessin d’un objet qui ne préexiste pas à son image, alors que l’usage courant du mot représentation fait de celle-ci la reproduction d’une réalité préexistante. » (Besse, 2006: 12) Rappelant l’étymologie du mot « diagramme », Jean-Marc Besse définit la carte comme « une *eikôn* d’un genre particulier » qui « nous renvoie d’une part à un acte d’écriture (*gramma*, relation avec *graphein*) et d’autre part [à] un acte d’articulation logique (*dia*-, à la fois distinguer et relier, enchaîner ce qui est distingué) » (2006: 15). L’assemblage de ces actes de figuration, d’écriture et d’articulation logique nous permet de définir la visualisation de données comme une forme de pensée visuelle qui figure un imaginaire raisonné et construit.



## 3.2 Pratiques de visualisation et de cartographie

L’exploitation des données de Conbavil que nous proposons prend diverses formes diagrammatiques : cartographie, mais aussi chronologie et typologie. Ces formes visuelles sont réexaminées à travers l’utilisation d’un nouveau format de production : la visualisation interactive. Grâce aux technologies du web 2.0 et particulièrement à la bibliothèque JavaScript D3.js, les données sont converties en graphiques directement dans le navigateur. Ces *data-driven visualizations* sont programmées pour s’animer sous l’action de l’utilisateur, qui peut ainsi sélectionner les données à afficher ou régler le niveau de détail lors de sa consultation (Bostock, 2019a). Dès lors, chaque visualisation devient une proposition, une vue sur les données. La perspective change selon la caractéristique mise de l’avant par le graphique : la géolocalisation pour la carte, la date de discussion de l’affaire pour la chronologie et le type architectural pour la classification hiérarchique rayonnante.



#### interactivité, manipulation

Nous voulons faire des données de CONBAVIL des objets à manipuler pour les chercheur·se·s.  ==> d3.js, visualisation interactive

=/= mise en page mais mise en scène de l'information [drucker] ; 

table de travail ou table de montage [Didi-huberman] " introduit le multiple, le divers, l'hybridité de tout montage"



### 3.2.1 Cartographie

Pour la carte, nous partons des informations spatiales renseignées dans Conbavil, c’est-à-dire du nom des communes pour lesquelles des projets architecturaux ont été examinés par le Conseil des bâtiments civils. Nous sommes ainsi parvenue à établir une liste d’emplacements que nous avons ensuite géolocalisés[7](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote7_mdql4ec). Lors de la production de la carte, chaque commune est figurée par un point dont la taille est proportionnelle aux nombres d’affaires la concernant. Le fond de carte sélectionné est un découpage de la France en départements datant de 1831[8](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote8_wb1lc8q). Celui-ci situe les communes tout en restant dans une relative abstraction, ce qui favorise la lisibilité de la carte. Les limites départementales offrent un repère géographique tout en rappelant le contexte historique. Il serait bien entendu préférable de disposer d’un fond de carte qui rende compte des évolutions des divisions administratives du territoire au cours des années, mais, malheureusement, ce jeu de données géo-historiques n’est pas encore disponible pour la France de cette époque.

<iframe src="https://www.public.archi/atlas-numerique/viz/carteCommunes/index.html" title="Lena Krause, *[Carte des départements français et densité des projets Conbavil](https://www.public.archi/atlas-numerique/viz/carteCommunes/index.html)* (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal "</iframe>



Cette carte permet ainsi de mener, pour la première fois, une analyse visuelle, spatiale et quantitative des données de Conbavil. Une étude primaire révèle que son agencement est le reflet de la hiérarchie administrative française. Le plus grand nombre des affaires traitées par le Conseil se situent dans la capitale administrative du pays, Paris. Les projets majeurs sont regroupés dans les chefs-lieux des départements, tandis que les autres communes répertoriées font seulement l’objet de quelques délibérations, habituellement pour des affaires de moindre envergure. Ce constat fait écho à notre critique des cartes produites par Teyssot et Érouard. Cependant, l’interactivité de la carte lui confère un tout autre potentiel. L’utilisateur peut sélectionner un ou plusieurs lieux et afficher les affaires concernées[9](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote9_qmnigzo). La carte n’est plus une fin en soi, mais devient un moyen de plonger dans les archives.



### 3.2.2 Chronologie

La deuxième visualisation cible quant à elle les données temporelles. À partir du code de Mike Bostock, créateur de la bibliothèque D3.js (2019b), nous avons généré une chronologie des séances du Conseil précisant le nombre de projets évalués à chaque occurrence. Ce graphique permet ainsi de rendre compte de la fréquence des séances du Conseil et de la quantité d’affaires traitées au fil du temps. Grâce à la fonction de zoom, l’utilisateur peut modifier l’axe chronologique et examiner de manière détaillée des intervalles temporels plus restreints. En dessous de cette visualisation, la légende, qui est elle-même un graphique, sert de repère. Elle situe la section visualisée et propose un autre moyen de parcourir la chronologie. Malgré tout l’intérêt de ces manipulations, l’illusion de continuité que cette figure pourrait donner à l’utilisateur constitue un problème important. En effet, le graphique génère une courbe qui relie les événements entre eux. C’est la raison pour laquelle nous avons choisi une courbe en escalier[10](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote10_pc6hjgr), qui crée des paliers entre chaque élément, pour essayer de discrétiser l’information, c’est-à-dire la séparer en des unités distinctes. Le problème persiste néanmoins en partie, car il n’est pas possible de distinguer les séances consécutives ayant le même nombre de délibérations. En outre, on ne peut pas visualiser les interruptions dans les sources : par exemple, il n’y a pas de séance entrée dans la base de données entre le 8 octobre 1833 et le 3 janvier 1834, mais la ligne continue suggère un nombre stable de délibérations pendant toute la période.

<iframe src="https://www.public.archi/atlas-numerique/viz/chronologie/index.html" title="Lena Krause, [*Chronologie des séances du Conseil des bâtiments civils*](https://www.public.archi/atlas-numerique/viz/chronologie/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal "</iframe>



Pour répondre à ces inconvénients, nous avons conçu un diagramme en bâtons. Dans cette visualisation, chaque barre représente une séance et sa hauteur le nombre de délibérations. La sélection d’une barre par un clic active l’affichage des délibérations concernées. Le repérage de la séance exacte à laquelle une affaire a été évaluée offre un contexte important, car le Conseil a parfois traité plus de cinquante dossiers au cours d’une même séance, tandis que d’autres sont consacrées exclusivement à un seul projet. Toutefois, cette visualisation présente elle aussi un problème évident de lisibilité. Limitée par son affichage sur la largeur d’un écran d’ordinateur, il nous est impossible d’y faire apparaître de façon claire les quelques 4000 séances du Conseil tenues entre 1795 et 1840. La fonction de zoom ne permet pas de changer d’échelle, uniquement d’élargir les dimensions de l’image. Malgré un travail rigoureux des couleurs, la lecture du graphique reste difficile. La solution idéale serait de parvenir à fusionner les deux graphiques en une seule visualisation, qui serait composée des barres et d’un axe chronologique interactif. Il serait également bénéfique d’ajouter quelques grands repères mettant en relation les activités du Conseil avec leur contexte historique, mais seule une connaissance fine des dynamiques politiques et administratives de l’époque permettrait des interprétations concluantes. Pour le moment, nous laissons cette tâche aux spécialistes, qui sauront enrichir la chronologie de leur expertise.

[<img src="http://revuecaptures.org/sites/default/files/styles/demi_largeur/public/Krause_figure_6.png?itok=zkVzrqSd" alt="img" style="zoom:25%;" />](http://revuecaptures.org/sites/default/files/Krause_figure_6.png)

Lena Krause, *Chronologie des séances du Conseil des bâtiments civils* (détail) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal

<iframe src="https://www.public.archi/atlas-numerique/viz/barChart/index.html" title="Lena Krause, [*Séances du Conseil des bâtiments civils*](https://www.public.archi/atlas-numerique/viz/barChart/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal "</iframe>



### 3.2.3 Typologie

Finalement, nous avons puisé dans les informations d’ordre typologique compilées dans Conbavil. Les chercheur·se·s chargé·e·s du dépouillement de ces données ont catégorisé les affaires évaluées par le Conseil selon leur type architectural, en se référant au *Thésaurus de la désignation des œuvres architecturales et des espaces aménagés* (Vergain, 2015)[11](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote11_pdz4gfe). Ce dernier classe les productions architecturales selon une typologie allant jusqu’à huit niveaux de détail. Par exemple, dans la catégorie « génie civil » figure la sous-catégorie « ouvrage d’art », qui elle-même contient « pont », « égout » ou « quai ». Ce système arborescent est judicieusement visualisé dans la version interactive du graphique circulaire à plusieurs niveaux, ou *Sunburst* (Bostock, 2018a), que nous avons élaboré. Chaque niveau est composé de catégories dont la largeur figure les proportions respectives. Étant limité à deux niveaux apparents, le diagramme maintient une grande lisibilité tout en donnant accès à un contenu plus détaillé par la voie de l’interactivité (Bostock, 2018b). Cette visualisation des données de Conbavil fournit ainsi une représentation visuelle du *Thésaurus*, qui, jusqu’à présent, ne pouvait être parcouru qu’en suivant une structure hiérarchique d’hyperliens.

<iframe src="https://www.public.archi/atlas-numerique/viz/sunburst/index.html" title="Lena Krause, [*Répartition des projets Conbavil par type architectural*](https://www.public.archi/atlas-numerique/viz/sunburst/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal "</iframe>

Lena Krause, [*Répartition des projets Conbavil par type architectural*](http://atlas.lenamk.site/viz/sunburst/) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal 

Notre soleil interactif Conbavil présente donc le contenu de la base de données par type architectural. Le fait de cliquer sur une catégorie permet de faire apparaître le niveau de profondeur suivant et le retour en arrière s’effectue en cliquant au centre du graphique. En glissant le curseur sur une catégorie, on peut voir le nombre de délibérations qui y sont associées. Rapidement, on constate que plus de la moitié des délibérations sont contenues dans trois catégories principales : « urbanisme », « architecture religieuse » et « architecture judiciaire, pénitentiaire ou de police ». La section « urbanisme » contient toutes les délibérations liées aux plans d’alignement des villes, car le Conseil était également responsable de l’ouverture des rues pour l’assainissement et l’embellissement des espaces publics (Château-Dutier, 2016, T1: 151-179). La prépondérance de l’architecture religieuse s’explique quant à elle par le grand nombre de réaffectations de bâtiments nationaux en écoles, préfectures et tribunaux, notamment (Woolf, 1987: 30-31).

La carte comme le soleil sont des graphiques cumulatifs, ce qui signifie que certaines délibérations y figurent plusieurs fois si elles sont associées à plusieurs lieux ou types architecturaux. Cette décision provient, entre autres, d’une incertitude dans les données, qui ne signalent pas de hiérarchie en cas d’attribution multiple. Il faut également garder à l’esprit que la carte, par exemple, ne représente pas le phénomène bâtisseur, mais reflète plutôt les délibérations du Conseil. La taille des points dépend donc du nombre de mentions lors des séances et non de la quantité de chantiers ouverts. Les graphiques créés sont exploratoires, ils ont pour but de mener à la découverte du contenu des archives. C’est pourquoi il nous a semblé pertinent d’offrir le plus grand nombre de points d’entrée possibles dans les données.



#### statut des visualisation: 

ne sont jamais présentées comme des fins en soi ... mais plutôt comme une matière pour l'élaboration intellectuelle ̣- mouvante et incarnée dans divers modes d'inscrption, mobilisant en même temps les nouveaux outils et des séquences de pratiques et des protocloes de travails existants. Les images produites ne sont ainsi pas uniquement conçues comme des outils d'interprétation, mais aussi de tri, de paramétrage, voire même d'enrichissement et de transformation des données (caviglia 2014)



## 3.3 Editorialisation : atlas

### 3.3.1 Théorie ( )

- jacob, besse, didi-huberman
- interactivité, manipulation

### 3.3.2 Interface ( 3.1.4??)

- Christian Jacob, *Lieux de savoir* 2013

Instrumentation de la recherche: défi : interaction en vue de développer "les environnements logiciels qui permettront d'entreprendre ce travail expérimental sur les données. Élaborer des outils spécifiques et pointus, répondant à des logiques intellectuelles particulières

- potentiel d'instruments de visualisation qui [...] permettraient de mettre à l'épreuve des hypothèses de travail en temps réel " ( Jacob 2013: cf lien ./1180) 
- besoin de faire varier la focale, de passer du local au global et inversement, mais aussi de passer d'une visualisation à l'autre "à mes yeux, l'environnement de recherche numérique idéal permettrait de passer d'une forme de visualisation à l'autre, d'un point de vue à l'autre. Il permettrait de mettre à l'épreuve en temps réel des hypothèses de travail, de procéder par des expérimentations successibes
- défi principal de l'instrumentation de la recherche aujourd'hui me semble être celui de la transitivité et de la fluidité
- réflexion critique sur les instrumentations de la recherche, sur les ergonoies des nouveaux outils, sur la manipulation et l'exploitation intellectuelle des documents qui s'accumulent chaque jour davantage sur nos disques durs

Outre exemples déjà donné: EAT ...

#### Sinclair et al]: rich-prospect interfaces 

#### Exemple: Presner et al :temporal topographies

épaisseur des cartes --> 

- temporalité
- manipulation 
- multiplicité des perspectives



### 3.3.3 L’atlas numérique comme instrument de recherche

Les visualisations que nous présentons ici constituent une première étape dans notre processus de recherche. Telle une machine bâtisseuse, la politique d’équipement de la France est, à la période qui nous intéresse, un engrenage dont les besoins et les contraintes se reflètent dans sa chronologie, dans son organisation spatiale et dans ses choix d’infrastructure. Nous cherchons donc, afin d’étudier son fonctionnement, à concevoir un instrument de recherche à partir de nos visualisations.

Des liens entre les visualisations ont été tissés à deux niveaux. Tout d’abord, celles-ci sont regroupées dans un même espace éditorial qui reprend le modèle de l’atlas. Christian Jacob définit l’atlas géographique comme un « dispositif qui permet de concilier le tout et le détail. Il est régi par une logique cumulative et analytique, qui conduit de la vision globale aux images partielles » (1992: 97). La forme-atlas est transformée lors de sa reprise par des artistes ou par des historien·ne·s de l’art. Dans ce domaine, il peut devenir, selon Georges Didi-Huberman, une « forme visuelle du savoir » comportant « [un] paradigme *esthétique* de la forme visuelle, et [un] paradigme *épistémique* du savoir » (2011: 12). Sa réception est une activité non linéaire : on ne *lit* pas mais on *consulte* un atlas. Cette particularité autorise l’émergence d’une forme de « connaissance par l’imagination » grâce à « la puissance intrinsèque du *montage* qui consiste à découvrir […] des liens que l’observation directe est incapable de discerner » (13). En somme, regrouper les visualisations produites à partir des archives numérisées du Conseil des bâtiments civils dans un atlas numérique crée un espace propice à la réflexion et à la recherche.

<iframe src="https://www.public.archi/atlas-numerique/viz/carteAvis/index.html" title="Lena Krause, [*Exemple d’interactivité entre deux visualisations : carte et avis du Conseil*](https://www.public.archi/atlas-numerique/viz/carteAvis/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal "</iframe>



Des liens dynamiques intégrés dans le code permettent de relier entre elles les différentes composantes de l’atlas. Chaque graphique est créé à partir du même jeu de données. Nous avons donc pu mettre en place un système qui reproduit la sélection d’un sous-ensemble (d’un intervalle chronologique, d’un lieu ou d’une catégorie architecturale) dans les autres visualisations. Offrant d’abord un aperçu global, les visualisations se transforment ensuite au fur et à mesure du parcours interactif en des perspectives de plus en plus détaillées, qui descendent en profondeur jusqu’à la consultation d’une seule affaire. Chaque action de l’utilisateur, guidée par ses hypothèses et par ses réflexions, façonne donc la constellation que forment les données dans l’atlas. La manipulation aide la chercheuse ou le chercheur à analyser le contenu de Conbavil et l’invite à émettre des hypothèses sur sa signification. Pour le moment, ces liens dynamiques sont implémentés entre la carte et un graphique des avis du Conseil. Initialement, tous les lieux sont sélectionnés et le graphique figure l’ensemble des affaires. On peut ensuite modifier la sélection de lieux, ce qui entraîne un ajustement du graphique des avis. Et, inversement, la sélection d’un avis se reflète automatiquement sur la carte[12](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote12_ajhxl80). On peut ainsi observer de façon spatiale, grâce à ces liens, les dispositions du Conseil face aux projets soumis. Aussi, la dynamique entre les visualisations permet l’étude de phénomènes par la recherche des corrélations : par exemple, les membres du Conseil étaient réputés intransigeants avec les architectes de province jugés « peu capables » (Château-Dutier, 2016, T2: 591), allant jusqu’à corriger leurs projets à grands coups de crayon sur les plans fournis. Nous pouvons rechercher ce phénomène dans l’atlas, en modifiant la sélection des avis et des lieux, afin d’identifier d’éventuelles régions où le taux de refus ou de modification serait plus élevé.

Notre atlas est encore à un stade embryonnaire et il ne présente pour le moment que quelques liens actifs entre deux visualisations. Cependant, la poursuite de ce travail à l’échelle de toutes les visualisations, permet d’augmenter de façon exponentielle le nombre de constellations de données que l’utilisateur peut découvrir. De l’association entre ces innombrables possibilités et l’imagination de l’utilisateur émerge un dispositif qui active « la puissance intrinsèque du *montage* » évoquée précédemment (Didi-Hubermann, 2011: 13). L’espace de l’atlas s’organise autour d’une structure éditoriale déterminée par son autrice, tout en se transformant en fonction de l’action de son utilisateur. Si la consultation d’un atlas papier est contrainte par les éléments structurels et les repères de l’ouvrage imprimé, les lecteur·rice·s sont libres de naviguer au sein de son contenu, de suivre la proposition des éditeur·rice·s ou de se laisser porter par la sérendipité de consulter l’atlas au hasard des pages. Et ces mêmes possibilités se présentent dans notre proposition d’atlas numérique : l’utilisateur est libre d’explorer le contenu à sa guise, malgré un cadre défini d’actions possibles dans l’interface. La sérendipité, quant à elle, est permise lors des déambulations du curseur dans l’interface, lors de la sélection aléatoire d’un sous-ensemble de données, ou encore lors de l’affichage à l’écran d’une constellation de données produite au hasard[13](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote13_n6q5i5d).

[![img](http://revuecaptures.org/sites/default/files/styles/demi_largeur/public/Krause_figure_10.png?itok=LCoY6crr)](http://revuecaptures.org/sites/default/files/Krause_figure_10.png)

Lena Krause, *Modélisation de l’atlas* (2019) , Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal 

La création d’une nouvelle interface pour la base de données Conbavil sous la forme d’un atlas peut être comprise comme un acte d’éditorialisation[14](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote14_psr6wnd). Il s’agit d’une démarche processuelle, expérimentale et surtout multiple (Vitali-Rosati, 2016: 68). La visualisation et la cartographie ont considérablement évolué avec l’apparition des logiciels et outils informatiques. D’après les historiennes Claire Lemercier et Claire Zalc, « il n’est plus question de publier chaque tableau ou graphique péniblement obtenu, mais plutôt de les utiliser pour avancer dans une recherche, quitte à n’en montrer au lecteur final que quelques-uns » (2008: n.p.). Comparativement aux grandes équipes de chercheur·se·s, ingénieur·e·s, informaticien·ne·s, cartographes et perforateur·rice·s de cartes, indispensables aux grandes enquêtes collectives menées dans les années 70, il est de nos jours possible de réduire le personnel, le temps, les connaissances et les coûts nécessaires à la création de cartes (Lemercier, 2008)[15](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote15_7tulxje). Cela favorise particulièrement l’expérimentation, tant avec les formes et les variables graphiques qu’avec les calculs et les statistiques privilégiés pour la cartographie thématique. Aussi, les nombreuses itérations possibles au cours du processus de production nous invitent à repenser chaque élément jusqu’à ce qu’il convienne aux besoins du projet.

### 3.3.4 Editorialisation ( )

- Editorialisation et enjeux
- Instrument de recherche 

Il serait tentant de penser que l’interactivité de l’atlas déconstruit des enjeux de pouvoir dans le champ du savoir. Il ne faut toutefois pas oublier les choix effectués lors de sa production. Du point de vue du contenu, les archives sont produites par des instances dans un contexte historique déterminé, à savoir une administration française issue de la première moitié du XIXe siècle pour le Conseil des bâtiments civils. La base de données, pour sa part, est issue du travail de chercheur·se·s au tournant du XXIe siècle. Les connaissances obtenues à partir de ces données ne représentent donc pas une vérité, mais plutôt un point de vue[16](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote16_5pi61ps). En ce qui concerne l’interface de l’atlas, son élaboration se base sur diverses institutions, telles que Open Street Map pour le géoréférencement ou le thésaurus architectural de l’Inventaire général du patrimoine culturel. Ces références formatent le contenu selon des ontologies du savoir précises, des perspectives dont il n’est pas impossible de remettre la pertinence en cause. Par exemple, la toponymie contemporaine peut s’avérer problématique dans le cadre d’études historiques. Il faut donc garder à l’esprit les formes de pouvoir et d’autorité qui subsistent dans la production du savoir de notre atlas. C’est la raison pour laquelle nous souhaitons encourager la réutilisation et l’appropriation de son code en le publiant sous une licence libre[17](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote17_bnrpj0k). L’objectif est de faciliter les ajouts, les modifications et les contre-propositions, ainsi que la réutilisation du code pour d’autres projets. Nous savons que cela nécessite un niveau de littératie numérique encore peu répandu parmi les chercheur·se·s en histoire de l’art. Cependant, grâce à l’accessibilité et à la transparence de notre dispositif, nous invitons celles et ceux qui seraient intéressé·e·s à se former par la pratique, ou du moins à développer une compréhension plus fine du code afin de pouvoir, éventuellement, y apposer un regard critique.

Si la construction de notre atlas est un processus en constante évolution, nous pensons avoir démontré le potentiel de la cartographie et de la visualisation pour transformer l’étude d’une base de données. L’interface visuelle et interactive de l’atlas numérique offre une approche inédite du contenu des archives du Conseil des bâtiments civil et permet de renouveler la recherche en faisant usage des méthodes numériques disponibles aujourd’hui. À la manière du millefeuille topographique imaginé par Dario Gamboni, l’atlas plonge l’utilisateur dans « [des] profondeur[s] qui invite[nt] à l’excavation » (2008: 6). Il reste cependant ancré dans des préoccupations contemporaines à ses sources, afin de se distancier d’éventuels anachronismes que l’écart entre les archives du XIXe siècle et les nouvelles technologies du web appliquées à une base de données pourraient générer. S’il n’est pas toujours évident de savoir comment se servir des données dans la recherche en histoire de l’art, la cartographie et la visualisation se révèlent être des instruments précieux dans le contexte numérique.

