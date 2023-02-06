# Chest_Cancer_Prediction__Python
L’objectif de ce projet est de créer un modèle de Deep Learning capable de repérer si une image représente le scanner d’une personne normal ou bien une personne attaquée par l’un des 3 types de cancer: l'adénocarcinome, le carcinome à grandes cellule et le carcinome épidermoïde.

# Dataset
The images are in jpg or png./
Data contain 3 chest cancer types which are Adenocarcinoma,Large cell carcinoma, Squamous cell carcinoma , and 1 folder for the normal cell.
Data folder is the main folder that contain all the step folders.
Inside Data folder are test , train , valid.
- test represent testing set.
- train represent training set.
- valid represent validation set.
training set is 70%
testing set is 20%
validation set is 10%

## Download link:
https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images

# Librairies
- TensorFlow: est une bibliothèque de calcul numérique open-source pour le machine learning basé sur les réseaux neuronaux. Elle dispose d’un écosystème flexible d’outils et de ressources communautaires.
- Keras: était à l’origine une plateforme d’expérimentation rapide de réseaux neuronaux profonds, mais s’est rapidement transformée en une bibliothèque ML Python autonome. Elle dispose d’un ensemble complet d’outils ML qui aide les entreprises à traiter efficacement les données de texte et d’image.
- Numpy: est une librairie fondamentale pour effectuer des calculs numériques. Elle facilite grandement la gestion des tableaux de données avec un grand nombre de fonctions permettant de générer des objets de type n-array.
- Pandas: est utilisé pour l’analyse et la manipulation des données, ainsi que pour les opérations de machine learning sous la forme de dataframes. En utilisant les dataframes, les développeurs peuvent facilement avoir une vue d’ensemble des données pour garantir une meilleure qualité du produit.
- Matplotlib : est une bibliothèque scientifique de données standard qui aide à générer des visualisations de données telles que des diagrammes et des graphiques bidimensionnels.

# Deep learning Models
- Sequential Model.
- Transfer learning: DenseNet201, ResNet50.
