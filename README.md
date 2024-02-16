# patients-anomalies-detection

#### 1. Contexte
Vous êtes le nouveau Data Scientist dans un centre de recherche en cardiologie. Un des grands cardiologues du centre vous propose de l’aider à mettre en place une approche de détection automatique des anomalies grâce aux données des électrocardiogrammes des patients.

Il vous met à disposition un jeu de données où chaque ligne représente les mesures de l’électrocardiogramme d’un patient. La dernière colonne permet de labelliser les patients :

  - “0” lorsqu’ils sont sains

  - “1” lorsqu’ils comportent une anomalie.

Les autres colonnes représentent les différents points de mesures de l'électrocardiogramme pour chaque patient.

Le médecin vous dit :

“Nous désirons nous servir de ce dataset pour entraîner un modèle nous permettant de déterminer automatiquement si un nouvel électrocardiogramme que nous mettons en entrée est sain ou s’il présente une anomalie. Cela nous serait très précieux pour améliorer la prise en charge rapide des patients”


#### 2. Consignes

  - Chargez le dataset suivant “ecg.csv”. Observez la dernière colonne du jeu de données pour vérifier que l’échantillon est bien équilibré (c’est à dire que la proportion des électrocardiogrammes sains et comportant une anomalie sont sensiblement identiques).

  - Construisez une SVM avec un gamma de 50 et observez sa courbe ROC comme vu dans le cours.

  - Optimisez les performances de votre modèle à l’aide d’une validation croisée.

  - Grâce à votre modèle optimisé, quelle valeur d’aire sous la courbe ROC sur le jeu de données de test obtenez-vous ?