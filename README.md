# <span style='background:blue'>Contexte</span>

L'entreprise **"Fruits!"** est une jeune entreprise qui a la volonté de préserver la biodiversité des fruits en permettant des traitements spécifiques pour chaque espèce de fruit en développant des robots cueilleurs intelligents.

Pour cela, l'entreprise souhaite se faire connaitre en mettant à disposition du grand public une application mobile qui permettrait aux utilisateurs de prendre en photo un fruit et d'obtenir des informations sur ce fruit. Le developpement de cette application nécessite un traitement Big Data pour la reconnaissance d'image.


# <span style='background:blue'>Missions</span>

1/ Expliquer pas-à-pas le script PySpark implémenté avec :
- Un traitement de diffusion des poids du modèle Tensorflow sur les clusters (broadcast des « weights » du modèle)

- Une étape d’une réduction de dimension de type ACP en PySpark

2/ Faire une démonstration de la mise en place d’une instance EMR opérationnelle.

3/ Démontrer le respect des contraintes RGPD (serveurs situés sur le territoire européen).

4/ Donner mon retour critique sur cette solution (utile avant de la généraliser).


# <span style='background:blue'>Dataset</span>

Ce jeux de données comporte des images de fruits pour train et test un modèle de reconnaissance d'image.

Nombre d'images : 90_483<br>
Nombre de classes : 131<br>
Taille des images : 100x100 pixels<br>

3 dossiers :
- Training (67_692 images)
- Test (22_688 images)
- test-multiple_fruits

Source : [Fruits-360 dataset](https://www.kaggle.com/datasets/moltean/fruits) sur Kaggle.com<br>


# <span style='background:blue'>Fichiers du dépôt</span>

- **Berthe_Pierrick_1_notebook_062024.ipynb** : Noteboook de traitement des images avec la réduction de dimension ACP sur PySpark et déployé sur un cluster EMR d'AWS.

- **Berthe_Pierrick_2_images_csv_062024.ipynb** : Notebook pour prouver que les images du dataset et le fichier CSV d'export ont bien été présents sur le cluster EMR du cloud.

- **Berthe_Pierrick_5_presentation_062024.pdf** : Présentation des résultats


# <span style='background:blue'>Auteur</span>

Pierrick BERTHE<br>
Juin 2024
