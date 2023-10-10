# Self-driving-rides

Hashcode 2018

## Description

Ce programme est une application Python utilisant la bibliothèque tkinter pour créer une interface graphique permettant de visualiser les trajets effectués par des véhicules autonomes dans un environnement donné. Les données des trajets sont lues à partir d’un fichier d’entrée (`*.txt`) et les trajets complétés sont lus à partir d’un fichier de sortie (`ends_*.txt`).

## Fonctionnalités

- Affichage des itinéraires des véhicules sous forme de lignes colorées sur un canevas.
- Zoom avant et arrière pour une meilleure visualisation.
- Défilement horizontal et vertical pour explorer l'ensemble de la carte.
- Affichage d'une légende pour interpréter les couleurs des trajets.
- Détection et affichage dans la console des trajets non attribués.

## Utilisation

1. Assurez-vous que les fichiers `*.txt` (fichier d’entrée) et `ends_*.txt` (fichier de sortie) sont dans le même répertoire que ce programme.
2. Exécutez le programme en lançant le script Python.
3. Utilisez les touches du clavier pour les actions suivantes :

   - `+` : Zoom avant
   - `-` : Zoom arrière
   - Flèche gauche : Défilement vers la gauche
   - Flèche droite : Défilement vers la droite
   - Flèche haut : Défilement vers le haut
   - Flèche bas : Défilement vers le bas

## Exemple de légende des couleurs de trajets

- Trajets non atteignables : Jaune
- Bonus non atteignable : Bleu
- Bonus atteignable : Vert

## Avertissement

Ce programme est destiné uniquement à des fins de visualisation et de démonstration. Il ne garantit pas l’exactitude ou la validité des données de trajet. Les trajets non attribués sont détectés et affichés dans la console, mais il est conseillé de vérifier les données pour une analyse plus approfondie.

## Remarques

Ce code utilise la bibliothèque tkinter pour créer l’interface graphique. Assurez-vous que tkinter est installé sur votre système pour exécuter ce programme.

## Plus de 300 trajets, c’est compliqué / ne soyez pas pressé

Si vous avez des idées d’optimisation...
