# Prédiction et analyse des délais de livraison des conteneurs de la Chine aux États-Unis

Projet personnel de science des données appliqué à la logistique maritime

## Objectif
Améliorer les prédiction des délais de livraison en comparant en nouveau modèle à un modèle déjà existant

## Contenu
- Jeu de données : '[Container Tracking Data.xlsx](https://www.kaggle.com/datasets/muzammalnawaz/container-tracking-data-set)'
- Notebook : '[Container Tracking Notebook](https://colab.research.google.com/drive/1QM6vU62aO0sHL7veBEyvsyO-o7V_26OW?usp=sharing)'

## Méthodologie
- Nettoyage des données de tracking incohérentes
- Décomposition du délai en sous-étapes logistiques
- Analyse des erreurs du modèle existant
- Construction d'un modèle Random Forest (régression par forêt aléatoire)
- Comparaison des performances des deux modèles (calcul de l'erreur absolue moyenne et du coefficient R^2)
- Identification des facteurs déterminants la prédiction  du délai

## Résultat
Réduction de l'erreur moyenne de prédiction de 3,93 à 3,01 jours (non négligeables à l'échelle du tracking de milliers de conteneurs
