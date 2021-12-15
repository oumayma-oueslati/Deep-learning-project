# Deep-learning-project
La base train contient 25 000 images de chiens et de chats. L'étiquette de chaque image de ce dossier fait partie du nom du fichier. Le dossier de test contient 12 500 images, nommées en fonction d'un identifiant numérique. Pour chaque image de la base test, on doit prédire la probabilité que l'image soit un chien (1 = chien, 0 = chat).

Pour résoudre ce problème de classification, on va utiliser un modèle pré-entraîné, ResNet-50, en remplaçant uniquement la dernière couche et le comparer avec un modèle CNN basique.

En utilisant le modèle pré-entraîné pour Keras, ResNet-50, on a pu obtenir un modèle assez bon en termes de précision de validation comparant avec le modèle CNN.
