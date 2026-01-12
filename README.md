Notes finales : 

- Valentin : 11.5/20
- Valentin : 11.5/20
- Thomas : 11.5/20


# suivi-datacamp
Les points hebdomadaires se feront sur ce README.md

## DONE
- [X] Pre-processing de façon logarithmique
- [X] Calcul variance d’expression de chaque gène à travers toutes les cellules afin d’identifier les gènes les plus informatifs.
- [X] Visualisation de la distribution des variances afin de choisir un seuil ou un nombre fixe de gènes hautement variables (HVGs).
- [X] Tests de différentes méthodes de resampling et comparaison par visualisation sous forme de PCA
- [X] Implémentation algorithme XGBoost via le fichier xgboost.py . Option de tuning et de regularisation
- [X] Création pipeline et classifier pour XGBoost
- [X] Submissions sur RAMP avec le modèle XGBoost
- [X] Fine-tuning XGBoost et submissions du modèle avec la meilleure accuracy 
- [X] Mise en place de notebooks globaux pour la partie pre-processing, la partie pipeline et la partie fine-tuning

## Conclusion
Analyse des données via pre-processing et application de méthodes tel que le resampling
Lancement d'un PCA sur un nombre fixe de variables pour récupérer les variables les plus descriptives du dataset
Création fichier classifier pour les méthodes de classification choisi et lancement submission sur RAMP
Meilleure accuracy de 0.84 et un training time de 18s avec un modèle XGBoost ou un modèle l'approximant
