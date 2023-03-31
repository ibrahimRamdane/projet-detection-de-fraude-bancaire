# Détecteur de fraude sur des transactions bancaires
Projet assez conséquent pour la détection de fraude sur des transactions bancaires

## Description
Ce projet a pour but de reconnaitre à l’aide d'une base de donnée si oui ou non, une transaction est frauduleuse. La base de donnée utilisée est composée de données banquaires associés à des transaction. Ces données sont un ensemble de variables explicatives, ainsi qu’une classe. La majorité des variables explicatives sont inconnus. Seulement la tranaction et sa valeur le sont. La classe de la valeur correspond au fait que la transaction soit frauduleuse ou non.
La base de donnée utilisée a été trouvé sur kaggle et est télechargeable sur mon repertoire git au nom 'Credit Card Fraud Detection(1).zip'.

Afin d’étudier les données différents algorithme de classification ont été utilisé et une régression logistique a été réalisé (car il n'y avait que 2 classes à prédire).

Dans ce projet la donnée étudiée en priorité a été le recall car l'enjeu est de ne laisser passer aucune transaction frauduleuse. De plus, nous ne voulons pas que trop de transactions soient faussement reconnu comme étant frauduleuses, donc la précision a aussi été analysée.

## Installation et Run
Le projet a été réalisé sur un NoteBook donc tous les résultats sont déja affichés il suffit uniquement d'ouvrir le fichier "PROJET_DETECTION_FRAUDE.ipynb".
Si jamais vous voulez run le code, pour aller plus loin (faire une ACP) ou faire des modification, il vous faudra créer un dossier dans lequel vous placerez la base de donnée et le notebook. Vous ouvrirez ensuite le dossier avec vscode ou jupiter notebook puis vous changerez l'emplacement du répertoire par rapport à ou vous aurez placé le dossier sur votre ordinateur. 
