# GMQ580_TravailSession_JT_LM
## Objectif du projet :
### À partir d'image satellite Sentinel-2, appliquer un calcul de NDAI (Normalized Difference Algae Index) sur une plage de valeur déterminée par l'utilisateur pour détecter le niveau de concentration d'algue dans l'eau.

## Les librairies utilisées :
### NumPy, pour manipuler des matrices, et GDAL, pour lire et traiter les formats d'images géospatiales.

## Pour utiliser l'extension, l'utilisateur doit : 
### Avoir une image Sentinel-2 avec les bandes B1, B2, B3, B4, B8
### Insérer manuellement un seuil de NDAI au format décimal « . » séparé par une virgule. ex : (0.5,0.6)

## Étapes à suivre pour l'installation de l'extension :
### Pour ajouter le script dans la Toolbox de Qgis, il faut tout d'abord avoir télécharger le dossier aquatic_plants_detector.
### Par la suite, ouvrir Qgis, aller dans | Préférences | Profils utilisateurs | Ouvrir le dossier du profil actif |.
### Ensuite, l'explorateur de fichier va s'ouvrir. Ouvrir le dossier python -> plugins et insérer le fichier aquatic_plants_detector.
### Maintenant, retourner sur Qgis, aller dans l'onglet | Extensions | Installer/Gérer les extensions | Installées | et cocher l'extension que vous avez ajouté.
### Finalement, ouvrir la boîte à outils et l'outil devrait être présent vers la fin de la liste.
