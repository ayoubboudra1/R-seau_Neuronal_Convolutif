# README.md

## Réseau Neuronal Convolutif avec TensorFlow et PyTorch

Ce projet présente deux implémentations de réseaux neuronaux convolutifs (CNN) pour la reconnaissance d'images, utilisant TensorFlow et PyTorch.

### Contenu

1. **tp2_cnn_mnist.ipynb**  
Ce projet présente un réseau neuronal convolutif (CNN) implémenté avec PyTorch pour la reconnaissance des chiffres manuscrits à partir du jeu de données MNIST. Il commence par établir une connexion entre Kaggle et Google Colab pour télécharger les données nécessaires. Ensuite, les données sont décompressées et préparées pour l’entraînement. Le code utilise diverses bibliothèques comme torch, torchvision, et pandas pour manipuler et visualiser les données. Ce projet illustre les étapes fondamentales de la construction et de l'entraînement d'un modèle CNN pour la classification d'images.

2. **tp2_cnn_tensorflow.ipynb**
Ce TP a pour objectif de créer un modèle classique de classification des chiffres en utilisant un réseau de neurones convolutif (CNN) avec TensorFlow. Il commence par l'importation des bibliothèques nécessaires, puis charge et normalise la base de données MNIST. Après avoir visualisé quelques exemples d'images, le TP aborde la construction et l'entraînement du modèle. Les résultats sont évalués à l'aide de métriques appropriées. Ce projet illustre l'application pratique des CNN dans le domaine de la reconnaissance d'images.

3. **tp2_dogchat.ipynb**  
Ce projet utilise un ensemble de données de Kaggle pour entraîner un modèle de classification d'images afin de distinguer les chiens des chats. Le notebook commence par établir une connexion entre Kaggle et Google Colab, suivi du téléchargement et de la décompression du jeu de données. Les images sont ensuite organisées pour faciliter l'entraînement. Ce travail est réalisé sur un GPU pour optimiser les performances. Les résultats de l'entraînement seront utilisés pour évaluer l'efficacité du modèle.

### Prérequis

- Python 3.x
- TensorFlow
- PyTorch
- Bibliothèques supplémentaires : NumPy, Pandas, Matplotlib
