---
comments: hidden
published: true
layout: post
title: Utilisation de la découpeuse laser
author: Camille
categories:
  - Découpeuse_laser
---
## Préparez votre fichier

* réalisez votre dessin avec un logiciel de dessin vectoriel (nous utilisons [Inkscape](https://inkscape.org/fr/), logiciel libre et gratuit)
* transformez tous vos objets en chemins (//sélectionnez vos objets > Chemin > Objets en chemins//)
* coloriez en rouge (RGBA 255, 0, 0, 255) les traits que vous souhaitez **découper** (//Objet > Remplissage et contour//)
* coloriez en noir (RGBA 0, 0, 0, 255) les traits que vous souhaitez **graver** (//Objet > Remplissage et contour//)
	* vous pouvez aussi utiliser des niveaux de gris pour moduler la profondeur de gravure
* réglez l'épaisseur des traits à **0,01 mm** (//Objet > Remplissage et contour//)
* rédimensionnez la page à la taille du dessin (//Fichier > Propriétés du document > Redimensionner la page au contenu > Ajuster la page au dessin ou à la sélection//)
* enregistrez votre fichier en .SVG (//Fichier > Enregistrer sous//)

## Préparer la découpeuse laser

* placer la planche
* allumer la découpeuse laser
* placer le faisceau sur la surface de découpe avec les boutons à droite
* placer le curseur en équilibre
* monter le plateau doucement jusqu'à ce que le curseur tombe

## Paramétrer le travail

* ouvrir le fichier .SVG dans Inkscape
* Fichier > Imprimer : sélectionner Trotec, puis Préférences
	* surface de découpe : 600mm x 300mm
    * matière : sélectionner le type et l'épaisseur
* lancer l'impression : le logiciel JC s'ouvre et demande un nom pour le nouveau "job"
* le fichier devrait apparaître dans le menu de droite : le placer sur la surface de découpe par cliquer-glisser
* sélectionner tous les "jobs" puis cliquer sur Mise à jour pour avoir une estimation du temps de coupe et de gravure
* connecter la découpeuse avec le bouton en bas à droite
* lancer le travail avec le bouton en bas à droite
