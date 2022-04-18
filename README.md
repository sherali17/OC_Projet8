# OC_Projet8
Déployez un modèle dans le cloud

## Contexte
Une très jeune start-up de l'AgriTech, nommée  "Fruits!", cherche à proposer des solutions innovantes pour la récolte 
des fruits.

La volonté de l’entreprise est de préserver la biodiversité des fruits en permettant des traitements spécifiques 
pour chaque espèce de fruits en développant des robots cueilleurs intelligents.

La start-up souhaite dans un premier temps se faire connaître en mettant à disposition du grand public une application
mobile qui permettrait aux utilisateurs de prendre en photo un fruit et d'obtenir des informations sur ce fruit.

Pour la start-up, cette application permettrait de sensibiliser le grand public à la biodiversité des fruits et de 
mettre en place une première version du moteur de classification des images de fruits.

De plus, le développement de l’application mobile permettra de construire une première version de l'architecture 
Big Data nécessaire.

## Mission
Développer dans un environnement Big Data une première chaîne de traitement des données qui comprendra le preprocessing
et une étape de réduction de dimension.

Il n’est pas nécessaire d’entraîner un modèle pour le moment.
L’important est de mettre en place les premières briques de traitement qui serviront lorsqu’il faudra passer à l’échelle
en termes de volume de données !

## Contraintes
Tenir compte dans nos développements du fait que le volume de données va augmenter très rapidement après la livraison 
de ce projet. Nous développerons donc des scripts en Pyspark et utiliserons par exemple le cloud AWS pour profiter
d’une architecture Big Data (EC2, S3, IAM), basée sur un serveur EC2 Linux.

## Données
Les données sont disponibles à l'adresse :
https://www.kaggle.com/datasets/moltean/fruits
