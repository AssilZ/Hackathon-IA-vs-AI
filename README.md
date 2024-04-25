# Hackathon-IA-vs-AI

Ce dépôt contient les différentes implémentations et analyses réalisées dans le cadre du Hackathon IA vs AI.

## Contenu du dépôt

- `analyse_datasets` : Une petite analyse des datasets utilisés.
- `bayesien_naif_dataset1` : Implémentation du modèle Bayésien Naïf pour le dataset 1.
- `bayesien_naif_dataset2` : Implémentation du modèle Bayésien Naïf pour le dataset 2.
- `logistic_regression` : Implémentation de la régression logistique pour le dataset 1.
- `logistic_regression2` : Implémentation de la régression logistique pour le dataset 2.
- `distilbert_dataset1` : Implémentation du modèle DistilBERT pour le dataset 1.
- `distilbert_dataset2` : Implémentation du modèle DistilBERT pour le dataset 2.
- `roberta_dataset2` : Implémentation du modèle RoBERTa pour le dataset 2.
- `albert_dataset2` : Implémentation du modèle ALBERT pour le dataset 2.

## Modèles pré-entraînés

Il est possible de récupérer des modèles pré-entraînés stockés sur Google Drive afin de ne pas avoir à réentraîner les modèles. Les modèles sont disponibles à ce lien : [Modèles pré-entraînés](https://drive.google.com/drive/folders/1bKuM64KGuQfA1raGojiZHwIQznKIEy9y?usp=sharing)

Pour utiliser un modèle pré-entraîné, il suffit de le télécharger et de le placer à la racine du dépôt.

## Configuration requise

- Python 3.x
- Bibliothèques Python : numpy, pandas, scikit-learn, torch, transformers

## Installation

1. Clonez ce dépôt : `git clone https://github.com/votre_username/Hackathon-IA-vs-AI.git`
2. Accédez au répertoire du projet : `cd Hackathon-IA-vs-AI`

## Utilisation

Chaque dossier contient un script principal qui peut être exécuté pour lancer l'entraînement et l'évaluation du modèle correspondant. Assurez-vous d'avoir les datasets nécessaires et les modèles pré-entraînés (si utilisés) avant d'exécuter les scripts.
