# Res'O Vélo Orléans Métropole  - projet QField.

'ResOvelo_OM_VE.zip' est un fichier de projet pour l'application [QField](https://qfield.org/) qui vous permetra de suivre les différents itinéraires des propositions d’aménagements pour le Rés’O Vélo Orléans Métropole de l'association [DAMMO](https://www.dammo.fr/r%C3%A9so-v%C3%A9lo) sur votre smartphone avec un positionnement automatique sur l'écran, le niveau de zoom et l'orientation que vous désirez, ainsi que le choix du fond de carte OpenStreetMap ou Topo.

Un tracé de la route empruntée peut être affichée aussi en bleu par dessus les tracés existants.

Les fonds de carte sont affichés 'en ligne' avec une connexion internet active consommant peu de données.

![Res'O vélo QField](MD/00.jpg "Res'O vélo sur QField")
![Res'O vélo version M12](MD/00-M12.jpg "Res'O vélo avec M12")

## Utilisation du projet ResOvelo_OM_VE avec l'application QField pour smartphone.

Télécharger le fichier du projet classique ![ici](ResOvelo_OM_VE.zip) ou la version avec les panneaux M12 ![ici](ResOvelo_OM_VE-M12.zip) en utilisant le bouton 'download raw file' à droite de la ligne.
Le fichier 'ResOvelo_OM_VE.zip' ne fait que quelques dizaines de Ko.

![download project](MD/download_project.png "download project")

### Première utilisation - installation du fichier du projet dans l'application QField.

Télécharger QField sur votre store (Android, iOS, Windows, Linux, MacOS) et lancer QField:

![icône QField](MD/01-icone_QField.jpg "icône QField")

Utiliser le bouton 'Ouvrir un fichier local':

![Ouvrir](MD/02.jpg "Ouvrir un fichier local")

Utiliser le bouton vert '+' en bas à droite pour choisir le projet précédemment téléchargé à importer ...

![Bouton +](MD/21.jpg "Utiliser le bouton +")

![Bouton +](MD/03.jpg "Utiliser le bouton +")

Choisir Importer depuis le ZIP dans le menu 

![Importer depuis le ZIP](MD/04.jpg "Importer depuis le ZIP")

Se déplacer dans le dossier ou est stocké le fichier téléchargé  'ResOvelo_OM_VE.zip' et cliquer dessus pour le charger dans l'application...

![Choisir le fichier du projet](MD/05.jpg "Choisir le fichier du projet")

Le projet s'affiche avec les couches composant les Jeux de données.
Cliquez sur le nom du projet 'Res'OVélo Orléans Métropole - Version publique évolutive'

![affichage du projet](MD/06.jpg "affichage du projet et des couches")

L'écran suivant est la couche GPS point. Il suffit de valider en haut à gauche avec ✅️

![Valider](MD/07.jpg "Valider")

La carte s'affiche alors. Le bouton GPS bleu en bas à droite permet de centrer la carte sur votre position actuelle et les boutons zoom + et - permettent de régler le niveau de zoom de l'affichage. Le bouton noir en haut à gauche est le menu.

![Affichage de la carte](MD/08.jpg "Affichage de la carte")

Via le bouton du menu en haut à gauche, on peut sélectionner les couches à afficher. Une icône 👁️‍🗨️️ en face du nom de chacune des couches permet d'afficher ou d'invisibiliser la couche.
Par défaut le fond de carte est OpenStreetMap (dernière couche en bas de la liste) et la trace GPS bleue 🔵️ (première couche en haut de liste) est activée.

![Menu des couches](MD/09.jpg "Menu des couches visibles")

Zoom sur la couche OSM:

![Zoom OSM](MD/10.jpg "Zoom couche OSM")

On peut changer la couche de fond pour un style Topo en activant la visualisation de la couche Topen25 et en masquant la couche OSM

![Activation Topen25](MD/11.jpg "Activation Topen25")

Zoom sur la couche Topen25:

![Zoom Topen25](MD/12.jpg "Zoom Topen25")

Le bouton GPS bleu en bas à droite est par défaut sur fond noir et permet de déplacer le fond de carte en le faisant glisser sur l'écran tactile et en zoomant.

Un appuie sur le bouton GPS fait passer le fond en bleu et recentre la carte sur votre position.

Un deuxieme appuie permet de suivre l'orientation de la bousole et la fait apparaitre en bas à gauche tout en modifiant l'orientation du fond de carte.

Un appuie sur l'icône de la boussole en bas à gauche redresse l'orientation de la carte avec le Nord en haut de l'écran.

Pour revenir en mode de non suivi GPS, il suffit de faire glisser le fond de carte sur l'écran tactile et le fond de l'icône du bouton GPS repasse en noir.

Un nouvel appuie relance le suivi et le centrage et recommence le cycle.

![bouton GPS](MD/20.jpg "Bouton GPS et boussole")

Pour effacer le tracé de votre parcours à la fin de l'utilisation ou pour effectuer un nouveau trajet, il suffit de recharger le projet (.ZIP) après avoir fermé puis relancé l'application, toujours via le menu 'Ouvrir un fichier local ,puis '+', puis 'importer depuis le projet ZIP', puis en cliquant sur le fichier 'ResOvelo_OM_VE.zip', et enfin valider en choisisant 'IMPORTER ET ECRASER' puis le clic sur le projet pour le relancer et ✅️

![Importer](MD/30-importer.jpg "Importer et ecraser")

Pour exporter le tracé du parcours (en bleu) avant de remettre à zéro le parcours, il faut aller dans le menu et choisir le dossier de projet via le bouton Paramètres

![Bouton Menu](MD/40-bouton_Menu.png "Choisir Menu...")
![Bouton Paramètres](MD/41-bouton_Paramètres.png "Bouton Paramètres...")
![Dossier de projet](MD/40.jpg "... puis Dossier de projet")


Puis, une fois dans le dossier de projet, se positionner sur la ligne 'couche GPS.gpkg' dans le Jeux de données, et dans le menu de fin de ligne sur les trois points, choisir 'Exporter vers le dossier'.


![Exporter vers le dossier...](MD/41.jpg "Exporter vers le dossier...")

Le fichier une fois récupéré dans un dossier du smartphone peut être ouvert avec la version Desktop de QGIS sur un pc, puis il suffit d'exporter la couche points au format .gpx (avec l'option GPX_USE_EXTENSION=YES) 