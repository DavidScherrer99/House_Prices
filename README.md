# House_Prices

*Setup:*
```sh
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

1. Analyse de données pour le choix des variables

2. Faire une baseline avec régession linéaire

3. Choix de la transfo en logarithme pour tenir compte des prix relatifs (pour l'optimisation des modèles)

4. Pipeline de base
    - transfo année en age de la maison

5. Tester plusieurs modèles et faire leur pipeline
    - Avec cross validation et optuna
