# PresidentialPredictML-FR

## Overview

Ce projet d'etude était l'application du Machine Learning pour prédire les résultats des élections présidentielles françaises de 2022. Par le biais de la régression et de la classification, J'ai aussi pu tester des modèles de boosting, ce travail permet de comprendre comment les données disponibles peuvent être utilisées pour anticiper les élections présidentielles françaises.

## Objectifs

- **Analyser les données** disponibles sur l'insee pour les élections présidentielles françaises.
- **Appliquer des modèles de Machine Learning** pour prédire les résultats des élections.
- **Tester l'efficacité** des différentes méthodes utilisés.

## Résultats Clés

- Une **précision de 59%** a été obtenue en utilisant des techniques de régression standards.
- En essayant **des modèles de boosting**, la précision a été améliorée, en atteignant **89%**.

## Limitations

Il est important de savoir que la précision obtenue avec ces modèles n'est pas sur pour **prédire les résultats des élections présidentielles**. Les votes sont influencés par de nombreux facteurs non quantifiables ou non disponibles dans notre dataset, tels que les événements d'actualité, les campagnes sur les réseaux sociaux, etc.

## Structure du Projet

- `/Data`: Dossier avec les datasets utilisés.
- `./`: les scripts des modèles de Machine Learning.
- `/Resultat`: Résultats générées par les modèles.

## Technologies Utilisées

- Python
- Scikit-learn pour le Machine Learning
- XGBoost et CatBoost pour le boosting
- Matplotlib et Seaborn pour la visualisation des données
