# CNN_classif_and_GradCAM

Travail réalisé lors d'un stage en laboratoire de recherche, au sein de l'Université de Technologie de Troyes

# Classification Binaire: 

Implémentation de CNN (Convolutional Neural Networks) sous Tensorflow, entraînement par GPU sur des données du monde réel :
des morceaux de roue de voiture, contenanant un défaut visuel.

Classification binaire : Défaut / abscence de défaut. Evaluation par Accuracy, Precision et Confusion Matrix
# Localisation : 

Implémentation de la localisation par [GradCAM](https://arxiv.org/abs/1610.02391) (Gradient Class Activation Maps)

Exemples de predictions : 
- En haut : Image de départ, en entrée du CNN, avec ajout de la bounding box predite
- En bas : Activation du CNN traitée par GradCAM, après seuillage

![alt text](https://github.com/lulud41/CNN_classif_and_GradCAM/blob/master/gradCAM_pred_1.png?raw=true)
![alt text](https://github.com/lulud41/CNN_classif_and_GradCAM/blob/master/gradCAM_pred2.png?raw=true)
