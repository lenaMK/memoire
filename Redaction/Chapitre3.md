[TOC]

# Chapitre 3

Nous voulons désormais créer un espace de travail pour l'interprétation et l'expérimentation avec les données de CONBAVIL. Il s'agit de concevoir un dispositif exploratoire qui a pour source d'inspiration les questions de recherche évoquées par les chercheur·se·s impliqué·e·s dans la création de la base, l'historiographie des recherches sur le sujet et le contexte historique, c'est-à-dire la statistique, la cartographie thématique et la rationalisation administrative. Nous cherchons, dans un premier temps, des concordances entre ces questions et les moyens méthodologiques et technologiques à notre disposition. Nous expérimentons ensuite avec leur mise en pratique de façon isolée, avant de les rassembler dans un espace éditorial commun: l'atlas numérique de l'architecture publique en France (1795 - 1840). Cet atlas est à la fois un outil de réflexion théorique autour des enjeux d'éditorialisation et de conception d'interfaces de recherche, et un micro-prototype issu de l'application pratique de ces opérateurs théoriques. 

## 3.1 Espaces et interprétation des données 

Une interface donne forme aux données, elle dicte donc notre façon d'y réfléchir et les questions qu'on voudrait y poser. Les interfaces produisent des affordances épistémologiques parce qu'elles sont le cadre au sein duquel nous posons nos questions, nos observations, nos hypothèses et nos déductions à propos de la base de données.

Puisqu'il existe déjà un outil d'interrogation de la base de données CONBAVIL, nous voulons créer, comme complément, un instrument de recherche. Si le premier permet de chercher un contenu spécifique via des requêtes SQL ou l'outil d'interrogation, le second est pensé comme instrument de recherche et dispositif critique qui serait à l'origine de questionnements et d'une herméneutique des données.

### 3.1.1 Quantitatif, statistique et cartographique

#### Approches quantitatives et statistiques

Notre première piste pour la création de notre instrument de recherche est issue de l'historiographie de la base de données et des archives du Conseil des bâtiments civils. Nous souhaitons poursuivre et étendre les recherches quantitatives ou statistique, ainsi que la dimension spatialisée des travaux de Georges Teyssot et Bernard Lepetit (ch1.3.3), ce qui est désormais non seulement rendu possible mais aussi facilité par CONBAVIL. Les données sont géolocalisées et d'indexées en catégories et sous-catégories architecturales, il reste à préciser la méthode à employer. 

Nous puisons également dans le contexte de création de la base de données pour les méthodes de recherches encore inexploitées. Quand il introduit CONBAVIL à l'occasion de sa mise en ligne en 2009, l'historien de l'architecture Jean-Phlippe Garric détaille l'énorme potentiel de cette base de données pour la recherche. 

> Cette base de données [...] nous conduit à imaginer des enquêtes et des travaux jadis presque impossibles, ouvrant des perspectives inédites sur des analyses quantitatives, économiques ou typologiques, sur des comparaisons entre régions ou sur les rapports Paris-Province, sur le mouvement de codification des règlements et des marchés de travaux, sur les combats de l’art et de la nécessité, du local et du national. (Jean-Philippe Garric dans Boudon 2009: 5)

Nous voulons donc pousser une réflexion quantitative, également inspirée par le contexte de production des archives. Comme nous l'avons vu au premier chapitre, une véritable volonté de créer et d'utiliser des données émerge à l'époque. Si les moyens n'étaient pas encore disponibles, ni en statistique, ni en cartographie, nous pouvons aujourd'hui en faire l'exercice. Nous envisageons donc la production de cartes thématiques ou d'autres façons pertinentes de visualiser nos données pour en révéler le raisonnement sous-jacent: des dynamiques bâtisseuses, des priorités régionales ou des tendances en matière d'équipement.

Pour ce faire, il faut trouver un moyen d'articuler les propriétés contenues dans les données. Les mentions de personnes et les informations financières n'étant pas suffisamment structurées, nous avons choisi de nous concentrer sur les propriétés spatiales, chronologiques et typologiques. Nous employons également des outils statistiques pour comptabiliser les actions du Conseil des bâtiment civil, à commencer par le simple acte d'addition selon un critère, puis une distribution en pourcentages.  Bien d'autres méthodes quantitatives et statistiques sont disponibles pour l'historien·ne (Lemercier et Zalc 2008). Nous avons toutefois choisi, dans le cadre de ce mémoire, de nous arrêter à ces méthodes de base car elles sont plus proche du mode de pensée à l'époque et nous procurent déjà une mine de nouvelles informations sur le sujet. 

#### Formes de pensée cartographique 

Les approches quantitatives se combinent aisément à une approche géographique inspirée par la géographie de l'art (Kaufmann 2004). 

> En 1987, Dario Gamboni regrettait, dans sa Géographie artistique de la Suisse, le caractère exceptionnel de l’usage de la carte en histoire de l’art, d’une part faute de « données systématiques et quantifiables comme celles que travaillent à recueillir ethnologues, dialectologues, économistes ou sociologues » (Gamboni, 1987, p. 2), et d’autre part en raison d’une conception de la culture « qui voit dans l’œuvre d’art le produit d’une activité échappant par essence aux déterminations  historiques, telles qu’elles se matérialisent notamment dans l’espace » (id.) (Besse 2010: 214)

CONBAVIL nous fournit ce type de "données systématiques et quantifiables". Nous pouvons donc envisager de contribuer à une géographie artistique afin d'ouvrir "de nouveaux programmes de recherche propres à l'histoire de l'art, apparus dans le prolongement de cet intérêt pour les problématiques spatiales" (Besse 2010: 215). 

Nous avons donc entrepris les recherches théoriques et pratiques nécessaires pour cartographier les données de CONBAVIL. Nous avons appui sur les réflexions du philosophe et historien Jean-Marc Besse, qui propose une conception pragmatique de la carte et, par extension, de l’acte cartographique :

> 1. Toute carte est en même temps une interprétation et un projet vis-à-vis du territoire auquel elle réfère, autrement dit toute carte se présente comme une version possible du territoire. 
> 2. Toute carte est la traduction et la condition d’un pouvoir qui cherche à s’exercer socialement et culturellement, et qui s’appuie sur la carte pour s’assurer une forme d’autorité. 
> 3. Toute carte développe sa stratégie par l’intermédiaire de la mise en œuvre d’un univers graphique au sein duquel elle construit son discours, un espace graphique qui n’est rien d’autre que la mise en forme d’un territoire de référence au sujet duquel le discours est construit. (Besse, 2006: 8)

Notre relevons ici l'importance de rendre visibles les dimensions interprétatives et graphiques de la carte, précepte qui ressort également dans les principes de la cartographie critique (Harley 1989). Dans son article "*Deconstructing the Map*" (1989), Harley met tout d’abord le système de la cartographie en relation avec celui du discours selon Foucault, c’est-à-dire un système de possibilités qui produit de la connaissance. L'auteur identifie deux ensembles de règles qui sous-tendent et dominent l’histoire de la cartographie occidentale depuis le XVIIème siècle. La première concerne la production technique des cartes et les règles scientifiques de la production de connaissances. La seconde contextualise la production cartographique dans sa dimension culturelle, les cartes respectant les codes de la société qu’elles représentent tout en les renforçant. Sous le masque de la neutralité scientifique se révèle une image construite non seulement à partir de mesures d’un monde phénoménologique mais également à partir de l’ordre social qui régit ce monde (Harley 1989: 3-7).

Dans la deuxième partie de l'article, l'auteur emploie la déconstruction selon Derrida pour analyser en détail le texte cartographique. Dans les marges et les écarts du modèle normatif, Harley identifie la dimension symbolique du fait cartographique. La cartographie est par nature un art de la communication persuasive. Le texte cartographique est donc un texte rhétorique qui utilise les codes à disposition afin communiquer au mieux le mythe qu’il cherche à propager. La rhétorique et la science ne sont pas opposées mais considérées comme deux éléments constitutifs et révélateurs lors de l’analyse de l’objet cartographié.(Harley 1989:  7-11). Harley poursuit avec les dimensions sociales et politiques de la cartographie. De retour en territoire Foucaldien, la carte est comprise comme une forme de savoir-pouvoir dans la société. Le pouvoir de la carte peut être externe, lié au pouvoir politique, ou interne, en relation avec l’impact politique de la pratique du cartographe. Ce dernier n’exerce pas son pouvoir directement sur les individus, mais sur le savoir à leur disposition. Il faut alors envisager l’impact de ces images dont la neutralité n’est plus concevable. (Harley 1989: 11-14). 

Le changement épistémologique proposé dans cet article rapproche selon nous la discipline de Harley de la nôtre. En effet, l’historien de la cartographie comme l’historien de l’art ne produit pas les objets de sa discipline. Cette distance critique avec l’objet étudié permet de révéler puis analyser le contexte culturel et les règles de production de ces objets. <!-- Denis Wood, the power of Maps 1992--> Le mouvement de cartographie critique a ensuite permis l'émergence, au cours des années 2000, d'une nouvelle pratique: la contre-cartographie. La carte, dispositif politique et instrument de savoir et de pouvoir, est employée pour ébranler le pouvoir et défier les normes. En reversant les postures (qui crée la carte et l'emploie, à qui elle est destinée), on peut permettre une "*political practice of mapping back*" (Halder, Michel dans Kollektiv Orangotango+ 2018: 13). La proposition est d'utiliser les instruments du pouvoir contre lui, pour révéler son fonctionnement et ses biais, ainsi que pour inverser les rapports de pouvoir.

La création d’un atlas numérique peut présenter diverses modalités de production de savoir en histoire de l’art. Dans le cas de l’*Atlasmuseum *(Pringuet 2017)*,* l’outil développé ne sert, du moins pas encore, pas tant à l’analyse qu’au recensement des œuvres d’art public en France, par le moyen d’une plateforme numérique participative. La diversité des modèles et usages des projets mêlant données géolocalisées et histoire de l’art[3](#sdfootnote3sym) suggère, d’une part, l’émergence d’une pratique dont les traits sont encore en train d’être définis. D’autre part, la pluralité des formes permises par le numérique offre l’opportunité de définir un modèle spécifique à chaque cadre de recherche. Ainsi, l’enjeu n’est pas de reproduire des modèles mais d’adapter sa méthode aux caractéristiques du projet de recherche[4](#sdfootnote4sym).



### 3.1.2 De la cartographie à la visualisation de données

CONBAVIL forme un espace cartographique composé de multiples épaisseurs. D’une part, il est constitué d’un territoire de référence physique, la France de la première moitié du XIXe siècle, sur lequel s’applique une politique architecturale. D’autre part, les archives administratives font partie intégrante du territoire et participent elles aussi à le construire. La cartographie fournit ainsi « une méthode pour unir dans une image le concept d’un territoire et une multitude d’informations dites empiriques livrées par la fréquentation du terrain » (Besse, 2006: 15). Aux informations « empiriques », nous substituons des données issues de sources archivistiques, lesquelles se trouvent enrichies par la géolocalisation que nous leur adjoignons. 

Notre processus cartographique vient ainsi réinscrire l’action du Conseil des bâtiments civils sur le territoire français et révéler son empreinte sur le pays. Au-delà de l’impact du patrimoine bâti sur le territoire, nous prenons aussi en compte les projets refusés ou inaboutis. Leur cartographie nous invite « à voir et à penser ce que l’on ne voit pas et ne pense pas quand on regarde l’espace réel » (Jacob, 1992: 50). L’imaginaire bâtisseur de l’époque se matérialise par ses archives et nous offre une autre facette de l’histoire de ce territoire. Nous cherchons ainsi à mettre en pratique la pensée de l’historien de l’art Dario Gamboni, selon qui,

> [p]our comprendre l’histoire d’un lieu, il importe de connaître non seulement ce qu’il a été possible d’y réaliser, mais encore ce qu’il était impossible d’y faire pour des raisons esthétiques et culturelles, techniques, sociales ou encore politiques. (2008: 9) 

L’historien Christian Jacob théorise la relation entre archives et cartographie dans son ouvrage majeur, *L’Empire des cartes* (1992). Il y présente un projet de recherche sur les prénoms mené par la *Rencontre des historiens du Limousin*[6](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote6_3hkkf7g). Dans le contexte d’un dépouillement massif d’archives, ces chercheur·se·s soulignent le potentiel épistémologique de l’usage de la cartographie pour « le quantitatif et l’étude de l’organisation spatiale des phénomènes » (Pérouas, 1984: 3). Dans le cadre d’un tel projet, la carte devient un instrument d’enquête pour l’historien·ne : elle « ne renvoie pas à une réalité visible sur le terrain — en revanche, elle permet de visualiser différemment des centaines d’archives dépouillées par les historiens » (Jacob, 1992: 32). Dans le cas du Conseil des bâtiments civils, plus de 26 000 affaires situées dans 4 200 lieux sont organisées selon une logique encore enfouie dans les sources. La cartographie de ces éléments nous permet de discerner leur organisation spatiale et de renouveler ainsi la compréhension de l’administration de l’architecture publique française au lendemain de la Révolution.

Nous préférons employer le terme « figuration » à celui de « représentation » pour parler de l’image produite par la cartographie car « la figuration est le dessin d’un objet qui ne préexiste pas à son image, alors que l’usage courant du mot représentation fait de celle-ci la reproduction d’une réalité préexistante. » (Besse, 2006: 12). De plus, nous élargissons notre approche cartographique pour y inclure des formes visuelles qui ne sont pas spécifiquement topographiques, notamment des diagrammes chronologiques ou typologiques. Rappelant l’étymologie du mot « diagramme », Jean-Marc Besse définit la carte comme « une *eikôn* d’un genre particulier » qui « nous renvoie d’une part à un acte d’écriture (*gramma*, relation avec *graphein*) et d’autre part [à] un acte d’articulation logique (*dia*-, à la fois distinguer et relier, enchaîner ce qui est distingué) » (2006: 15). L’assemblage de ces actes de figuration, d’écriture et d’articulation logique nous permet de définir la visualisation de données comme une forme de pensée visuelle qui figure un imaginaire raisonné et construit.

L’acte cartographique ajoute également une dimension spatiale au savoir. Non-linéaire, la carte ne dicte pas nécessairement un point de vue unique. Lorsqu’elle est conçue comme un objet de recherche, elle peut démultiplier les perspectives et les échelles tout en accumulant, tel un millefeuille[^1], les multiples couches temporelles qui composent l’histoire d’un lieu. Avec le développement d’outils informatiques pour la production de cartes numériques puis leur accessibilité au travers des applications web de cartographie comme Google Earth et OpenStreetMap, l’acte cartographique est transformé (Presner, Shepard, et Kawano 2014: 16) . 

On peut désormais envisager un acte de cartographie « épaisse », *thick mapping* (Presner, Shepard, et Kawano 2014: 15-19) . Dans l'ouvrage *Hypercities* (Presner, Shepard, et Kawano 2014: 2014), les chercheur·se·s allient l’approche géographique, les plateformes de cartographies numériques et les pratiques interprétatives de l’histoire pour mettre en place une forme de recherche sur l’espace qui se veut riche, nuancée et pluridimensionnelle. Cette épaisseur cartographique cristallise des opportunités nouvelles « de navigation empirique, d’épistémologie de la représentation et de rhétorique de la visualisation » (Burdick 2012: 46) . Ce tournant spatial promeut une variété d’approches pour analyser et cartographier les fortes imbrications qui existent entre les notions de culture, de pouvoir et d’espace (Presner, Shepard, et Kawano 2014: 53). 

La richesse et la complexité des cartes que nous souhaitons produire nécessitent aussi l’utilisation d’un langage graphique expressif. L’utilisation des variables visuelles identifiées par Jacques Bertin sera donc d’une grande utilité (Bertin 2013). L’analyse d’exemples et d’antécédents, couplée au processus d’éditorialisation, servira également à déterminer la forme graphique et numérique la plus appropriée pour notre atlas numérique de l’architecture publique.

### 3.1.3 Les outils de visualisation et de cartographie numérique

Il existe une gamme d'outil variée pour la visualisation de données et la cartographie numérique. Pour les présenter, nous les divisons en trois grandes catégories.

#### Les logiciels

La première concerne les logiciels pour la visualisation de données. Une recension récente des outils et logiciels est disponible dans l'ouvrage *Hands-On Data-visualization* publié en 2021 par Jack Dougherty et Ilya Ilyankou (2021: chap 6 - 8) Palladio, développé par le *Research Lab* à Standford, en est un excellent exemple dans le domaine des humanités numériques (Palladio). En chargeant les données dans le logiciel, on peut accéder à différentes vues sur les données - carte, graphe, liste et galerie - qui peuvent être filtrées selon certains critères ou à l'aide de la chronologie générée par les données (Braude 2014, fig. 1). Ce type de logiciel est fait pour être simple d'utilisation et ne requiert pas de connaissances particulières en informatique.Il faut toutefois, au minimum, avoir des données et savoir les structurer pour leur utilisation dans le logiciel.

Nous notons deux inconvénients quant à notre projet d'instrument de recherche. D'une part, le logiciel prédéfinit les vues possibles sur les données. On ne peut pas les adapter ni en ajouter, contraignant ainsi le choix de visualisations à celles mises à disposition. D'autre part, il s'agit d'une utilisation individuelle. On peut enregistrer le projet pour le partager avec d'autres, mais l'accès et la diffusion restent internes au logiciel <!-- on pourrait imaginer faire un iframe vu que c'est web, mais pas sûr qu'on puisse envoyer le package de données ou comment le publier...? -->. 

<img src="https://hestia.open.ac.uk/hestia-data/uploads/2014/10/HestiaPalladioTimeLineTimeSpan1-1024x551.png" alt="Interface Palladio" style="zoom:90%;" />

fig. 1 *Interface de Palladio* capture d'écran [ajouter source ou faire la mienne avec les données de CONBAVIL <!-- if i have time, enter CONBAVIL data into palladio -->]

#### Les SIG

La seconde catégorie est propre à la cartographie numérique, il s'agit des systèmes d'information géographique (SIG). Ces logiciels complexes et puissants, tel que [QGIS](qgis.org) et [ArcGIS](https://www.arcgis.com/index.html), doivent être installés sur l'ordinateur des chercheur·se·s. Ils requièrent un apprentissage spécialisé en cartographie numérique mais présentent un vaste attirail d'outil pour spécifier chaque aspect technique et visuel de la carte<!-- dont j'ai bénéficié à l'école d'été du GRSH-UAM en carto numérique-->. Remontant aux années 1960, les SIG d'abord été crées pour une utilisation interne au logiciel qui permet des exports de cartes statiques (png ou pdf). Il existe désormais des extensions qui permettent certaines formes de publication interactive sur le web. Excepté pour QGIS, qui est un logiciel libre, il faut également prendre en compte le coût très élevé pour l'emploi de ces logiciels. 

<img src="./img/QGIS_pop1831.png" alt="qgis_pop_1831" style="zoom: 75%;" />

Fig. 2 *Carte figurant la densité par commune de la population française en 1831*, Lena Krause (2019), avec les données de Thomas Thevenin

Nous avons ici employé QGIS pour visualiser les données du recensement des communes françaises de 1831 qui nous ont été transmises par Thomas Thevenin (fig. 2). 

#### Les librairies de code

La dernière catégorie d'outil sont les librairies de code, telles que Leaflet.js et D3.js. Leur emploi requiert des connaissances en programmation. Une librairie de code est un ensemble d'outils de programmation auxquels on peut faire appel pour coder un projet. Leaflet.js, par exemple, est conçue pour la création de cartes interactives. Nous en avons testé la fonctionnalité qui permet de créer une *heat map* (fig. 3), nous y reviendrons dans la sous-partie sur la cartographie 3.2.1.

<img src="./img/Leaflet_heatMap.png" alt="Environnement Leaflet - CONBAVIL" style="zoom:55%;" />

fig.3 *Carte des projets CONBAVIL*

La librairie D3.js se spécialise quant à elle en *data-driven visualizations* (Bostock, 2019a). Les données sont converties en graphiques directement dans le navigateur. Ces graphiques, dont nous présentons des excemples ci-dessous (fig.4) s'animent sous l'action de l'utilisateur·rice·s, qui peut ainsi sélectionner les données à afficher ou régler le niveau de détail lors de la consultation.

<div>
    <iframe width="100%" height="500" frameborder="0" src="https://observablehq.com/embed/@d3/gallery?cell=*">&nbsp;</iframe>
</div>

​    Fig. 4, Galerie d'exemples de visualisations avec D3.js (2020) Mike Bostock, <a href="https://observablehq.com/@d3/gallery" target="_blank" class="return">ObservableHQ</a>
​    

Nous avons établis plusieurs critères pour sélectionner un outil de visualisation et de cartographie pour CONBAVIL. Nous souhaitions, dès le départ, explorer une pluralité de formes visuelles, de la cartographie aux différentes formes de graphiques et de diagrammes. L'accès web et interactif à ces visualisations est également important dans la conception d'un instrument de recherche. Dans l'ensemble, nous voulions privilégier un outil qui permette la création d'un espace de recherche pour les données de CONBAVIL et disposer d'un maximum de possibilités d'expérimentation visuelle. C'est pourquoi nous avons choisi de travailler avec la librairie d3.js, conçue pour le web et qui offre la plus grande flexibilité et variété dans les formes de visualisation de données ainsi que dans les interactions possibles.

## 3.2 Pratiques de visualisation et de cartographie

Dès les premières recherches de ce mémoire, il semblait essentiel de cartographier CONBAVIL à partir informations spatiales renseignées dans CONBAVIL. Nous avons beaucoup expérimenté avant d'arriver à notre carte, c'est pourquoi nous commençons par décrire notre processus <!-- intérêt valeur académique des erreurs-->, avant de présenter nos prototypes d’exploration visuelle des données de CONBAVIL. Ceux-ci prennent diverses formes diagrammatiques et chaque une proposition présente une vue sur les données. La perspective change selon la caractéristique mise de l’avant par le graphique : la géolocalisation pour la carte, la date de discussion de l’affaire pour la chronologie et le type architectural pour la classification hiérarchique rayonnante. Nous effectuons ensuite un retour critique sur ces visualisations, une étape importante avant d'en arriver la forme-atlas.

### 3.2.1 Premières expérimentations et questions d'échelle

Chaque délibération, c’est-à-dire chaque projet architectural évalué par le Conseil des bâtiments civils lors d'une de ses séances, continent dans sa description les noms de commune, de département et de région, ainsi que le numéro de département. Notre premier essai cartographique est inspiré des travaux de Teyssot et Lepetit, dont leur emploi de l'échelle du département. Cela semblait évident pour procéder à une comparaison entre leur travail et les nouvelles données dont nous disposons avec CONBAVIL. 

Le fond de carte sélectionné est un découpage de la France en départements datant de 1831[^3]. Nous l'avons ensuite complétée de façon colorimétrique, exactement comme les autres cartes thématiques que nous avons vues, en indiquant la densité des projets. Notre carte se distingue par son interactivité. On peut passer sa souris par dessus chaque département pour voir le nombre exact de délibérations concernées. Cliquer n'affiche, pour le moment, que le nom du département et le ce chiffre associé dans la console du navigateur. Toutefois, puisque la carte est réalisée à partir des données de CONBAVIL, il serait aisé d'afficher les délibérations concernées lors de la sélection d'un département. 

<div>
    <iframe width="100%" height="129" frameborder="0"   src="https://observablehq.com/embed/47e03b0eadfc73b3?cells=viewof+gradientLegend"></iframe>
</div>

<img src="./img/CONBAVIL_carte_departements.PNG" style="zoom: 50%;" />

fig. 5 *Carte des départements français et densité des projets CONBAVIL* (2018), Lena Krause, carte réalisée sur ObservableHQ pendant le cours LLCU-498&698 "Digital Humanities Project" donné par Prof. Stéfan Sinclair.

<!--<div><iframe src="" title="Lena Krause, *[Carte des départements français et densité des projets Conbavil](https://www.public.archi/atlas-numerique/viz/carteCommunes/index.html)* (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal " width="640" height="480" style="display:block; margin: 0 auto;">&nbsp;</iframe></div>-->

Malgré le succès de cette première entreprise de cartographie numérique, nous trouvons que cette carte un peu décevante du point de vue herméneutique. À cette échelle, la cartographie des données présente un intérêt relatif. La densité de délibérations dans le département du Nord pose quelques questions, toutefois, on ne peut pas vraiment observer de tendance grâce à la spatialisation produite ici. Un·e chercheur·se qui travaillerait sur un département français pourrait immédiatement consulter les délibérations qui y sont associées. Outre la dimension visuelle de la requête, le résultat demeurerait cependant équivalent à une recherche par département effectuée dans l'interface de l'INHA. 

Nous avons donc choisi de poursuivre nos expérimentations à une plus petite échelle: les communes. Avec plus de 30'000 communes françaises, il est presque impensable d'envisager un projet de cartographie thématique à cette échelle sans l'assistance d'un outil informatique. Nous avons d'ailleurs fait l'erreur un peu naîve d'employer le même code pour cartographier les communes que celui pour les département. Ce code dessine le contour de chaque élément puis inscrit son nom en son centre. Comme fond de carte, nous avons employé des données sur les divisions administratives françaises disponibles en ligne[^2].Le résultat (fig. 6) produit un dense nuage de noms qui recouvrent le territoire et dont on entrevoit des extraits en zone liminaire. Pour visualiser le maillage des communes, nous l'avons ouvert avec QGIS (fig. 7).

<img src="./img/mapOfCommunes.png" alt="mapOfCommunes" style="zoom: 67%;" />

fig. 6 *Carte des communes françaises*, Lena Krause (2018), capture d'écran de la visualisation réalisée sur [ObservableHQ](https://observablehq.com/d/05c73472e7a61b64)

<img src="./img/communesF.PNG" alt="communesF" style="zoom: 67%;" />

fig. 7 *Carte des communes françaises*, Lena Krause (2019), capture d'écran des données visualisées sur QGIS 

Ce ne sont toutefois pas les 30'000 apparaissent dans CONBAVIL. Comme nous l'avons détaillé dans le chapitre précédent (2.3.2), nous avons établi la liste des communes dans CONBAVIL, auxquelles nous avons ensuite associé une géolocalisation. Nous avons également décidé qu'en considérant les communes à l'échelle de la France, le centroid serait une indication plus simple à gérer que la représentation de chaque aire[^7]. Sur la suggestion de Prof. Stéfan Sinclair, nous avons réalisé, avec son aide précieuse, notre première carte (fig. 5) dans l'environnement de code en ligne [*ObservableHQ*](https://observablehq.com/about) . Ces "cahiers numériques" ou *notebooks* sont conçus pour faciliter l'apprentissage et l'emploi de la librairie D3.js. Nous avons cependant dû quitter cet environnement car les données de CONBAVIL sont très lourdes à charger. De plus, nous n'avons pas le droit de les rendre accessibles publiquement en ligne, ce qui compliquait la tâche pour les employer dans Observable. 

Nous avons donc commencé à coder nos visualisation nativement, en créant une page web classique composée de fichiers HTML, CSS et Javascript. Nous avons longuement réfléchi à la possibilité d'employer, en plus de d3.js pour la visualisation de données, une librairie de code comme React.js pour bâtir notre interface. Toutefois, le temps d'apprentissage nécessaire ainsi que l'ampleur du travail requis pour coder chaque visualisation nous ont dissuadé de le faire dans le cadre de ce mémoire. Nous avons déjà eu bien des complications, à commencer par un grand nombres de problèmes dans nos tentatives de cartographie numérique. 

En effet, nous avons commencé à coder nos visualisations lors d'un séjour de recherche au MédiaLab à SciencesPo Paris. Malgré l'immense aide de Paul Girard, Arnaud Pichon et l'ensemble de l'équipe tech, nous avons eu de nombreuses difficultés en cartographie numérique, comme le montrent ces quelques exemples que nous avons documentés (fig. 8 - 12). 

<img src="./img/minimalF$.PNG" alt="minimalF$" style="zoom:30%;" />

fig. 8 *Échec cartographique #1*, Lena Krause (2019), capture d'écran



<img src="./img/artContemporain.png" alt="artContemporain" style="zoom: 50%;" />

fig. 9 *Échec cartographique #2*, Lena Krause (2019), capture d'écran

<img src="./img/smallerFail.PNG" alt="smallerFail" style="zoom:25%;" />

fig. 10 *Échec cartographique #3*, Lena Krause (2019), capture d'écran

<img src="./img/prettyFailbis.PNG" alt="prettyFailbis" style="zoom:25%;" />

fig. 11 *Échec cartographique #4*, Lena Krause (2019), capture d'écran

<img src="./img/moreorless.PNG" alt="moreorless" style="zoom: 25%;" />

fig. 12 *Échec cartographique #5*, Lena Krause (2019), capture d'écran

Nous sommes finalement parvenues à un résultat correct dans l'encodage et la projection des données (fig.13). Cette carte, que nous avons espièglement surnommée "varicelle", place un point rouge sur chaque commune présente dans CONBAVIL. Nous avons réemployé le fond de carte de 1831, cette fois non pas comme réceptacle du contenu mais en guise de contenant, tel un guide visuel situe les communes. Si les délimitation des départements s'est modifiée souvent pendant l'époque concernée, nous ne disposons pas (encore) des versions numérique de chaque division à travers le temps. Si cela enrichirait considérablement la carte, nous sommes au moins satisfaite d'avoir un fond de carte d'époque. 

<img src="./img/ProjetsConbavilFrance1831-communes.PNG" alt="ProjetsConbavilFrance1831-communes" style="zoom: 50%;" />

fig. 13 *Carte varicelle CONBAVIL*, Lena Krause (2019) capture d'écran des expérimentations cartographiques

Maintenant que chaque commune est figurée par un point, nous devons encore ajuster la taille des points en fonction du nombre de projets en ce lieu. La disproportion de délibérations à Paris a tout d'abord donné naissance à cette carte, dite "nez rouge" (fig. 14). 

<img src="./img/bigParis.PNG" alt="bigParis" style="zoom: 67%;" />

fig. 14 *Carte nez rouge CONBAVIL*, Lena Krause (2019) capture d'écran des expérimentations cartographiques

Nous avons essayé d'ajuster l'échelle, et l'excès dans l'ajustement a créé une autre carte "noyée" par ses contenus (fig. 15). Cette carte, illisible à première vue, possète toutefois un curieux potentiel herméneutique. En effet, cette carte interagit avec la position de la souris. On peut ainsi l'explorer en la survolant. Chaque cercle se révèle en changeant de couleur lorsqu'il est "actif", c'est-à-dire lorsque la souris passe dessus. Ainsi, tel un explorateur dans un grotte sombre, la souris fait office de lampe de poche qui révèle les contenus entremêlés. <!-- iframe de la carte exploratoire-->

<img src="./img/cercles.PNG" alt="cercles" style="zoom: 50%;" />

fig. 15 *Carte spéléologique de CONBAVIL*

Au cours de ce processus, nous avons également expérimenté avec d'autres librairies de code, comme leaflet.js. Cette librairie de cartographie interactive facilite grandement la tâche et permet "facilement" de créer des cartes. Entre deux échecs cartographiques, nous avons choisi de tester la fonctionnalité *heat map* ou carte thermique disponible dans la librairie[^8]. Le résultat donne une vue "empâtée" où l'on ne peut rien distinguer ni sélectionner (fig. 16). Nous avons essayé d'ajuster l'échelle, mais le rendu revenait à l'effet "nez rouge parisien" ou "beurrait épais" la surface de la France. Malgré la simplicité du code, qui inclut un fond de carte géographique et une fonctionnalité de zoom, le manque d'interactivité avec les données nous a dissuadé de continuer l'emploi de cette librairie, certes pratiques, mais un peu moins adaptées à nos préoccupations de recherche. <!-- add iframe-->

<img src="./img/heapmap_france.PNG" alt="heapmap_france" style="zoom: 25%;" />

fig. 16 *Heat map CONBAVIL*

### 3.2.2 Prototypes

Nous arrivons désormais à la section consacrée aux prototypes de ce mémoire. Malgré un côté plus "fini" que les expérimentations de la partie précédente, nous prévenons nos lecteur·rice·s qu'il y aurait encore beaucoup d'ajustement souhaités, imaginés, ou même codés mais pas tout à fait fonctionnels. Leur état est donc restreint par des contraintes temporelles, mais pourrait encore beaucoup évoluer si l'opportunité d'y retravailler advient.

#### Carte

Notre prototype de carte figure chaque commune par un point dont la taille est proportionnelle aux nombres d’affaires la concernant (fig. 17). Cette fois, l'équilibre entre la taille des points se veut plus balancé, même si Paris demeure "écrasante". L'échelle linéaire est calculé à partir de la racine carrée du nombre de délibérations, afin que les cercles de respecter le ratio plutôt que de l'augmenter exponentiellement lorsqu'il est transformé en une aire. Le fond de carte situe les communes tout en restant dans une relative abstraction, ce qui favorise la lisibilité de la carte. Les limites départementales offrent un repère géographique tout en rappelant le contexte historique. <!-- try and produce a legend in observable, then embbed it with iframe -->

<div>
    <iframe src="https://www.public.archi/atlas-numerique/viz/carteCommunes/index.html" title="Lena Krause, *[Carte des départements français et densité des projets Conbavil](https://www.public.archi/atlas-numerique/viz/carteCommunes/index.html)* (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal " width="100%" height="700" frameborder="0"  style="display:block; margin: 0 auto;">&nbsp;</iframe>
</div>
fig. 17 *[Carte des départements français et densité des projets Conbavil](http://atlas.lenamk.site/viz/carteCommunes/)* Lena Krause (2019) Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal 

Cette carte permet ainsi de mener, pour la première fois, une analyse visuelle, spatiale et quantitative des données de CONBAVIL. Une étude primaire révèle que son agencement est le reflet de la hiérarchie administrative française. Le plus grand nombre des affaires traitées par le Conseil se situent dans la capitale administrative du pays, Paris. Les projets majeurs sont regroupés dans les chefs-lieux des départements, tandis que les autres communes répertoriées font seulement l’objet de quelques délibérations, habituellement pour des affaires de moindre envergure. Ce constat fait écho à notre critique des cartes produites par Teyssot et Érouard. Cependant, l’interactivité de la carte lui confère un tout autre potentiel. L’utilisateur peut sélectionner un ou plusieurs lieux et afficher les affaires concernées[^4]. La carte n’est plus une fin en soi, mais devient un moyen de plonger dans les archives.

#### Chronologie 

La deuxième visualisation cible quant à elle les données temporelles. À partir du code de Mike Bostock, créateur de la bibliothèque D3.js (2019b), nous avons généré une chronologie des séances du Conseil précisant le nombre de projets évalués à chaque occurrence (fig. 18). Ce graphique permet ainsi de rendre compte de la fréquence des séances du Conseil et de la quantité d’affaires traitées au fil du temps. Grâce à la fonction de zoom, l’utilisateur peut modifier l’axe chronologique et examiner de manière détaillée des intervalles temporels plus restreints. En dessous de cette visualisation, la légende, qui est elle-même un graphique, sert de repère. Elle situe la section visualisée et propose un autre moyen de parcourir la chronologie. 

<div>
    <iframe width="100%" height="600" frameborder="0" style="display:block; margin: 0 auto;" src="https://www.public.archi/atlas-numerique/viz/chronologie/index.html" title="Lena Krause, [*Chronologie des séances du Conseil des bâtiments civils*](https://www.public.archi/atlas-numerique/viz/chronologie/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal">&nbsp;</iframe>
</div>
fig. 18 [*Chronologie des séances du Conseil des bâtiments civils*](http://atlas.lenamk.site/viz/chronologie/) Lena Krause (2019) Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal

Malgré tout l’intérêt de ces manipulations, l’illusion de continuité que cette figure pourrait donner à l’utilisateur constitue un problème important. En effet, le graphique génère une courbe qui relie les événements entre eux. C’est la raison pour laquelle nous avons choisi une courbe en escalier[^5], qui crée des paliers entre chaque élément, pour essayer de discrétiser l’information, c’est-à-dire la séparer en des unités distinctes. Le problème persiste néanmoins en partie, car il n’est pas possible de distinguer les séances consécutives ayant le même nombre de délibérations. En outre, on ne peut pas visualiser les interruptions dans les sources : par exemple, il n’y a pas de séance entrée dans la base de données entre le 8 octobre 1833 et le 3 janvier 1834, mais la ligne continue suggère un nombre stable de délibérations pendant toute la période (fig. 19).

<img src="http://revuecaptures.org/sites/default/files/styles/demi_largeur/public/Krause_figure_6.png?itok=zkVzrqSd" alt="img" style="zoom: 33%;" />

fig. 19 Lena Krause, *Chronologie des séances du Conseil des bâtiments civils* (détail) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal

Pour répondre à ces inconvénients, nous avons conçu un diagramme en bâtons (fig. 20). Dans cette visualisation, chaque barre représente une séance et sa hauteur le nombre de délibérations. Le nombre est également figuré par la couleur pour faciliter la lecture dans le brouhaha visuel causé par le grand nombre d'éléments visualisés. La sélection d’une barre par un clic active l’affichage des délibérations concernées. Le repérage de la séance exacte à laquelle une affaire a été évaluée offre un contexte important, car le Conseil a parfois traité plus de cinquante dossiers au cours d’une même séance, tandis que d’autres sont consacrées exclusivement à un seul projet. Toutefois, cette visualisation présente elle aussi un problème évident de lisibilité. 

<div>
    <iframe width="100%" height="128" frameborder="0"
  src="https://observablehq.com/embed/@lenamk/legendes-atlas?cells=viewof+gradientLegend">&nsbp;</iframe>
</div>

<div>
    <iframe width="100%" height="600" frameborder="0" style="display:block; margin: 0 auto;" src="https://www.public.archi/atlas-numerique/viz/barChart/index.html" title="Lena Krause, [*Séances du Conseil des bâtiments civils*](https://www.public.archi/atlas-numerique/viz/barChart/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal ">&nbsp;</iframe>
</div>
fig. 20 [*Séances du Conseil des bâtiments civils*](http://atlas.lenamk.site/viz/barChart/) Lena Krause (2019) Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal 

Limitée par son affichage sur la largeur d’un écran d’ordinateur, il nous est impossible d’y faire apparaître de façon claire les quelques 4000 séances du Conseil tenues entre 1795 et 1840. La fonction de zoom ne permet pas de changer d’échelle, uniquement d’élargir les dimensions de l’image. Malgré un travail rigoureux des couleurs, la lecture du graphique reste difficile. La solution idéale serait de parvenir à fusionner les deux graphiques en une seule visualisation, qui serait composée des barres et d’un axe chronologique interactif. Il serait également bénéfique d’ajouter quelques grands repères mettant en relation les activités du Conseil avec leur contexte historique, mais seule une connaissance fine des dynamiques politiques et administratives de l’époque permettrait des interprétations concluantes. Pour le moment, nous laissons cette tâche aux spécialistes, qui sauront enrichir la chronologie de leur expertise.

#### Typologie

Finalement, nous avons puisé dans les informations d’ordre typologique compilées dans CONBAVIL. Les chercheur·se·s chargé·e·s du dépouillement de ces données ont catégorisé les affaires évaluées par le Conseil selon leur type architectural, en se référant au *Thésaurus de la désignation des œuvres architecturales et des espaces aménagés* (Vergain, 2015)[^6]. Ce dernier classe les productions architecturales selon une typologie allant jusqu’à huit niveaux de détail. Par exemple, dans la catégorie « génie civil » figure la sous-catégorie « ouvrage d’art », qui elle-même contient « pont », « égout » ou « quai ». Ce système arborescent est judicieusement visualisé dans la version interactive du graphique circulaire à plusieurs niveaux, ou *Sunburst* (Bostock, 2018a), que nous avons élaboré (fig. 21). Chaque niveau est composé de catégories dont la largeur figure les proportions respectives. Étant limité à deux niveaux apparents, le diagramme maintient une grande lisibilité tout en donnant accès à un contenu plus détaillé par la voie de l’interactivité (Bostock, 2018b). Cette visualisation des données de CONBAVIL fournit ainsi une représentation visuelle du *Thésaurus*, qui, jusqu’à présent, ne pouvait être parcouru qu’en suivant une structure hiérarchique d’hyperliens.

<div>
    <iframe width="100%" height="800" frameborder="0" style="display:block; margin: 0 auto;" src="https://www.public.archi/atlas-numerique/viz/sunburst/index.html" title="Lena Krause, [*Répartition des projets Conbavil par type architectural*](https://www.public.archi/atlas-numerique/viz/sunburst/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal ">&nbsp;</iframe>
</div>

fig. 21 [*Répartition des projets CONBAVIL par type architectural*](http://atlas.lenamk.site/viz/sunburst/) (2019) Lena Krause Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal 

Notre soleil interactif CONBAVIL présente donc le contenu de la base de données par type architectural. Le fait de cliquer sur une catégorie permet de faire apparaître le niveau de profondeur suivant et le retour en arrière s’effectue en cliquant au centre du graphique. En glissant le curseur sur une catégorie, on peut voir le nombre de délibérations qui y sont associées. Rapidement, on constate que plus de la moitié des délibérations sont contenues dans trois catégories principales : « urbanisme », « architecture religieuse » et « architecture judiciaire, pénitentiaire ou de police ». La section « urbanisme » contient toutes les délibérations liées aux plans d’alignement des villes, car le Conseil était également responsable de l’ouverture des rues pour l’assainissement et l’embellissement des espaces publics (Château-Dutier, 2016, T1: 151-179). La prépondérance de l’architecture religieuse s’explique quant à elle par le grand nombre de réaffectations de bâtiments nationaux en écoles, préfectures et tribunaux, notamment (Woolf, 1987: 30-31).

### 3.2.3 Observations critiques

La carte comme le soleil sont des graphiques cumulatifs, ce qui signifie que certaines délibérations y figurent plusieurs fois si elles sont associées à plusieurs lieux ou types architecturaux. Cette décision provient, entre autres, d’une incertitude dans les données, qui ne signalent pas de hiérarchie en cas d’attribution multiple. Il faut également garder à l’esprit que la carte, par exemple, ne représente pas le phénomène bâtisseur, mais reflète plutôt les délibérations du Conseil. La taille des points dépend donc du nombre de mentions lors des séances et non de la quantité de chantiers ouverts. Les graphiques créés sont exploratoires, ils ont pour but de mener à la découverte du contenu des archives. C’est pourquoi il nous a semblé pertinent d’offrir le plus grand nombre de points d’entrée possibles dans les données.

Nous devons également souligner les silences dans nos visualisations. Dans le cas de la carte, celle-ci ne figure que le territoire 

 pas les affaires administratives ni toute autre délibération qui n'est pas associée à un lieu. Nous avions pensé créer une petite île, un territoire symbolique pour visualiser les affaires sans lieux. 



```
{
    "file": "FRAN/F/21/2533",
    "meeting": "1837-01-03",
    "id": "conbavil14195",
    "title": "prison pour les condamnés politiques",
    "commune": "",
    "unsureCommune": true,
    "departement": "Ile de la Réunion",
    "numDepartement": "974",
    "oldDepartement": "Isle Bourbon",
    "region": "La Réunion",
    "recommendation": "La nature de l'édifice et la situation géographique (climat) rendent le programme indispensable pour juger du projet. Le jugement rendu sera conjectural. L'absence d'enceinte et d'un chemin de ronde, indispensables en métropole, ne s'imposent peut-être pas. L'élévation des bâtiments sur 3 niveaux n'est pas souhaitable (discipline). Le toit devrait être très saillant (ombre). Une seule salle pour réfectoire et ateliers paraît insuffisante.",
    "advice": "adoption avec réserve",
    "reportAuthor": "Caristie",
    "report": "Manquent programme, devis descriptif et estimatif.",
    "participants": [],
    "buildingCategory": [
      "architecture judiciaire pénitentiaire ou de police"
    ],
    "buildingType": [
      "prison"
    ],
    "projectGenre": [
      "construction"
    ]
  },{
    "file": "FRAN/F/21/2533",
    "meeting": "1837-01-27",
    "id": "conbavil01540",
    "commune": "Salazie",
    "departement": "Ile de la Réunion",
    "numDepartement": "974",
    "oldDepartement": "Ile Bourbon",
    "region": "La Réunion",
    "eventPrecedent": "1837-01-03 (même cote, dos.1, p.1)",
    "recommendation": "esquisse n°1 la meilleure.",
    "advice": "adoption",
    "reportAuthor": "Caristie",
    "report": "A la demande du ministre de la Marine, et en l'absence de l'auteur, le rapporteur chargé de corriger le projet. Présente plusieurs variantes:- choix du site: 1 cirque naturel dans le quartier de Salazie, 'la hute du petit diable' au bord de la rivière du Mât.- prison séparée de la caserne, bâtiment d'1 niveau sur rez-de-chaussée, chambres individuelles ou jumelées, plus spacieuses que dans le 1° projet (cube d'air nécessaire dans ce climat chaud); ateliers multiples pour 'offrir aux détenus les moyens de trouver dans le travail 1 adoucissement à l'ennui de leur captivité'.",
    "participants": [
      {
        "persName": "Anonyme",
        "occupation": "ingénieur en chef",
        "role": "author"
      },
      {
        "persName": "[Du Campe de Rosamel, Claude]",
        "occupation": "ministre de la Marine",
        "role": "intervenor"
      }
    ],
    "mentionPlace": "Le Mât, rivière",
    "buildingCategory": [
      "architecture militaire",
      "architecture judiciaire pénitentiaire ou de police"
    ],
    "buildingType": [
      "bagne",
      "caserne"
    ],
    "projectGenre": [
      "construction"
    ]
  },
  {
    "file": "FRAN/F/21/2533",
    "meeting": "1837-08-28",
    "id": "conbavil13612",
    "commune": "",
    "unsureCommune": true,
    "departement": "Ile de la Réunion",
    "numDepartement": "974",
    "oldDepartement": "Isle Bourbon",
    "region": "La Réunion",
    "advice": "adoption",
    "reportAuthor": "Caristie",
    "report": "Réclamation porte sur les frais de copies de dessins, de rédaction du devis. Somme très modérée, légitimement due.",
    "participants": [],
    "fundingFees": "3.500F",
    "buildingCategory": [
      "architecture judiciaire pénitentiaire ou de police"
    ],
    "buildingType": [
      "prison"
    ],
    "projectGenre": [
      "construction"
    ],
    "administrativeObject": [
      "réclamation d'honoraires",
      "rémunération"
    ]
  },
```



Johanna Drucker distingue les représentation statiques qui référencent ou visualisent une information connue, et les "générateurs de connaissances" *knowledge generators*. Ces derniers sont dynamiques et créent des ouvertures dans leur utilisation qui possèdent le potentiel de créer de nouveaux savoir (Drucker 2013: 65) 

> Ces visualisations ne sont pas en fins en soi, mais plutôt une matière pour l'élaboration intellectuelle ̣- mouvante et incarnée dans divers modes d'inscription, mobilisant en même temps les nouveaux outils et des séquences de pratiques et des protocoles de travaux existants. Les images produites ne sont ainsi pas uniquement conçues comme des outils d'interprétation, mais aussi de tri, de paramétrage, voire même d'enrichissement et de transformation des données (caviglia 2014)



## 3.3 Editorialisation & atlas

Suite à nos expérimentations dans la production de visualisations individuelles, la création d'un instrument de recherche pour CONBAVIL requiert leur mise en commun dans un espace éditorial numérique. 

- Outil numérique --> interface
- Ensemble de cartes --> atlas
- Publication (forme éditorialie) numérique --> éditorialisation

Créer un instrument de recherche revient à concevoir une interface qui permet la manipulation et la recherche avec les données de CONBAVIL. Nous pouvons ainsi expérimenter avec des formes visuelles qui révéleraient certaines caractéristiques de l'engrenage de l'architecture publique en France. Ses besoins et ses contraintes se reflètent dans sa chronologie, dans son organisation spatiale et dans ses choix d’infrastructure. 



### 3.3.1 Théories pour la conception d'un instrument de recherche

#### Interfaces

Au sein d'une réflexion sur les *Lieux de savoir*, Christian Jacob s'intéresse à l'instrumentation de la recherche (2013). Il questionne l'ergonomie des outils disponibles, notamment pour la manipulation de données et leur exploitation intellectuelle. Le défi identifié revient à développer des environnements logiciels au sein desquels on pourra expérimenter avec les données. Ceux-ci offriraient les moyens de varier la focale, de passer du local au global et inversement, mais aussi de passer d'une visualisation à l'autre. Il s'agit d' "élaborer des outils spécifiques et pointus, répondant à des logiques intellectuelles particulières, notamment le potentiel d'instruments de visualisation qui [...] permettraient de mettre à l'épreuve des hypothèses de travail en temps réel" (  Jacob 2013: cf lien ./1180). Ces réflexions sont au cœur de notre démarche pour la conception d'un instrument de recherche. 

Les logiciels et outils numériques comportent une dimension *back-end*, les mécanismes de l'outil, et  une interface ou *front-end*, ce que l'utilisateur voit. La médiation entre les tâches et les comportements est effectuée par l'interface, qui "discipline, contraint et détermine ce qui peut être fait dans tout environnement numérique" (Drucker 2013: 139). Pour utiliser le logiciel, on passe par les éléments de l'interfaces - boutons, objets cliquables, etc. On peut également penser la structure d'une interface sous deux aspects. Le premier provient du milieu éditorial, la mise en page, c'est-à-dire l'organisation des composantes dans un espace graphique. Le second est plus dynamique, il s'agit la mise en scène de l'information, pour concevoir l'interface comme un environnement pour l'action (Drucker 2013: 139).

Les chercheur·se·s Stan Ruecker, Milena Redzikowska et Stéfan Sinclair ont théorisé le design d'interfaces visuelles pour le patrimoine culturel numérique. Il·elle·s analysent d'abord les formes classiques d'interfaces d'extraction ou de récupération (*retrieval interface*). Celles-ci, similaires à l'interface actuelle pour la recherche dans CONBAVIL, aident l'utilisateur·rice à effectuer des requêtes dans les données. L'interface présente une formulaire pour la sélection de données qui répondent à certains critères. La machine envoie les spécifications au *back-end* , qui renvoie les données correspondantes à montrer à l'utilisation dans l'interface. Ruecker, Redikowska et Sinclair démontrent les restrictions que pose ce type d'interface dans le potentiel de recherche dans les données. L'utilisateur ne peut pas voir certaines informations utiles et disponibles concernant, par exemple, les liens entre les items: les regroupements possibles, d'éventuels séquençages ou motif s dessinés par leur mise en relation (Ruecker et al. 2011: 2). Leur publication se poursuit toutefois avec la théorisation d'une forme d'interface "d'exploration riche en perspectives" ou *rich-prospect browsing*. Celle-ci serait dotée d'une série de principes conducteurs qui visualisent les possibilités, ou *affordances*, pour la recherche dans l'interface (Ruecker et al. 2011: 3-4). Ces principes incluent notamment l'affichage de grands formats ou d'une grande quantité de données, tant qu'elles sont structurées dans un logique perceptible par l'utilisateur, fournir des informations pour la navigation dans l'interface et situer l'utilisateur dans son exploration des données.

Lors de la création de nos visualisation et dans la conception de notre interface, nous nous questionnons sur la possibilité de produire un instrument de recherche centré sur l'herméneutique, qui produirait une richesse et une diversité dans l'interprétation dans les données. Il s'agirait de créer une interface dont les affordances me nous mènent pas nécessairement où on avait prévu, mais dans des espaces où on savait qu’on pouvait aller. En proposant des nouvelles perspectives incongrues, on pourrait ainsi tomber sur une dimension pertinente de l’objet qui nous intéresse. 



#### La forme-atlas

Nous avons également été inspirée par le concept d' "atlas" pour penser notre instrument de recherche. Christian Jacob définit l’atlas géographique comme un « dispositif qui permet de concilier le tout et le détail. Il est régi par une logique cumulative et analytique, qui conduit de la vision globale aux images partielles » (1992: 97).  La forme-atlas est associée à une variété de formes visuelles: cartes, mais aussi graphiques, chronologies, illustrations, et même des reproductions d'œuvres d'art. 

L'atlas prend d'autres formes encore lors de son emploi par des artistes ou par des historien·ne·s de l’art. Dans ce domaine, il peut devenir, selon Georges Didi-Huberman, une « forme visuelle du savoir » comportant « [un] paradigme *esthétique* de la forme visuelle, et [un] paradigme *épistémique* du savoir » (2011: 12). Cet outil crée des zones interstitielles, des intervalles heuristiques dans son ouverture inépuisables aux possibles.  Sa réception est une activité non linéaire : on ne *lit* pas mais on *consulte* un atlas. Cette particularité, qui introduit le multiple, le divers et l'hybridité, autorise l’émergence d’une forme de « connaissance par l’imagination » grâce à « la puissance intrinsèque du *montage* qui consiste à découvrir […] des liens que l’observation directe est incapable de discerner » (Didi-Huberman 2017: 13). 

L'atlas est donc une forme éditoriale qui répond aux critères d'instrument de recherche que nous souhaitons créer. Sa forme numérique permet de faciliter l'interactivité et la manipulation du contenu. L'interactivité des visualisations comme de l'atlas nous sert également à réduire la tentation de faire d'en faire des preuves. La forme mouvante reflète la construction, *constructedness*, de l'image. Un arrêt sur image devient un choix conscient qu'il faut argumenter et que l'on peut critiquer. Avec l'atlas, nous voulons donc expérimenter avec une forme d'épistémologie visuelle, spatiale et numérique en histoire de l'art. 

#### Éditorialisation

Le travail envisagé est un **acte éditorial**, il s’agit de donner une forme à l’objet en question : la base de données CONBAVIL. La création d’une nouvelle interface pour la base de données CONBAVIL sous la forme d’un atlas peut être comprise comme un acte d’éditorialisation[14](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote14_psr6wnd). Il s’agit d’une démarche processuelle, expérimentale et surtout multiple (Vitali-Rosati, 2016: 68). La visualisation et la cartographie ont considérablement évolué avec l’apparition des logiciels et outils informatiques. D’après les historiennes Claire Lemercier et Claire Zalc, « il n’est plus question de publier chaque tableau ou graphique péniblement obtenu, mais plutôt de les utiliser pour avancer dans une recherche, quitte à n’en montrer au lecteur final que quelques-uns » (2008: n.p.). Comparativement aux grandes équipes de chercheur·se·s, ingénieur·e·s, informaticien·ne·s, cartographes et perforateur·rice·s de cartes, indispensables aux grandes enquêtes collectives menées dans les années 70, il est de nos jours possible de réduire le personnel, le temps, les connaissances et les coûts nécessaires à la création de cartes (Lemercier, 2008)[15](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote15_7tulxje). Cela favorise particulièrement l’expérimentation, tant avec les formes et les variables graphiques qu’avec les calculs et les statistiques privilégiés pour la cartographie thématique. Aussi, les nombreuses itérations possibles au cours du processus de production nous invitent à repenser chaque élément jusqu’à ce qu’il convienne aux besoins du projet.

### 3.3.2 Un atlas numérique comme instrument de recherche

Des liens entre les visualisations ont été tissés à deux niveaux. Tout d’abord, celles-ci sont regroupées dans un même espace éditorial qui reprend le modèle de l’atlas.

<div>
   <iframe src="https://www.public.archi/atlas-numerique/viz/carteAvis/index.html" title="Lena Krause, [*Exemple d’interactivité entre deux visualisations : carte et avis du Conseil*](https://www.public.archi/atlas-numerique/viz/carteAvis/index.html) (2019), Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal ">&nsbp;</iframe>
</div>    



Des liens dynamiques intégrés dans le code permettent de relier entre elles les différentes composantes de l’atlas. Chaque graphique est créé à partir du même jeu de données. Nous avons donc pu mettre en place un système qui reproduit la sélection d’un sous-ensemble (d’un intervalle chronologique, d’un lieu ou d’une catégorie architecturale) dans les autres visualisations. Offrant d’abord un aperçu global, les visualisations se transforment ensuite au fur et à mesure du parcours interactif en des perspectives de plus en plus détaillées, qui descendent en profondeur jusqu’à la consultation d’une seule affaire. Chaque action de l’utilisateur, guidée par ses hypothèses et par ses réflexions, façonne donc la constellation que forment les données dans l’atlas. La manipulation aide la chercheuse ou le chercheur à analyser le contenu de CONBAVIL et l’invite à émettre des hypothèses sur sa signification. Pour le moment, ces liens dynamiques sont implémentés entre la carte et un graphique des avis du Conseil. Initialement, tous les lieux sont sélectionnés et le graphique figure l’ensemble des affaires. On peut ensuite modifier la sélection de lieux, ce qui entraîne un ajustement du graphique des avis. Et, inversement, la sélection d’un avis se reflète automatiquement sur la carte[12](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote12_ajhxl80). On peut ainsi observer de façon spatiale, grâce à ces liens, les dispositions du Conseil face aux projets soumis. Aussi, la dynamique entre les visualisations permet l’étude de phénomènes par la recherche des corrélations : par exemple, les membres du Conseil étaient réputés intransigeants avec les architectes de province jugés « peu capables » (Château-Dutier, 2016, T2: 591), allant jusqu’à corriger leurs projets à grands coups de crayon sur les plans fournis. Nous pouvons rechercher ce phénomène dans l’atlas, en modifiant la sélection des avis et des lieux, afin d’identifier d’éventuelles régions où le taux de refus ou de modification serait plus élevé.

Notre atlas est encore à un stade embryonnaire et il ne présente pour le moment que quelques liens actifs entre deux visualisations. Cependant, la poursuite de ce travail à l’échelle de toutes les visualisations, permet d’augmenter de façon exponentielle le nombre de constellations de données que l’utilisateur peut découvrir. De l’association entre ces innombrables possibilités et l’imagination de l’utilisateur émerge un dispositif qui active « la puissance intrinsèque du *montage* » évoquée précédemment (Didi-Hubermann, 2011: 13). L’espace de l’atlas s’organise autour d’une structure éditoriale déterminée par son autrice, tout en se transformant en fonction de l’action de son utilisateur. Si la consultation d’un atlas papier est contrainte par les éléments structurels et les repères de l’ouvrage imprimé, les lecteur·rice·s sont libres de naviguer au sein de son contenu, de suivre la proposition des éditeur·rice·s ou de se laisser porter par la sérendipité de consulter l’atlas au hasard des pages. Et ces mêmes possibilités se présentent dans notre proposition d’atlas numérique : l’utilisateur est libre d’explorer le contenu à sa guise, malgré un cadre défini d’actions possibles dans l’interface. La sérendipité, quant à elle, est permise lors des déambulations du curseur dans l’interface, lors de la sélection aléatoire d’un sous-ensemble de données, ou encore lors de l’affichage à l’écran d’une constellation de données produite au hasard[13](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote13_n6q5i5d).

[![img](http://revuecaptures.org/sites/default/files/styles/demi_largeur/public/Krause_figure_10.png?itok=LCoY6crr)](http://revuecaptures.org/sites/default/files/Krause_figure_10.png)

Lena Krause, *Modélisation de l’atlas* (2019) , Produite comme prototype dans le cadre du projet *Atlas numérique de l’architecture publique en France (1795-1840)*, Montréal : Université de Montréal 



Le potentiel de l'éditorialisation réside également dans l'évolution constante du contenu. Les technologies nécessaires pour la création de compte utilisateurs - qui pourraient, au cours de leur exploration de l'atlas, nettoyer, associer ou enrichir les données - sont disponibles. On peut également permettre l'export, statique ou interactif (intégration de la visualisation ou d'un iframe) des contenus afin de les associer à de nouvelles publications. 

### 3.3.3 L'imaginaire et ses limites



Il serait tentant de penser que l’interactivité de l’atlas déconstruit des enjeux de pouvoir dans le champ du savoir. Il ne faut toutefois pas oublier les choix effectués lors de sa production. Du point de vue du contenu, les archives sont produites par des instances dans un contexte historique déterminé, à savoir une administration française issue de la première moitié du XIXe siècle pour le Conseil des bâtiments civils. La base de données, pour sa part, est issue du travail de chercheur·se·s au tournant du XXIe siècle. Les connaissances obtenues à partir de ces données ne représentent donc pas une vérité, mais plutôt un point de vue[16](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote16_5pi61ps). En ce qui concerne l’interface de l’atlas, son élaboration se base sur diverses institutions, telles que Open Street Map pour le géoréférencement ou le thésaurus architectural de l’Inventaire général du patrimoine culturel. Ces références formatent le contenu selon des ontologies du savoir précises, des perspectives dont il n’est pas impossible de remettre la pertinence en cause. Par exemple, la toponymie contemporaine peut s’avérer problématique dans le cadre d’études historiques. Il faut donc garder à l’esprit les formes de pouvoir et d’autorité qui subsistent dans la production du savoir de notre atlas. 

C’est la raison pour laquelle nous souhaitons encourager la réutilisation et l’appropriation de son code en le publiant sous une licence libre[17](http://revuecaptures.org/article-dune-publication/constellations-de-données-historiques#footnote17_bnrpj0k). L’objectif est de faciliter les ajouts, les modifications et les contre-propositions, ainsi que la réutilisation du code pour d’autres projets. Nous savons que cela nécessite un niveau de littératie numérique encore peu répandu parmi les chercheur·se·s en histoire de l’art. Cependant, grâce à l’accessibilité et à la transparence de notre dispositif, nous invitons celles et ceux qui seraient intéressé·e·s à se former par la pratique, ou du moins à développer une compréhension plus fine du code afin de pouvoir, éventuellement, y apposer un regard critique.

Si la construction de notre atlas est un processus en constante évolution, nous pensons avoir démontré le potentiel de la cartographie et de la visualisation pour transformer l’étude d’une base de données. L’interface visuelle et interactive de l’atlas numérique offre une approche inédite du contenu des archives du Conseil des bâtiments civil et permet de renouveler la recherche en faisant usage des méthodes numériques disponibles aujourd’hui. À la manière du millefeuille topographique imaginé par Dario Gamboni, l’atlas plonge l’utilisateur dans « [des] profondeur[s] qui invite[nt] à l’excavation » (2008: 6). Il reste cependant ancré dans des préoccupations contemporaines à ses sources, afin de se distancier d’éventuels anachronismes que l’écart entre les archives du XIXe siècle et les nouvelles technologies du web appliquées à une base de données pourraient générer. S’il n’est pas toujours évident de savoir comment se servir des données dans la recherche en histoire de l’art, la cartographie et la visualisation se révèlent être des instruments précieux dans le contexte numérique.

## Notes

[^1]: Le millefeuille comme analogie des multiples couches temporelles dans une représentation topographique est une analogie imagine par Dario Gamboni dans son article *Mille fleurs ou millefeuille? Pour un inventaire à* n *dimensions *(Gamboni 2008)* *
[^2]: Nous avons utilisé [un fichier de données mis en ligne par Grégoire David](https://france-geojson.gregoiredavid.fr/) en 2018. Ce dernier partage, au format GeoJSON, les cartes des régions, départements, arrondissements, cantons et communes de France à partir  des données publiées par l’IGN et l’INSEE. 
[^3]: Le fond de carte provient de l’école d’été « Méthodes et outils  numériques : la cartographie informatique en histoire », organisée  en 2018 à l’UQAM (GRHS - PIREH).
[^4]: L’affichage du contenu textuel de la base de données est encore limité  dans l’interface, mais il est disponible, pour le moment, dans la  console du navigateur
[^5]: [La documentation de D3.js](https://github.com/d3/d3-shape#curveLinear) présente clairement les différents types de courbes et leurs biais respectifs.
[^6]: Puisque la base de données Conbavil a été créée en s’appuyant sur une version antérieure du thésaurus (*Thésaurus de l’architecture,* 2000), des ajustements mineurs ont dû être effectués
[^12]: Pour les communes actuellement françaises, elles sont documentées dans CONBAVIL selon leur nom actuel. Nous avons donc établit la concordance entre ces noms et les entités géographiques et administratives dans le fichier de [Grégoire David](https://france-geojson.gregoiredavid.fr/). Pour les autre, nous avons utilisé le service [Nominatim d’Open Street Map](https://nominatim.openstreetmap.org/).

<!-- cf chp2??? -->

[^7]: Le centroid est le centre géométrique d'une surface. Il est calculé mathématiquement et est fréquemment employé en cartographie, pour inscrire le nom des zones géographiques par exemple. 
[^8]: Avec l'aide, toujours et encore, du très excellent Arnaud Pichon