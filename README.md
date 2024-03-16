TP1 – Hiver 2024 :

Objectif : Modèle linéaire pour la régression sur des données.

Description des données:
  La description détaillée des données est sur le site :
    https://archive.ics.uci.edu/ml/datasets/combined+cycle+power+plant
  (Combined Cycle Power Plant Data Set).
Ces données visent à construire un modèle pour prédire la quantité d’énergie électrique produite par heure d’une centrale électrique à cycle combiné. L’ensemble des données collectées contient 9568 instances. Pour chaque instance quatre caractéristiques constituant les vecteurs d’entrées sont mesurées :
  1) La température (Temperature : T) (entre 1.81°C et 37.11°C),
  2) La pression ambiante (Ambiant pressure : AP) (entre 992.89 et 1033.30 milibar)
  3) L’humidité relative (Relative Humidity: RH) (entre 25.56% et 100.16%)
  4) Le vaccum d’échappement (Exhaust Vacuum:V) (entre 25.36 et 81.56 cm Hg)
La sortie prédite (5e colonne du tableau) est l’énergie électrique nette produite par heure.

Implantation demandée:
  Tester deux cas de régression linéaire sur les données. On vous demande de choisir aléatoirement 70% des données pour l’entrainement et le restant des données pour la validation des modèles.
  
  Afficher pour chaque cas l’erreur de régression sur les données de test :
    
    Cas 1 : Utiliser une régression linéaire en combinant deux à deux les 4 caractéristiques pour la prédiction ainsi que le produit de ces caractéristiques. Afficher les graphes de régression correspondants et les erreurs moyennes du test de régression.
    
    Cas 2 : Répéter le même exercice maintenant en ayant les 4 caractéristiques combinées pour faire la prédiction et mesurer l’erreur de validation. On peut omettre d’afficher les graphes dans ce cas, mais on devrait afficher l’erreur moyenne du test de régression. 
