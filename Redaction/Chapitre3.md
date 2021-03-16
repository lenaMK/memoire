#  Chapitre 3

Nous voulons désormais créer un espace de travail pour l'exploration et l'interprétation des données de CONBAVIL. Il s'agit de concevoir un dispositif exploratoire qui a pour source d'inspiration les questions de recherche évoquées par les chercheur·se·s impliqué·e·s dans la création de la base, l'historiographie des recherches sur le sujet, le contexte historique, c'est-à-dire la statistique, la cartographie thématique et la rationalisation administrative. Nous cherchons, dans un premier temps, des concordances entre ces questions et les moyens méthodologiques et technologiques à notre disposition. Nous expérimentons ensuite avec leur mise en pratique de façon isolée, avant de les rassembler dans un espace éditorial commun: l'atlas numérique de l'architecture publique en France (1795 - 1840). Cet atlas est à la fois un outil de réflexion théorique autour des enjeux d'éditorialisation et de conception d'interfaces de recherche, et un micro-prototype issu de l'application pratique de ces opérateurs théoriques. 

## 3.1 Espaces et interprétation des données 

Une interface donne forme aux données, elle dicte donc notre façon d'y réfléchir et les questions qu'on voudrait y poser. Les interfaces produisent des affordances épistémologiques parce qu'elles sont le cadre au sein duquel nous posons nos questions, nos observations, nos hypothèses et nos déductions à propos de la base de données.

Puisqu'il existe déjà un outil d'interrogation, nous voulons plutôt créer un instrument de recherche. Si le premier permet de chercher un contenu spécifique (heuristique) via des requêtes SQL ou l'outil d'interrogation, le second est pensé comme instrument de recherche et dispositif critique qui serait à l'origine de questionnements (herméneutique).

### 3.1.1 Quantitatif, statistique et cartographique

#### Approches quantitatives et statistiques

Notre première piste pour la création de notre instrument de recherche est issue de l'historiographie de la base de données et des archives du Conseil des bâtiments civils. Nous souhaitons poursuivre et étendre les recherches quantitatives ou statistique, ainsi que la dimension spatialisée des travaux de Georges Teyssot et Bernard Lepetit (ch1.3.3), ce qui est désormais non seulement rendu possible mais aussi facilité par CONBAVIL. Les données sont géolocalisées et d'indexées en catégories et sous-catégories architecturales, il reste à décider de la méthode à employer. 

Nous puisons également dans le contexte de création de la base de données pour les méthodes de recherches encore inexploitées. Quand il introduit CONBAVIL à l'occasion de sa mise en ligne en 2009, l'historien de l'architecture Jean-Phlippe Garric détaille l'énorme potentiel de cette base de données pour la recherche. 

> Cette base de données [...] nous conduit à imaginer des enquêtes et des travaux jadis presque impossibles, ouvrant des
> perspectives inédites sur des analyses quantitatives, économiques ou typologiques, sur des comparaisons entre régions ou sur les rapports Paris-Province, sur le mouvement de codification des règlements et des marchés de travaux, sur les combats de l’art et de la nécessité, du local et du national. (Jean-Philippe Garric dans Boudon 2009: 5)

Le contexte de création de ces archives nous inspire également, car une véritable volonté de créer et d'utiliser des données qui émerge à l'époque (chapitre1.2). Si les moyens n'étaient pas encore disponibles, ni en statistique, ni en cartographie, nous pouvons aujourd'hui en faire l'exercice. Cela nous semble d'autant plus pertinent que l'objectif même des archives est de pouvoir retrouver, retracer et saisir le travail de l'administration qui l'a produite. Dans l'idéal de transparence et de traçabilité d'un état-nation dont l'administration est au service du public, les archives documentent les actions et sont mises à disposition pour permettre une sorte de vérification par le public. 

[quantitatif versus statistique au sens méthodologique. Pourquoi c'est peu présent, pas exploité alors que c'est disponible et facilement faisable --> n'est pas dans l'intérêt de recherche, plus axé sur la pensée visuelle et la cartographie que sur jouer avec des chiffres]

[à compléter: i guess maybe somewere talk about geography of art? or not...]

#### Formes de pensée cartographique 

Les approches quantitatives se combinent aisément à la cartographie lors que les données possèdent une dimension spatiale. Nous avons donc entrepris les recherches théoriques et pratiques nécessaires pour cartographier les données de CONBAVIL. Nous avons appui sur les réflexions du philosophe et historien Jean-Marc Besse, qui propose une conception pragmatique de la carte et, par extension, de l’acte cartographique :

> 1. Toute carte est en même temps une interprétation et un projet vis-à-vis du territoire auquel elle réfère, autrement dit toute carte se présente comme une version possible du territoire. 
> 2. Toute carte est la traduction et la condition d’un pouvoir qui cherche à s’exercer socialement et culturellement, et qui s’appuie sur la carte pour s’assurer une forme d’autorité. 
> 3. Toute carte développe sa stratégie par l’intermédiaire de la mise en œuvre d’un univers graphique au sein duquel elle construit son discours, un espace graphique qui n’est rien d’autre que la mise en forme d’un territoire de référence au sujet duquel le discours est construit. (Besse, 2006: 8)

Notre relevons ici l'importance de rendre visibles les dimensions interprétatives et graphiques de la carte, précepte qui ressort également d'un autre opérateur théorique que nous souhaitons employer, la cartographie critique. 

La cartographique critique est un mouvement de pensée né dans les années 1990, avec pour référence l'article pionnier "Deconstructing the Map" (1989) du cartographe historien Brian Harley. Il y propose de déconstruire la carte – au sens postmoderne, un procédé qui permet de briser le lien entre réalité et représentation – afin d’encourager un tournant épistémologique dans l’interprétation et l’analyse de la pratique cartographique. Le processus de déconstruction permet de révéler de nouvelles approches de la carte et de retracer les mécanismes sociaux liés à sa production.

Harley met tout d’abord le système de la cartographie en relation avec celui du discours selon Foucault, c’est-à-dire un système de possibilités qui produit de la connaissance. En dérive la question des règles qui régissent ce système. L'auteur identifie deux ensembles de règles qui sous-tendent et dominent l’histoire de la cartographie occidentale depuis le XVIIème siècle. La première concerne la production technique des cartes et les règles scientifiques de la production de connaissances. La seconde contextualise la production cartographique dans sa dimension culturelle, les cartes respectant les codes de la société qu’elles représentent tout en les renforçant. Sous le masque de la neutralité scientifique se révèle une image construite non seulement à partir de mesures d’un monde phénoménologique mais également à partir de l’ordre social qui régit ce monde.

En deuxième partie, la déconstruction selon Derrida permet d’analyser en détail le texte cartographique. Dans les marges et les écarts du modèle normatif, Harley identifie la dimension symbolique du fait cartographique. La cartographie est par nature un art de la communication persuasive. Le texte cartographique est donc un texte rhétorique qui utilise les codes à disposition afin communiquer au mieux le mythe qu’il cherche à propager. La rhétorique et la science ne sont pas opposées mais considérées comme deux éléments constitutifs et révélateurs lors de l’analyse de l’objet cartographié.

La troisième partie de l’article analyse les dimensions sociales et politiques de la cartographie. De retour en territoire Foucaldien, la carte est comprise comme une forme de savoir-pouvoir dans la société. Le pouvoir de la carte peut être externe, lié au pouvoir politique, ou interne, en relation avec l’impact politique de la pratique du cartographe. Ce dernier n’exerce pas son pouvoir directement sur les individus, mais sur le savoir à leur disposition. Il faut alors envisager l’impact de ces images dont la neutralité n’est plus concevable. 

Le changement épistémologique proposé dans cet article rapproche selon nous la discipline de Harley de la nôtre. En effet, l’historien de la cartographie comme l’historien de l’art ne produit pas les objets de sa discipline. Cette distance critique avec l’objet étudié permet de révéler puis analyser le contexte culturel et les règles de production de ces objets. 

Le mouvement de cartographie critique a ensuite mené à une nouvelle pratique, la contre-cartographie. La carte, dispositif politique et instrument de savoir et de pouvoir, est employée pour ébranler le pouvoir et défier les normes. En reversant les postures (qui crée la carte et l'emploie, à qui elle est destinée), on peut permettre une "*political practice of mapping back*" (Halder, Michel dans Kollektiv Orangotango+ 2018: 13). La proposition est d'utiliser les instruments du pouvoir contre lui, pour révéler son fonctionnement et ses biais, ainsi que pour inverser les rapports de pouvoir.

#### Profanation et détournement de l'archive administrative? 

Cette notion d'inversion et de renversement des pouvoir est également réfléchie par Giorgio Agamben en relation aux dispositifs. Le terme "dispositif" est employé par Foucault dans pour parler de 

> "manipulation des rapports de force, d'une intervention rationnelle et concertée dans ces rapports de force, soit pour les développer dans telle direction, soit pour les bloquer, soit pour les stabiliser, les utiliser. Le dispositif, donc, est toujours inscrit dans un jeu de pouvoir, mais toujours lié à des bornes de savoir, qui en naissent, mais, tout autant, le conditionnent. C'est ça le dispositif: **des stratégies de rapports de force supportant des types de savoir, et supportés par eux**" (Foucaut, *Dits et écrits", vol III, p. 299 sq., dans Agamben 2007: 9-10)

Ces dispositifs de gouvernement, par leur pratiques, leurs discours et leurs savoirs, assujettissent les individus en les rendant "libres" mais dociles (Agamben 2007: 41-42). Agamben propose de se libérer de l'emprise de ces dispositifs, non pas en œuvrant à les détruire mais en les réemployant, afin de les "rendre à l'usage commun" (Agamben 2007: 37-38). Il puise dans l'histoire pour qualifier cette action de restitution au commun et au libre usage - ou ce contre-dispositif - de "profanation" (Agamben 2007: 39-40).

Nous avons étudié, dans le premier chapitre de ce mémoire, le processus de rationalisation au sein de l'administration. La réduction de la réalité à des objets quantifiables et à des dossiers administratifs est définie par Arnaud Sabatier comme une "opération d'objectivation [...] qui remplace des objets et le monde par des référentiels" (2010: 29). L'approche de la cartographie critique vient révéler les vides et les silences dans cette transformation. La contre-cartographie nous amène à nous poser les questions suivantes: est-il possible de procéder à une profanation des archives ou de créer un processus de contre-administration critique? L'ambition est de donner l'instrument de pouvoir - que ce soit la carte, la statistique, ou l'archive - à ceux·elles qui veulent l'étudier ou le question, révélant ainsi ses biais tout en restituant leur usage au "hommes". En nous appropriant les dispositifs de l'administration et du gouvernement, nous pouvons développer une approche critique de l'action de cette administration via les traces qu'elles nous a laissées, c'est-à-dire ses archives.

<!-- lien avec le cadre conceptuel dans l'intro: authority must be questionned, or at least questionnable. Do I need to write it again? -->

<!-- verhoeven? =/= utiliser les données pour montrer ce qu'on sait déjà, mais propose une approche critique -->



### 3.1.2 De la cartographie à la visualisation de données

[intérêt pour la cartographie --> pensée spatiale liée au côté topographique des données, mais aussi à une envie de percevoir les dynamiques et changements, à travers le temps et l'espace. ]

 CONBAVIL forme un espace cartographique composé de multiples épaisseurs. D’une part, il est constitué d’un territoire de référence physique, la France de la première moitié du XIXe siècle, sur lequel s’applique une politique architecturale. D’autre part, les archives administratives font partie intégrante du territoire et participent elles aussi à le construire. La cartographie fournit ainsi « une méthode pour unir dans une image le concept d’un territoire et une multitude d’informations dites empiriques livrées par la fréquentation du terrain » (Besse, 2006: 15). Aux informations « empiriques », nous substituons des données issues de sources archivistiques, lesquelles se trouvent enrichies par la géolocalisation que nous leur adjoignons. Notre processus cartographique vient ainsi réinscrire l’action du Conseil des bâtiments civils sur le territoire français et révéler son empreinte sur le pays. Au-delà de l’impact du patrimoine bâti sur le territoire, nous prenons aussi en compte les projets refusés ou inaboutis. Leur cartographie nous invite « à voir et à penser ce que l’on ne voit pas et ne pense pas quand on regarde l’espace réel » (Jacob, 1992: 50). L’imaginaire bâtisseur de l’époque se matérialise par ses archives et nous offre une autre facette de l’histoire de ce territoire. Nous cherchons ainsi à mettre en pratique la pensée de l’historien de l’art Dario Gamboni, selon qui,

> [p]our comprendre l’histoire d’un lieu, il importe de connaître non seulement ce qu’il a été possible d’y réaliser, mais encore ce qu’il était impossible d’y faire pour des raisons esthétiques et culturelles, techniques, sociales ou encore politiques. (2008: 9) 

L’historien Christian Jacob théorise la relation entre archives et cartographie dans son ouvrage majeur, *L’Empire des cartes* (1992). Il y présente un projet de recherche sur les prénoms mené par la *Rencontre des historiens du Limousin*[6](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote6_3hkkf7g). Dans le contexte d’un dépouillement massif d’archives, ces chercheur·se·s soulignent le potentiel épistémologique de l’usage de la cartographie pour « le quantitatif et l’étude de l’organisation spatiale des phénomènes » (Pérouas, 1984: 3). Dans le cadre d’un tel projet, la carte devient un instrument d’enquête pour l’historien·ne : elle « ne renvoie pas à une réalité visible sur le terrain — en revanche, elle permet de visualiser différemment des centaines d’archives dépouillées par les historiens » (Jacob, 1992: 32). Dans le cas du Conseil des bâtiments civils, plus de 26 000 affaires situées dans 4 200 lieux sont organisées selon une logique encore enfouie dans les sources. La cartographie de ces éléments nous permet de discerner leur organisation spatiale et de renouveler ainsi la compréhension de l’administration de l’architecture publique française au lendemain de la Révolution.

En outre, nous élargissons cette approche cartographique pour y inclure des formes visuelles qui ne sont pas spécifiquement topographiques, notamment des diagrammes. C’est pourquoi nous préférerons employer le terme « figuration » à celui de « représentation » pour parler de l’image produite par la cartographie : « [L]a figuration est le dessin d’un objet qui ne préexiste pas à son image, alors que l’usage courant du mot représentation fait de celle-ci la reproduction d’une réalité préexistante. » (Besse, 2006: 12) Rappelant l’étymologie du mot « diagramme », Jean-Marc Besse définit la carte comme « une *eikôn* d’un genre particulier » qui « nous renvoie d’une part à un acte d’écriture (*gramma*, relation avec *graphein*) et d’autre part [à] un acte d’articulation logique (*dia*-, à la fois distinguer et relier, enchaîner ce qui est distingué) » (2006: 15). L’assemblage de ces actes de figuration, d’écriture et d’articulation logique nous permet de définir la visualisation de données comme une forme de pensée visuelle qui figure un imaginaire raisonné et construit.

L’acte cartographique ajoute également une dimension spatiale au savoir. Non-linéaire, la carte ne dicte pas nécessairement un point de vue unique. Lorsqu’elle est conçue comme un objet de recherche, elle peut démultiplier les perspectives et les échelles tout en accumulant, tel un millefeuille[1](#sdfootnote1sym), les multiples couches temporelles qui composent l’histoire d’un lieu. Avec le développement d’outils informatiques pour la production de cartes numériques puis leur accessibilité au travers des applications web de cartographie comme Google Earth et OpenStreetMap, l’acte cartographique est transformé (Presner, Shepard, et Kawano 2014: 16) . On peut désormais envisager un acte de cartographie « épaisse », *thick mapping* (Presner, Shepard, et Kawano 2014: 15-19) . Cette pratique allie l’approche géographique, les plateformes de cartographies numériques et les pratiques interprétatives de l’histoire pour mettre en place une forme de recherche sur l’espace qui se veut riche, nuancée et pluridimensionnelle. Cette épaisseur cartographique cristallise des opportunités nouvelles « de navigation empirique, d’épistémologie de la représentation et de rhétorique de la visualisation » (Burdick 2012: 46) . Ce tournant spatial promeut une variété d’approches pour analyser et cartographier les fortes imbrications qui existent entre les notions de culture, de pouvoir et d’espace (Presner, Shepard, et Kawano 2014: 53) . La richesse et la complexité des cartes que nous souhaitons produire nécessitent l’utilisation d’un langage graphique expressif. L’utilisation des variables visuelles identifiées par Bertin sera donc d’une grande utilité (Bertin 2013). L’analyse d’exemples et d’antécédents, couplée au processus d’éditorialisation, servira également à déterminer la forme graphique et numérique la plus appropriée pour notre atlas numérique de l’architecture publique.

​	[1](#sdfootnote1anc) Le millefeuille comme analogie des multiples couches temporelles dans une representation topographique est une analogie imagine par Dario Gamboni dans son article *Mille fleurs ou millefeuille? Pour un invetaire à* n *dimensions *(Gamboni 2008)* *



### 3.1.3 Les outils de visualisation et de cartographie numérique

#### Les logiciels

Il existe une gamme d'outil variée pour la visualisation de données et la cartographie numérique. Nous les divisons en trois grandes catégories. La première concerne les logiciels pour la visualisation de données. Une recension récente des outils et logiciels est disponible dans l'ouvrage *Hands-On Data-visualization* publié en 2021 par Jack Dougherty et Ilya Ilyankou (2021: chap 6 - 8) Palladio, développé par le *Research Lab* à Standford, en est un excellent exemple dans le domaine des humanités numériques (Palladio). En chargeant les données dans le logiciel, on peut accéder à différentes vues sur les données - carte, graphe, liste et galerie - qui peuvent être filtrées selon certains critères ou à l'aide de la chronologie générée par les données (Braude 2014). Ce type de logiciel est fait pour être simple d'utilisation et ne requiert pas de connaissances particulières en informatique (même s'il faut au minimum savoir préparer ses données). Nous notons deux inconvénients quant à notre projet d'instrument de recherche. D'une part, le logiciel prédéfinit les vues possibles sur les données. On ne peut pas les adapter ni en ajouter, contraignant ainsi le choix de visualisations à celles mises à disposition. D'autre part, il s'agit d'une utilisation individuelle. On peut enregistrer le projet pour le partager avec d'autres, mais l'accès et la diffusion restent interne au logiciel <!-- on pourrait imaginer faire un iframe vu que c'est web, mais pas sûr qu'on puisse envoyer le package de données ou comment le publier...? -->. 

<img src="https://hestia.open.ac.uk/hestia-data/uploads/2014/10/HestiaPalladioTimeLineTimeSpan1-1024x551.png" alt="Interface Palladio" style="zoom:90%;" />

<!-- if i have time, enter CONBAVIL data into palladio -->

#### Les SIG

La seconde catégorie est propre à la cartographie numérique, il s'agit des systèmes d'information géographique (SIG). Ces logiciels complexes et puissants, tel que [QGIS](qgis.org) et [ArcGIS](https://www.arcgis.com/index.html), doivent être installés sur l'ordinateur des chercheur·se·s. Ils requièrent un apprentissage spécialisé en cartographie numérique mais présentent un vaste attirail d'outil pour spécifier chaque aspect technique et visuel de la carte<!-- dont j'ai bénéficié à l'école d'été du GRSH-UAM en carto numérique-->. Remontant aux années 1960, les SIG d'abord été crées pour une utilisation interne au logiciel qui permet des exports de cartes statiques (png ou pdf). Il existe désormais des extensions qui permettent certaines formes de publication interactive sur le web. Excepté pour QGIS, qui est un logiciel libre, il faut également prendre en compte le coût très élevé pour l'emploi de ces logiciels. 

<img src="./img/QGIS_pop1831.png" alt="qgis_pop_1831" style="zoom: 75%;" />



#### Les librairies de code

La dernière catégorie d'outil sont les librairies de code, telles que Leaflet.js et D3.js. Leur emploi requiert des connaissances en programmation. Une librairie de code est un ensemble d'outils de programmation auxquels on peut faire appel pour coder un projet. Leaflet.js est conçu pour la création de cartes interactives. Nous avons par exemple testé la fonctionnalité qui permet de créer une *heat map* (Leaflet). 

<img src="/home/lenamk/Documents/memoire/Redaction/img/Leaflet_heatMap.png" alt="Environnement Leaflet - CONBAVIL" style="zoom:55%;" />

La librairie D3.js se spécialise quant à elle en *data-driven visualizations* (Bostock, 2019a). Les données sont converties en graphiques directement dans le navigateur. Ces graphiques s'animent sous l'action de l'utilisateur·rice·s, qui peut ainsi sélectionner les données à afficher ou régler le niveau de détail lors de la consultation.

<iframe width="100%" height="500" frameborder="0"
  src="https://observablehq.com/embed/@d3/gallery?cell=*"></iframe>

​    <a href="https://observablehq.com/@d3/gallery" target="_blank" class="return">Lien vers la source</a>
​    

Nous avons établis plusieurs critères pour sélectionner un outil de visualisation et de cartographie pour CONBAVIL. Nous souhaitions, dès le départ, explorer une pluralité de formes visuelles, de la cartographie aux différentes formes de graphiques et de diagrammes. L'accès web et interactif à ces visualisations est également important dans la conception d'un instrument de recherche. Dans l'ensemble, nous voulions privilégier un outil qui permette la création d'un espace de recherche pour les données de CONBAVIL. C'est pourquoi nous avons choisi de travailler avec la librairie d3.js, conçue pour le web et qui offre la plus grande flexibilité et variété dans les formes de visualisation de données ainsi que dans les interactions possibles.

## 3.2 Pratiques de visualisation et de cartographie

L’exploitation des données de CONBAVIL que nous proposons prend diverses formes diagrammatiques : cartographie, mais aussi chronologie et typologie. Chaque visualisation est une proposition, une vue sur les données. La perspective change selon la caractéristique mise de l’avant par le graphique : la géolocalisation pour la carte, la date de discussion de l’affaire pour la chronologie et le type architectural pour la classification hiérarchique rayonnante.

### 3.2.1 Cartographie

Pour la carte, nous partons des informations spatiales renseignées dans CONBAVIL, c’est-à-dire du nom des communes pour lesquelles des projets architecturaux ont été examinés par le Conseil des bâtiments civils. Nous sommes ainsi parvenue à établir une liste d’emplacements que nous avons ensuite géolocalisés[7](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote7_mdql4ec). Lors de la production de la carte, chaque commune est figurée par un point dont la taille est proportionnelle aux nombres d’affaires la concernant. Le fond de carte sélectionné est un découpage de la France en départements datant de 1831[8](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote8_wb1lc8q). Celui-ci situe les communes tout en restant dans une relative abstraction, ce qui favorise la lisibilité de la carte. Les limites départementales offrent un repère géographique tout en rappelant le contexte historique. Il serait bien entendu préférable de disposer d’un fond de carte qui rende compte des évolutions des divisions administratives du territoire au cours des années, mais, malheureusement, ce jeu de données géo-historiques n’est pas encore disponible pour la France de cette époque.

<iframe src="https://www.public.archi/atlas-numerique/viz/carteCommunes/index.html" title="Lena Krause, *[Carte des départements français et densité des projets Conbavil](https://www.public.archi/atlas-numerique/viz/carteCommunes/index.html)* (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal "</iframe>



Cette carte permet ainsi de mener, pour la première fois, une analyse visuelle, spatiale et quantitative des données de CONBAVIL. Une étude primaire révèle que son agencement est le reflet de la hiérarchie administrative française. Le plus grand nombre des affaires traitées par le Conseil se situent dans la capitale administrative du pays, Paris. Les projets majeurs sont regroupés dans les chefs-lieux des départements, tandis que les autres communes répertoriées font seulement l’objet de quelques délibérations, habituellement pour des affaires de moindre envergure. Ce constat fait écho à notre critique des cartes produites par Teyssot et Érouard. Cependant, l’interactivité de la carte lui confère un tout autre potentiel. L’utilisateur peut sélectionner un ou plusieurs lieux et afficher les affaires concernées[9](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote9_qmnigzo). La carte n’est plus une fin en soi, mais devient un moyen de plonger dans les archives.



### 3.2.2 Chronologie

La deuxième visualisation cible quant à elle les données temporelles. À partir du code de Mike Bostock, créateur de la bibliothèque D3.js (2019b), nous avons généré une chronologie des séances du Conseil précisant le nombre de projets évalués à chaque occurrence. Ce graphique permet ainsi de rendre compte de la fréquence des séances du Conseil et de la quantité d’affaires traitées au fil du temps. Grâce à la fonction de zoom, l’utilisateur peut modifier l’axe chronologique et examiner de manière détaillée des intervalles temporels plus restreints. En dessous de cette visualisation, la légende, qui est elle-même un graphique, sert de repère. Elle situe la section visualisée et propose un autre moyen de parcourir la chronologie. Malgré tout l’intérêt de ces manipulations, l’illusion de continuité que cette figure pourrait donner à l’utilisateur constitue un problème important. En effet, le graphique génère une courbe qui relie les événements entre eux. C’est la raison pour laquelle nous avons choisi une courbe en escalier[10](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote10_pc6hjgr), qui crée des paliers entre chaque élément, pour essayer de discrétiser l’information, c’est-à-dire la séparer en des unités distinctes. Le problème persiste néanmoins en partie, car il n’est pas possible de distinguer les séances consécutives ayant le même nombre de délibérations. En outre, on ne peut pas visualiser les interruptions dans les sources : par exemple, il n’y a pas de séance entrée dans la base de données entre le 8 octobre 1833 et le 3 janvier 1834, mais la ligne continue suggère un nombre stable de délibérations pendant toute la période.

<iframe src="https://www.public.archi/atlas-numerique/viz/chronologie/index.html" title="Lena Krause, [*Chronologie des séances du Conseil des bâtiments civils*](https://www.public.archi/atlas-numerique/viz/chronologie/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal "</iframe>



Pour répondre à ces inconvénients, nous avons conçu un diagramme en bâtons. Dans cette visualisation, chaque barre représente une séance et sa hauteur le nombre de délibérations. La sélection d’une barre par un clic active l’affichage des délibérations concernées. Le repérage de la séance exacte à laquelle une affaire a été évaluée offre un contexte important, car le Conseil a parfois traité plus de cinquante dossiers au cours d’une même séance, tandis que d’autres sont consacrées exclusivement à un seul projet. Toutefois, cette visualisation présente elle aussi un problème évident de lisibilité. Limitée par son affichage sur la largeur d’un écran d’ordinateur, il nous est impossible d’y faire apparaître de façon claire les quelques 4000 séances du Conseil tenues entre 1795 et 1840. La fonction de zoom ne permet pas de changer d’échelle, uniquement d’élargir les dimensions de l’image. Malgré un travail rigoureux des couleurs, la lecture du graphique reste difficile. La solution idéale serait de parvenir à fusionner les deux graphiques en une seule visualisation, qui serait composée des barres et d’un axe chronologique interactif. Il serait également bénéfique d’ajouter quelques grands repères mettant en relation les activités du Conseil avec leur contexte historique, mais seule une connaissance fine des dynamiques politiques et administratives de l’époque permettrait des interprétations concluantes. Pour le moment, nous laissons cette tâche aux spécialistes, qui sauront enrichir la chronologie de leur expertise.

[<img src="http://revuecaptures.org/sites/default/files/styles/demi_largeur/public/Krause_figure_6.png?itok=zkVzrqSd" alt="img" style="zoom:25%;" />](http://revuecaptures.org/sites/default/files/Krause_figure_6.png)

Lena Krause, *Chronologie des séances du Conseil des bâtiments civils* (détail) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal

<iframe src="https://www.public.archi/atlas-numerique/viz/barChart/index.html" title="Lena Krause, [*Séances du Conseil des bâtiments civils*](https://www.public.archi/atlas-numerique/viz/barChart/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal "</iframe>



### 3.2.3 Typologie

Finalement, nous avons puisé dans les informations d’ordre typologique compilées dans CONBAVIL. Les chercheur·se·s chargé·e·s du dépouillement de ces données ont catégorisé les affaires évaluées par le Conseil selon leur type architectural, en se référant au *Thésaurus de la désignation des œuvres architecturales et des espaces aménagés* (Vergain, 2015)[11](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote11_pdz4gfe). Ce dernier classe les productions architecturales selon une typologie allant jusqu’à huit niveaux de détail. Par exemple, dans la catégorie « génie civil » figure la sous-catégorie « ouvrage d’art », qui elle-même contient « pont », « égout » ou « quai ». Ce système arborescent est judicieusement visualisé dans la version interactive du graphique circulaire à plusieurs niveaux, ou *Sunburst* (Bostock, 2018a), que nous avons élaboré. Chaque niveau est composé de catégories dont la largeur figure les proportions respectives. Étant limité à deux niveaux apparents, le diagramme maintient une grande lisibilité tout en donnant accès à un contenu plus détaillé par la voie de l’interactivité (Bostock, 2018b). Cette visualisation des données de CONBAVIL fournit ainsi une représentation visuelle du *Thésaurus*, qui, jusqu’à présent, ne pouvait être parcouru qu’en suivant une structure hiérarchique d’hyperliens.

<iframe src="https://www.public.archi/atlas-numerique/viz/sunburst/index.html" title="Lena Krause, [*Répartition des projets Conbavil par type architectural*](https://www.public.archi/atlas-numerique/viz/sunburst/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal "</iframe>

Lena Krause, [*Répartition des projets CONBAVIL par type architectural*](http://atlas.lenamk.site/viz/sunburst/) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal 

Notre soleil interactif CONBAVIL présente donc le contenu de la base de données par type architectural. Le fait de cliquer sur une catégorie permet de faire apparaître le niveau de profondeur suivant et le retour en arrière s’effectue en cliquant au centre du graphique. En glissant le curseur sur une catégorie, on peut voir le nombre de délibérations qui y sont associées. Rapidement, on constate que plus de la moitié des délibérations sont contenues dans trois catégories principales : « urbanisme », « architecture religieuse » et « architecture judiciaire, pénitentiaire ou de police ». La section « urbanisme » contient toutes les délibérations liées aux plans d’alignement des villes, car le Conseil était également responsable de l’ouverture des rues pour l’assainissement et l’embellissement des espaces publics (Château-Dutier, 2016, T1: 151-179). La prépondérance de l’architecture religieuse s’explique quant à elle par le grand nombre de réaffectations de bâtiments nationaux en écoles, préfectures et tribunaux, notamment (Woolf, 1987: 30-31).

La carte comme le soleil sont des graphiques cumulatifs, ce qui signifie que certaines délibérations y figurent plusieurs fois si elles sont associées à plusieurs lieux ou types architecturaux. Cette décision provient, entre autres, d’une incertitude dans les données, qui ne signalent pas de hiérarchie en cas d’attribution multiple. Il faut également garder à l’esprit que la carte, par exemple, ne représente pas le phénomène bâtisseur, mais reflète plutôt les délibérations du Conseil. La taille des points dépend donc du nombre de mentions lors des séances et non de la quantité de chantiers ouverts. Les graphiques créés sont exploratoires, ils ont pour but de mener à la découverte du contenu des archives. C’est pourquoi il nous a semblé pertinent d’offrir le plus grand nombre de points d’entrée possibles dans les données.



#### statut des visualisation: 

ne sont jamais présentées comme des fins en soi ... mais plutôt comme une matière pour l'élaboration intellectuelle ̣- mouvante et incarnée dans divers modes d'inscription, mobilisant en même temps les nouveaux outils et des séquences de pratiques et des protocloes de travails existants. Les images produites ne sont ainsi pas uniquement conçues comme des outils d'interprétation, mais aussi de tri, de paramétrage, voire même d'enrichissement et de transformation des données (caviglia 2014)



## 3.3 Editorialisation & atlas



=/= mise en page mais mise en scène de l'information [drucker] ; 



table de travail ou table de montage [Didi-huberman] " introduit le multiple, le divers, l'hybridité de tout montage"



### 3.3.1 Interface - instrument de recherche

- Christian Jacob, *Lieux de savoir* 2013

Instrumentation de la recherche: défi : interaction en vue de développer "les environnements logiciels qui permettront d'entreprendre ce travail expérimental sur les données. Élaborer des outils spécifiques et pointus, répondant à des logiques intellectuelles particulières

- potentiel d'instruments de visualisation qui [...] permettraient de mettre à l'épreuve des hypothèses de travail en temps réel " ( Jacob 2013: cf lien ./1180) 
- besoin de faire varier la focale, de passer du local au global et inversement, mais aussi de passer d'une visualisation à l'autre "à mes yeux, l'environnement de recherche numérique idéal permettrait de passer d'une forme de visualisation à l'autre, d'un point de vue à l'autre. Il permettrait de mettre à l'épreuve en temps réel des hypothèses de travail, de procéder par des expérimentations successibes
- défi principal de l'instrumentation de la recherche aujourd'hui me semble être celui de la transitivité et de la fluidité
- réflexion critique sur les instrumentations de la recherche, sur les ergonoies des nouveaux outils, sur la manipulation et l'exploitation intellectuelle des documents qui s'accumulent chaque jour davantage sur nos disques durs

Outre exemples déjà donné: EAT ...



Il s’agit aussi d’essayer de présenter un modèle alternatif de production du savoir en histoire de l’art en usant du caractère visuel et spatial de la carte. L’utilisation de l’interactivité, dont il sera question dans la troisième partie de cet article, nous permet de contrer certains effets d’autorité causés par l’illusion d’une objectivité scientifique et cartographique (Harley, 1989b: 82). 

Il demeure toutefois essentiel, tout au long de ce processus, de tenir compte des formes de pouvoir impliquées par la création de l’interface et de situer le savoir ainsi produit.

Nous voulons faire des données de CONBAVIL des objets à manipuler pour les chercheur·se·s. ==> d3.js, visualisation interactive



#### Sinclair et al]: rich-prospect interfaces 

#### Exemple: Presner et al :temporal topographies

épaisseur des cartes --> 

- temporalité
- manipulation 
- multiplicité des perspectives

**Instrument de recherche heuristique**

Hypothèse : Visualisation et manipulation de données : nouvelles affordance pour la recherche  instrument heuristique ? 

Créer une interface dont les affordances qui nous mène pas où on avait prévu, où on savait qu’on pouvait aller, mais qui nous propose des nouvelles perspectives incongrues, qui oui parfois peuvent être vides de sens, mais peut-être parfois très pertinentes, sur l’objet qui nous intéresse. (exemple du défi 10 clics wikipédia)



### 3.3.2 Théories et pratiques de l'atlas

- jacob, besse, didi-huberman
- interactivité, manipulation

--

I wanted to go further by thinking about the visualizations together, by producing a space in which they can not only coexist but also be interlinked. 

My conception of an atlas was forged by various references: 

1. the classical atlas as an editorial space or, as Christian Jacob proposes "an apparatus that allows to reconcile the whole and the detail.. it is ruled by a cumulative and analytical reasonning, that guides from a global outlook to partial images... " [Jacob 1992:97] 

2. This mutliplicity of maps combined with images at large comes from a later form: the thematic atlas. Its content is visual and graphic, encompassing maps but also illustrations, timelines or any types of infographics, reproductions of artworks or cultural artifacts etc.

3. In art history, we study a very wide range of atlases produced by artists. Art historians such as Aby Warburg also created atlases. This phenomenon was studied by philosopher and art historian Georges Didi-Huberman. He offers multiple definitions of the atlas in this discipline, highlighting that it is a **visual form of knowledge powered by imagination** [Didi-Huberman 2011:13] that emerges from the reader's capacity to link various elements in order to pursue knowledge of a given field.

4. The characteristics of the atlas that I want to enhance in this digital form is the active role of the user, the ability to manipulate the objects and chose how to navigate the contents. I want to try and reproduce the serendipity of opening an atlas at a random page, letting the user make connections between "seemingly unrelated elements" while browsing through the atlas, their compliation potentially affording the production of knowledge.



Speaking of users, my primary target are researchers at large, as this database was produced for research, though it could be adapter or curated for a wider audience. 

I am currently working on interlinking the various visualisations I showed today. As they all represent the same dataset, each visualization becomes a potential filter, selecting a subset of the data. Here's an example ─ but this is a mockup, so please imagine this as interactive and responsive: select a location, the timeline will adjust to reflect the chronological information for said location, and same for the sunburst. Select a timeframe or a building type, all will shift and reflect the new selection. 

As the view on the data is constantly adjusted and adapted to the interests of the user, one can really explore the contents of the CONBAVIL database. This interactive dimension enables a wide diversity of approaches or ways into the data, creating a dynamic platform that aims to create knowledge through exploration, association of ideas, imagination, and manipulation.

Interactivity also breaks the sometimes tempting illusion that knowledge is set or that a visualization acts as proof. On the contrary, manipulating a map reveals its "constructedness" or its representational characteristic, which as such lacks "meaning" until its significance is argued by an author/user.

In summary, this research tool is an experiment for a visual, digital and spatial epistemology in art history. By combining the study of territory, knowledge, and power through a spatial and quantitative method, we can renew our understanding of public architecture and its politics, that are relevant to understand the XIXth century as well as our contemporary societies.

This is an experiment in progress. This presentation was to help you imagining my proposition for an atlas, but beyond CONBAVIL, I hope that ths experiment with data, mapping, visualization and knowledge production perhaps inspired some questions or approaches for your own research.



Pourquoi choisir la forme un atlas ? 

Premièrement, il s’agit bien d’essayer d’envisager le travail du Conseil des bâtiments civils tel qu’ils le concevaient eux-mêmes, une multiplicité de projets dans une logique d’ensemble, à l’échelle nationale. 

Je vous ai montré en début de conférence de nombreuses cartes pour illustrer mon propos. Après la Révolution, les cartes connaissent une popularité grandissante, dans le but d’instruire la population et « d’ouvrir les portes du savoir ». Elles sont également diffusées à un bien plus grande échelle grâce à la lithographie. 

Le développement de la cartographie est lié au contexte historique que je vous ai présenté. La volonté républicaine de démocratisation de la connaissance et la plus grande accessibilité de la cartographie donne lieu à son appropriation par des scientifiques et amateurs qui les utilisent tant pour mener des recherches, pour soutenir une argumentation ou pour l’enseignement et la pédagogie. La cartographie permet aussi de créer un imaginaire national, tout en rendant compte de la diversité régionale. Le développement de la cartographie thématique, et particulièrement l’exemple de cette (tout à fait géniale) *Carte gastronomique* de 1810 en est une excellente illustration.

A cette époque se développe ainsi une « pensée cartographique » peu mise de l’avant par les archives à notre disposition (Il reste toutefois que les projets soumis à l’examen du Conseil devaient être accompagnés d’un plan qui situe l’édifice dans la ville par exemple). Me concentrer sur cette dimension spatiale m’a semblé important. 

Deuxièmement, la création d’un atlas est une pratique éditoriale. Il s’agit de compiler un ensemble de documents, cartographiques ou non, sur un même sujet. Cette appellation convient donc à ma volonté de proposer une diversité de vues sur les données. Ces vues seront pour certaines cartographiques, d’autres seraient plus de l’ordre des diagrammes ou des statistiques. Il de faire des assemblages et des montages, en faisant appel à d’autres données, de géolocalisation par exemple. 

Et troisièmement, l’atlas se présente comme une forme visuelle du savoir. Un atlas est conçu comme un recueil d’images ou d’informations sur un sujet donné. Création de liens et associations entre les divers éléments par la lecture active/non linéaire. L’atlas est donc une forme visuelle du savoir qui contient un potentiel épistémologique.

**Un atlas numérique**

Nouvelle forme (potentielle) d’épistémologie visuelle dans le numérique.

Le passage d’une forme éditoriale au numérique permet de continuer à réfléchir à son fonctionnement et à son utilisation.Il faut prendre en compte les caractéristiques du numérique.

Deux caractéristiques importantes : 

- ​	Nouveaux moyens de visualisation de données (pas existants dans les études faites au préalable sur l’architecture publique). Faire des cartes, des diagrammes ne représente plus le même travail.
- ​	Interactivité sur le web



### 3.3.3 L’atlas numérique comme instrument de recherche

Les visualisations que nous présentons ici constituent une première étape dans notre processus de recherche. Telle une machine bâtisseuse, la politique d’équipement de la France est, à la période qui nous intéresse, un engrenage dont les besoins et les contraintes se reflètent dans sa chronologie, dans son organisation spatiale et dans ses choix d’infrastructure. Nous cherchons donc, afin d’étudier son fonctionnement, à concevoir un instrument de recherche à partir de nos visualisations.

Des liens entre les visualisations ont été tissés à deux niveaux. Tout d’abord, celles-ci sont regroupées dans un même espace éditorial qui reprend le modèle de l’atlas. Christian Jacob définit l’atlas géographique comme un « dispositif qui permet de concilier le tout et le détail. Il est régi par une logique cumulative et analytique, qui conduit de la vision globale aux images partielles » (1992: 97). La forme-atlas est transformée lors de sa reprise par des artistes ou par des historien·ne·s de l’art. Dans ce domaine, il peut devenir, selon Georges Didi-Huberman, une « forme visuelle du savoir » comportant « [un] paradigme *esthétique* de la forme visuelle, et [un] paradigme *épistémique* du savoir » (2011: 12). Sa réception est une activité non linéaire : on ne *lit* pas mais on *consulte* un atlas. Cette particularité autorise l’émergence d’une forme de « connaissance par l’imagination » grâce à « la puissance intrinsèque du *montage* qui consiste à découvrir […] des liens que l’observation directe est incapable de discerner » (13). En somme, regrouper les visualisations produites à partir des archives numérisées du Conseil des bâtiments civils dans un atlas numérique crée un espace propice à la réflexion et à la recherche.

<iframe src="https://www.public.archi/atlas-numerique/viz/carteAvis/index.html" title="Lena Krause, [*Exemple d’interactivité entre deux visualisations : carte et avis du Conseil*](https://www.public.archi/atlas-numerique/viz/carteAvis/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal "</iframe>



Des liens dynamiques intégrés dans le code permettent de relier entre elles les différentes composantes de l’atlas. Chaque graphique est créé à partir du même jeu de données. Nous avons donc pu mettre en place un système qui reproduit la sélection d’un sous-ensemble (d’un intervalle chronologique, d’un lieu ou d’une catégorie architecturale) dans les autres visualisations. Offrant d’abord un aperçu global, les visualisations se transforment ensuite au fur et à mesure du parcours interactif en des perspectives de plus en plus détaillées, qui descendent en profondeur jusqu’à la consultation d’une seule affaire. Chaque action de l’utilisateur, guidée par ses hypothèses et par ses réflexions, façonne donc la constellation que forment les données dans l’atlas. La manipulation aide la chercheuse ou le chercheur à analyser le contenu de CONBAVIL et l’invite à émettre des hypothèses sur sa signification. Pour le moment, ces liens dynamiques sont implémentés entre la carte et un graphique des avis du Conseil. Initialement, tous les lieux sont sélectionnés et le graphique figure l’ensemble des affaires. On peut ensuite modifier la sélection de lieux, ce qui entraîne un ajustement du graphique des avis. Et, inversement, la sélection d’un avis se reflète automatiquement sur la carte[12](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote12_ajhxl80). On peut ainsi observer de façon spatiale, grâce à ces liens, les dispositions du Conseil face aux projets soumis. Aussi, la dynamique entre les visualisations permet l’étude de phénomènes par la recherche des corrélations : par exemple, les membres du Conseil étaient réputés intransigeants avec les architectes de province jugés « peu capables » (Château-Dutier, 2016, T2: 591), allant jusqu’à corriger leurs projets à grands coups de crayon sur les plans fournis. Nous pouvons rechercher ce phénomène dans l’atlas, en modifiant la sélection des avis et des lieux, afin d’identifier d’éventuelles régions où le taux de refus ou de modification serait plus élevé.

Notre atlas est encore à un stade embryonnaire et il ne présente pour le moment que quelques liens actifs entre deux visualisations. Cependant, la poursuite de ce travail à l’échelle de toutes les visualisations, permet d’augmenter de façon exponentielle le nombre de constellations de données que l’utilisateur peut découvrir. De l’association entre ces innombrables possibilités et l’imagination de l’utilisateur émerge un dispositif qui active « la puissance intrinsèque du *montage* » évoquée précédemment (Didi-Hubermann, 2011: 13). L’espace de l’atlas s’organise autour d’une structure éditoriale déterminée par son autrice, tout en se transformant en fonction de l’action de son utilisateur. Si la consultation d’un atlas papier est contrainte par les éléments structurels et les repères de l’ouvrage imprimé, les lecteur·rice·s sont libres de naviguer au sein de son contenu, de suivre la proposition des éditeur·rice·s ou de se laisser porter par la sérendipité de consulter l’atlas au hasard des pages. Et ces mêmes possibilités se présentent dans notre proposition d’atlas numérique : l’utilisateur est libre d’explorer le contenu à sa guise, malgré un cadre défini d’actions possibles dans l’interface. La sérendipité, quant à elle, est permise lors des déambulations du curseur dans l’interface, lors de la sélection aléatoire d’un sous-ensemble de données, ou encore lors de l’affichage à l’écran d’une constellation de données produite au hasard[13](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote13_n6q5i5d).

[![img](http://revuecaptures.org/sites/default/files/styles/demi_largeur/public/Krause_figure_10.png?itok=LCoY6crr)](http://revuecaptures.org/sites/default/files/Krause_figure_10.png)

Lena Krause, *Modélisation de l’atlas* (2019) , Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal 

La création d’une nouvelle interface pour la base de données CONBAVIL sous la forme d’un atlas peut être comprise comme un acte d’éditorialisation[14](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote14_psr6wnd). Il s’agit d’une démarche processuelle, expérimentale et surtout multiple (Vitali-Rosati, 2016: 68). La visualisation et la cartographie ont considérablement évolué avec l’apparition des logiciels et outils informatiques. D’après les historiennes Claire Lemercier et Claire Zalc, « il n’est plus question de publier chaque tableau ou graphique péniblement obtenu, mais plutôt de les utiliser pour avancer dans une recherche, quitte à n’en montrer au lecteur final que quelques-uns » (2008: n.p.). Comparativement aux grandes équipes de chercheur·se·s, ingénieur·e·s, informaticien·ne·s, cartographes et perforateur·rice·s de cartes, indispensables aux grandes enquêtes collectives menées dans les années 70, il est de nos jours possible de réduire le personnel, le temps, les connaissances et les coûts nécessaires à la création de cartes (Lemercier, 2008)[15](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote15_7tulxje). Cela favorise particulièrement l’expérimentation, tant avec les formes et les variables graphiques qu’avec les calculs et les statistiques privilégiés pour la cartographie thématique. Aussi, les nombreuses itérations possibles au cours du processus de production nous invitent à repenser chaque élément jusqu’à ce qu’il convienne aux besoins du projet.

### 3.3.4 Editorialisation 





Le point de départ de ma réflexion, issu des conversations avec mon directeur de recherche, Emmanuel Château-Dutier, est ancré dans le concept d’éditorialisation. En effet, le travail envisagé est un **acte éditorial**, il s’agit de donner une forme à l’objet en question : la base de données CONBAVIL. 

Si l’éditorialisation a été définie de multiples fois et pour des contextes variés, je me suis particulièrement intéressée à la définition qu’en fait Marcello Vitali-Rosati et qui évolue entres autres au cours du séminaire « écritures numérique et éditorialisation ».

Un aspect de l’éditorialisation sur lequel j’aimerais insister aujourd’hui est la nature processuelle de l’éditorialisation. La création de cet atlas est un **processus ouvert**, qui n’est pas construit en vue d’une finalité prédéfinie. 

En fait, le processus fait penser à la recherche-création par exemple, avec une approche centrée sur l’expérimentation et le « faire ». 

Le « faire », justement, nous amène également au sein de la nature performative de l’éditorialisation. La forme de l’atlas n’est pas vraiment prévisible, elle est modelée au fur et à mesure par les activités entreprises. Je reviendrai sur cet aspect à la fin de ma présentation.

A quoi ressemblera alors cet atlas ? Quelle forme prendra-t-il ?


 

- Editorialisation et enjeux
- Instrument de recherche 

Il serait tentant de penser que l’interactivité de l’atlas déconstruit des enjeux de pouvoir dans le champ du savoir. Il ne faut toutefois pas oublier les choix effectués lors de sa production. Du point de vue du contenu, les archives sont produites par des instances dans un contexte historique déterminé, à savoir une administration française issue de la première moitié du XIXe siècle pour le Conseil des bâtiments civils. La base de données, pour sa part, est issue du travail de chercheur·se·s au tournant du XXIe siècle. Les connaissances obtenues à partir de ces données ne représentent donc pas une vérité, mais plutôt un point de vue[16](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote16_5pi61ps). En ce qui concerne l’interface de l’atlas, son élaboration se base sur diverses institutions, telles que Open Street Map pour le géoréférencement ou le thésaurus architectural de l’Inventaire général du patrimoine culturel. Ces références formatent le contenu selon des ontologies du savoir précises, des perspectives dont il n’est pas impossible de remettre la pertinence en cause. Par exemple, la toponymie contemporaine peut s’avérer problématique dans le cadre d’études historiques. Il faut donc garder à l’esprit les formes de pouvoir et d’autorité qui subsistent dans la production du savoir de notre atlas. C’est la raison pour laquelle nous souhaitons encourager la réutilisation et l’appropriation de son code en le publiant sous une licence libre[17](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote17_bnrpj0k). L’objectif est de faciliter les ajouts, les modifications et les contre-propositions, ainsi que la réutilisation du code pour d’autres projets. Nous savons que cela nécessite un niveau de littératie numérique encore peu répandu parmi les chercheur·se·s en histoire de l’art. Cependant, grâce à l’accessibilité et à la transparence de notre dispositif, nous invitons celles et ceux qui seraient intéressé·e·s à se former par la pratique, ou du moins à développer une compréhension plus fine du code afin de pouvoir, éventuellement, y apposer un regard critique.

Si la construction de notre atlas est un processus en constante évolution, nous pensons avoir démontré le potentiel de la cartographie et de la visualisation pour transformer l’étude d’une base de données. L’interface visuelle et interactive de l’atlas numérique offre une approche inédite du contenu des archives du Conseil des bâtiments civil et permet de renouveler la recherche en faisant usage des méthodes numériques disponibles aujourd’hui. À la manière du millefeuille topographique imaginé par Dario Gamboni, l’atlas plonge l’utilisateur dans « [des] profondeur[s] qui invite[nt] à l’excavation » (2008: 6). Il reste cependant ancré dans des préoccupations contemporaines à ses sources, afin de se distancier d’éventuels anachronismes que l’écart entre les archives du XIXe siècle et les nouvelles technologies du web appliquées à une base de données pourraient générer. S’il n’est pas toujours évident de savoir comment se servir des données dans la recherche en histoire de l’art, la cartographie et la visualisation se révèlent être des instruments précieux dans le contexte numérique.

