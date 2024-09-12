# Image Classification Project

## Description
Ce projet utilise un modèle de deep learning pour effectuer la classification d'images en deux catégories : `Happy` et `Sad`. Le modèle est construit à l'aide de TensorFlow et Keras, et il est entraîné sur un ensemble de données d'images organisées en deux classes. 

## Structure du Projet
- **data/** : Contient les images utilisées pour l'entraînement et la validation du modèle.
- **models/** : Emplacement où les modèles entraînés sont sauvegardés.
- **logs/** : Contient les logs de TensorBoard pour le suivi de l'entraînement du modèle.
- **ImageClassification/** : Répertoire contenant le code source du projet.
- **Getting Started.ipynb** : Notebook Jupyter contenant le code utilisé pour construire, entraîner, et évaluer le modèle.

## Prérequis
- Python 
- TensorFlow 
- OpenCV
- Matplotlib

Vous pouvez installer toutes les dépendances nécessaires en utilisant `pip` :
```bash
pip install tensorflow opencv-python matplotlib
Installation
Clonez le dépôt :
git clone https://github.com/HichemMhadhbi/Happy-and-sad-model-CNN.git 
Naviguez dans le répertoire du projet :
cd Classification_Project
Assurez-vous que toutes les dépendances sont installées en utilisant pip :
terminal : .\deepproj\Scripts\activate

Utilisation
Prétraitement des données : Les images sont chargées et redimensionnées pour être uniformes. Elles sont ensuite normalisées pour être utilisées par le modèle.
Entraînement du modèle : Le modèle de réseau de neurones convolutifs (CNN) est entraîné sur les données prétraitées. Les métriques de performance, telles que la précision et la perte, sont suivies à l'aide de TensorBoard.
Évaluation : Le modèle est évalué sur un ensemble de données de test pour vérifier sa précision.
Prédiction : Le modèle est utilisé pour prédire la classe des nouvelles images.
Pour exécuter le notebook Jupyter et reproduire les étapes, utilisez la commande suivante :

jupyter notebook Getting\ Started.ipynb
Résultats
Le modèle atteint une précision de 100% sur l'ensemble de test, avec des scores de précision et de rappel parfaits, indiquant un modèle bien entraîné sans erreurs de classification.

Sauvegarde et Chargement du Modèle
Le modèle peut être sauvegardé au format HDF5 (.h5) ou au format Keras (.keras). Pour charger un modèle sauvegardé, utilisez le code suivant :

from tensorflow.keras.models import load_model
new_model = load_model('imageclassifier.h5')  # ou 'imageclassifier.keras'
Contributions
Les contributions sont les bienvenues. Veuillez soumettre un pull request avec des suggestions d'améliorations ou de nouvelles fonctionnalités.

License
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

### Explication des sections :
- **Description** : Un résumé de ce que fait le projet.
- **Structure du Projet** : Décrit les principaux répertoires et fichiers dans le projet.
- **Prérequis** : Liste les logiciels et bibliothèques nécessaires pour exécuter le projet.
- **Installation** : Guide pour cloner le dépôt et installer les dépendances.
- **Utilisation** : Explique comment utiliser le projet, y compris l'entraînement du modèle et les prédictions.
- **Résultats** : Décrit les résultats obtenus par le modèle.
- **Sauvegarde et Chargement du Modèle** : Donne des instructions pour la gestion des modèles sauvegardés.
- **Contributions** : Encourage les autres développeurs à contribuer au projet.
- **License** : Spécifie la licence sous laquelle le projet est distribué.
