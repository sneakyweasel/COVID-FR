# COVID-FR

Liste des projets open-source pour pallier rapidement à la crise sanitaire du COVID-19.

## Présentation

- Plusieurs efforts open-source collaboratifs sont en cours et la communauté makers / hackers se mobilise pour tenter de pallier très rapidement au manque critique de matériel.
- J’ai cofondé une NGO médicale il y plus de 10 ans [Action Aide Asie](http://actionaideasie.com/) avec lequel j’ai fait plusieurs dizaines de missions en Asie du Sud-Est, je m’occupe également d’une association de précarité lourde en milieu hospitalier en France. [Amis des Malades](http://amisdesmalades.com/)
- Mon oncle Christophe est responsable de l’hôpital COVID-19 de Calot et son fils Romain est en première ligne comme médecin militaire urgentiste dans l’Est. Je suis en contact avec eux et ils ont manifesté le besoin urgent de certains équipements.
- L'expérience que j'ai acquise du système de santé des pays en voie de développement lors de mes missions montre le courage et la capacité d'adaptation des médecins face à la pénurie d'équipement, ces mêmes qualités dont nous avons besoin maintenant en France.

## Situation

- Une pénurie de matériel médical de protection et de ventilateurs de réanimation est en cours et devrait conduire à de très nombreux decès potentiellent évitables.
- Des capacités de production rapide grâce aux techniques d'impression 3D et de prototypage rapide existent en France et pourraient être mobilisées en quelques jours.
- Les autres pays industriels sont dans la même situation que nous et il ne faut pas espérer d'aide internationale rapide.
- Le fort ralentissement de l'industrie chinoise va également entrainer des pénuries d'approvisionnement de pièces nécessaires au fonctionnement de notre système de santé.

## Collaboration

- De nombreux ingénieurs, spécialistes et codeurs sont actuellement confinés chez eux et pourraient apporter une aide précieuse pour pallier à la situation de crise que nous affrontons.
- Plusieurs gouvernements, entreprises et particuliers dans le monde travaillent au prototypage et à la fabrication rapide de ces équipements.
- La France dispose d'un large parc d'imprimantes 3D, de fraiseuses numériques et de capacité de production à la demande qui pourraient être mobilisées en quelques heures / jours.
- La mobilisation de ces capacités de production pourrait permettre la réalisation très rapide de matériel pour protéger nos soignants et éviter de nombreuses pertes humaines.
  
## Liste des appels à projet / concours internationaux COVID

- [Ministère de la Défense FR](https://www.defense.gouv.fr/aid/appels-a-projets/appel-a-projets-lutte-covid-19)
- [Université Mc Gill Canada](https://www.agorize.com/fr/challenges/code-life-challenge)

## Logistique

- Un des principaux problèmes est l'acheminement des matériels fabriqués vers les hopitaux et ceux qui en ont besoin. On pourrait imaginer que la Poste, les livreurs ou un autre service récupère la production des particuliers et l'achemine vers les hôpitaux locaux.
- On pourrait imaginer de petites unités de production de quelques imprimantes situées dans/à coté des hôpitaux qui produiraient en flux tendu les éléments nécessaires pour le personnel soignant.

## Liste des projets intéressants

Veuillez me contacter si vous souhaitez ajouter des projets à cette liste.

### Protection des soignants

La protection des soignants est cruciale, la pénurie de moyens de protection est forte et l'utilisation de masque jetables n'est pas forcément optimale si la crise persiste (changement de masque toutes les 8h). Il faudrait une solution plus pérenne.

#### Visière de protection imprimées Prusa (Statut: OK)

- **PRESENTATION** Le retour des médecins urgentistes "au front" montre qu'il y a de nombreuses projections par les patients et une forte chance de contamination du personnel soignant. Les autres personnes exposés comme les médecins de ville, caissiers, etc. pourrait également bénéficier de ces visières. La production a déjà commencé, manque la logistique.
- **SITE** [Visière PRUSA](https://www.prusaprinters.org/prints/25857-protective-face-shield-rc1)
- **VALIDATION** Ce projet a été validé par le ministère de la Santé Tchèque.
- **TEMPS PAR UNITE** 2h / imprimante soit 12 visières / jour / imprimante
- **CAHIER DES CHARGES**
  - PLA / PETG
  - Feuille de plexiglass (ou autre) de 0.5mm
  - Rouleau de bande élastique
- **PRIX PAR UNITE** 1-2€
- **BESOINS**
  - Fabriquants / distributeurs de feuille plastique transparent d'environ 5mm
  - Imprimantes de particuliers / mise à disposition des parcs d'imprimantes à la demande (FabLab, particuliers, services à la demande, etc.)
  - Solution logistique pour les faire arriver rapidement au personnel soignant malgré le confinement.

#### Projet de masque réutilisables à pression positive PAPR "Snorky" (Statut: En cours)

- **PRESENTATION** Les respirateurs à pression positive mettent sous pression légère l'équipement de protection de façon à ce qu'en cas de fuite l'air contaminé ne puisse pas rentrer. C'est la protection utilisée dans les laboratoires de virologie BSL-3 et un des meilleurs équipement possible pour les soignants. [PAPR](https://en.wikipedia.org/wiki/Powered_air-purifying_respirator) (Besoin de traduction wikipedia FR). Le projet utilise un masque de plongée intégral (largement disponible et très bien conçus: Décathlon Easybreath, visiblement plusieurs milliers en stock) qui est confortable et par définition étanche modifié pour recevoir un équipement de filtration FPP3 à la place du tuba.
- **VALIDATION** En cours
- **TEMPS PAR UNITE**
  - Version simple: environ 2h
  - Version pression positive: environ 6h
- **CAHIER DES CHARGES**
  - MASQUE:
    - Masque EasyBreath Decathlon ou copie chinoise 20€
    - Connecteur tuba / ventilation imprimé en 3D
  - CARTOUCHE:
    - Cartouche imprimées 3D jetable 2€
    - Joint d'étanchéité pour la cartouche 0.5€
    - Filtre HEPA industriel d'aspirateur (filtration similaire FPP3) 2€
  - SYSTEME DE VENTILATION:
    - Ventilateur de PC 12v PWM
    - Batterie 12V de type perceuse
    - Coque imprimée en 3D
    - Système mécanique ou éléctronique de régulation du débit d'air
    - Tuyau de raccord ventilation & masque
- **PRIX PAR UNITE** 50-60€
- **BESOINS**
  - besoin de retours de médecins
  - besoin de spécialiste fabriquant / connaissant ces équipements
  - besoin de retour sur la stérilisation (eau bouillante, alcool, UV, impact sur les plastiques et silicones à voir ?)
  - besoin d'ingénieurs et de spécialiste de mécanique des fluides

### RESPIRATEURS D'URGENCE

Les anglais estiment visiblement à 25000 le pic de besoin en respirateurs, il en ont visiblement 5000 disponibles. Plusieurs idées et projets pourraient être d’une utilité vitale.
Une communauté active de plusieurs dizaines de personnes travaille dèjà (en anglais) sur ces projets [ProjectOpenAir](https://www.projectopenair.org/)

#### Valve de dédoublement des respirateurs médicaux (Statut: OK)

- **PRESENTATION** Si les patients ont environ le même volume pulmonaire il est possible d'alimenter jusqu'à 4 patients avec le même respirateur sans trop leur nuire. Cela augmente potentiellement la capacité de réanimation ventilatoire existante. [Article Hackaday](https://hackaday.com/2020/03/19/saving-4-patients-with-just-1-ventilator/), [Vidéo](https://www.youtube.com/watch?v=uClq978oohY&feature=emb_title)
- **VALIDATION** Oui (Publication: <https://onlinelibrary.wiley.com/doi/epdf/10.1197/j.aem.2006.05.009>)
- **SITE** [Fichiers 3D](https://github.com/Judoguy12/4-way-ventilator)
- **TEMPS PAR UNITE** environ 10h
- **PRIX PAR UNITE** 2€
- **CAHIER DES CHARGES**
  - PLA ou impression dans un matériel pro avec Sculpteo
- **BESOINS**
  - Besoin de connaitre les modèles des hôpitaux français, les tailles d'entrée, sortie pour le design paramétrique.
  - A quel point cela gène-t'il les patients?

#### Respirateurs vétérinaires (Statut: En cours)

- **PRESENTATION** Il semblerait que les anglais aient réquisitionné certains ventilateurs vétérinaires possèdant des caractéristiques proches de ceux pour les humains.

### Projet d'adaptation de respirateur CPAP (Statut: Avancé)

- **PRESENTATION** Convertir un respirateur pour les apnées du sommeil en changeant son logiciel afin de le convertir pour le COVID-19. C'est le projet actuel qui semble le plus avancé.
- **SITE** [Fichiers et Code](https://github.com/jcl5m1/ventilator)

### AUTRES

- L’impression 3D pourrait également permettre d’imprimer localement les différents éléments : valves, etc. dont les hôpitaux pourraient avoir besoin comme le cas italien des valves à 10.000€

### FAQ

`Comment comptez-vous réunir les imprimantes nécessaires, et où?`
• Il existe de large parcs d’imprimantes 3D en France, FabLab et universités avec des services en ligne comme [Sculpteo](https://www.sculpteo.com/fr/) qui pourrait être utilisés.
• Des distributeurs d’imprimantes comme [Atome 3D](https://www.atome3d.com/) possèdent de nombreuses imprimantes en stock.
• Il existe également plusieurs entreprises et universités ayant des parcs d’imprimantes disponibles.
• Je ne connais pas la taille du parc des imprimantes de particuliers en France, mais je pense qu’il y a plusieurs milliers de machines.
On pourrait imaginer une fois les modèles 3D validés par les experts que la production commence à l’instant même, une fois configurée leur fonctionnement n’est pas très différent d’une photocopieuse.
On pourrait également imaginer que de petits parcs de quelques imprimantes soient installés à coté / dans les hôpitaux pour pallier en flux tendus aux demandes de pièces plastiques : (valves, cartouches jetables, etc.) Il existe des risques de pénuries de pièces détachées suite au fort ralentissement de la production chinoise.

`Comment définir les priorités de distribution des produits finis?`
Une idée serait d’avoir dans/à coté de l’hôpital un petit parc d’imprimante qui produise en flux tendu à la demande les pièces en PLA nécessaires en quelques minutes / heures. Ceci est très différent des circuits longs de l’industrie classique.
Sculpteo ou d’autres services pourrait fournir les pièces plus complexes en Nylon, etc. et les livrer.

`Comment bypasser le protocole d'homologation des produits médicaux?`
Les matériels médicaux homologués seront évidemment prioritaires par rapport aux matériels imprimés. Il s’agit plutôt de pallier une situation de pénurie critique et vitale avec des solutions rapides.
Si le cas devait se poser entre aucun respirateur et un respirateur 3D non homologué je pense que le choix pourrait être simple.
Le design collaboratif médical existe déjà avec des projets de matériel libre (à lire [Matériel libre](https://fr.wikipedia.org/wiki/Mat%C3%A9riel_libre)). Un exemple de projet open-hardware médical est le projet d’écho-stéthoscope à 50€: [Echopen](http://www.echopen.org/)

`Avez-vous en tête un objectif de date pour lancer une production?`
La production pourrait commencer instantément une fois les modèles 3D basiques conçus avec la possibilité d’une amélioration de la qualité des pièces avec le retour des utilisateurs suivant le modèle open-source.

Les étapes de ce circuit court en heures / jours pourraient être:
• Dessin paramétrique 3D d’un modèle basique fonctionnel
• Validation par un panel d’experts et ingénieurs confinés ou à la retraite
• Publication du modèle 3D libre de droit sur des plateforme de distribution comme GitHub ou Thingiverse.
• Téléchargement du modèle 3D par les parcs d’imprimantes / particuliers 
• Impression des pièces dans l’hôpital ou livraison express
• Retour des soignants sur les défauts / amélioration des pièces produites.
• Nouveau cycle de dessin, d’amélioration, impression et distribution pour la v2, v3, etc. tous les quelques jours.
