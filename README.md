# Classification Binaire avec CNN et TensorFlow

## Description
Ce projet est un TP visant à se familiariser avec les réseaux de neurones convolutifs (CNN) pour la classification d'images binaires en utilisant TensorFlow. Le dataset utilisé est une version simplifiée de **Food-101**, ne contenant que deux classes : **pizza** et **steak**.

## Objectifs
- Comprendre les architectures des CNN et leurs composants
- Implémenter un modèle de classification d'images binaires
- Expérimenter différentes techniques pour améliorer l'apprentissage : normalisation, data augmentation, dropout, batch normalization
- Évaluer et optimiser les performances du modèle

## Étapes du projet
1. **Préparation des données** : Chargement du dataset, division en ensembles d'entraînement et de test, transformation en batches
2. **Construction du modèle CNN** : Création d'un modèle inspiré de TinyVGG avec plusieurs couches convolutionnelles et fully connected
3. **Entraînement et évaluation** : Utilisation de `binary_crossentropy` comme fonction de perte, Adam comme optimiseur et `accuracy` comme métrique d'évaluation
4. **Amélioration du modèle** : Expérimentation avec max pooling, augmentation des données et ajustement des hyperparamètres
5. **Prédictions** : Chargement et traitement d'images personnalisées pour tester le modèle sur de nouvelles données

## Technologies utilisées
- Python
- TensorFlow / Keras
- Matplotlib (visualisation des images et des performances)
- NumPy / Pandas

## Résultats et observations
- Un modèle de base a été créé et amélioré avec des techniques comme le pooling et l'augmentation des données
- L'augmentation des données a aidé à réduire l'overfitting et à améliorer la généralisation du modèle
- L'entraînement du modèle a été évalué via les courbes de perte et d'accuracy
 

Ce projet est une introduction aux CNN et peut être étendu à la classification multi-classes ou à des architectures plus avancées comme ResNet ou EfficientNet.

