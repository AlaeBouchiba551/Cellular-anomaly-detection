# Projet de Détection d'Anomalies d'Images avec AutoEncodeurs

Ce projet vise à démontrer l'utilisation des autoencodeurs pour détecter des anomalies dans des images médicales, en se concentrant spécifiquement sur le cas d'images de cellules sanguines infectées par le paludisme.

## Objectif

L'objectif principal de ce projet est de construire un modèle d'autoencodeur capable de reconstruire des images saines tout en identifiant les anomalies dans les images infectées. Pour ce faire, le modèle utilise des techniques telles que l'erreur de reconstruction et l'estimation de densité du noyau dans l'espace latent.

## Dataset

Le jeu de données utilisé dans ce projet provient du [LHNCBC](https://lhncbc.nlm.nih.gov/LHC-publications/pubs/MalariaDatasets.html) et est spécifiquement destiné à la détection du paludisme dans les cellules sanguines.

## Structure du Projet

- **autoencoder_detection.py**: Le script principal qui contient le code pour construire, former et évaluer le modèle d'autoencodeur.
- **cell_images/**: Le répertoire sauveguardée contenant les données d'entraînement et de test, divisées en images saines et infectées.
- **README.md**: Le fichier que vous lisez actuellement, fournissant des informations sur le projet et son utilisation.

  Remarque : diviser le dossier "infected" en 2, copier à peu près 80 images dans un nouveau dossier appelé "infected-test", et modifier l'autre pour qu'il soit appelé "infected-train"
