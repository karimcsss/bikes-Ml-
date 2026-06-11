

# Bike Share — Apprentissage supervisé

Résumé
---
Notebook d'analyse et de régression pour prédire le nombre de locations quotidiennes de vélos à partir du jeu de données `daily-bike-share.csv`. Projet réalisé en collaboration avec Microsoft Learn (mslearn).

Contenu du dépôt
---
- `bikes(learning).ipynb` — Notebook principal : nettoyage, préparation des données, entraînement et évaluation de plusieurs modèles (Lasso, Decision Tree, Random Forest, Gradient Boosting).
- `daily-bike-share.csv` — Jeu de données utilisé (doit être placé au même niveau que le notebook).

Prérequis
---
- Python 3.8+
- Packages Python : pandas, scikit-learn, numpy, matplotlib, jupyter

Installation rapide
---
1. Créer un environnement virtuel :
   - Windows (PowerShell) :
     ```powershell
     python -m venv .venv
     .\.venv\Scripts\Activate.ps1
     ```
2. Installer les dépendances :
   ```powershell
   pip install pandas scikit-learn numpy matplotlib jupyter
   ```

Exécution
---
1. Lancer Jupyter :
   ```powershell
   jupyter notebook
   ```
2. Ouvrir `bikes(learning).ipynb` et exécuter les cellules.

Points importants
---
- Le notebook construit X et y à partir des colonnes suivantes : season, mnth, holiday, weekday, workingday, weathersit, temp, atemp, hum, windspeed.
- Fractionnement train/test : test_size=0.30, random_state=0.
- Évaluation : MSE, RMSE, R2 et graphiques prédictions vs réels.

Remarques sur la contribution
---
Ce projet a été réalisé avec le support de Microsoft Learn. Pour contributions : ouvrir une issue ou proposer une pull request.

