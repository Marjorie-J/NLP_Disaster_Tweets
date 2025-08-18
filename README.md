# NLP_Disaster_Tweets

Concours de prédiction Kaggle : https://www.kaggle.com/competitions/nlp-getting-started/overview


## Description du concours

Twitter est devenu un canal de communication important en cas d'urgence.
L'omniprésence des smartphones permet d'annoncer en temps réel une situation d'urgence. De ce fait, de plus en plus d'organismes (organisations de secours et agences de presse, par exemple) s'intéressent à la surveillance programmatique de Twitter.

Mais il n'est pas toujours évident de savoir si les paroles d'une personne annoncent réellement une catastrophe. 

Dans ce concours, vous devrez créer un modèle d'apprentissage automatique capable de prédire quels tweets concernent des catastrophes réelles et lesquels n'en concernent pas. 
Vous aurez accès à un ensemble de données de 10 000 tweets classés manuellement. 


## Évaluation

Les soumissions sont évaluées à l'aide de F1 entre les réponses prévues et attendues.


## Dossier de soumission

Pour chaque identifiant de l'ensemble de test, vous devez prédire 1 si le tweet décrit une catastrophe réelle, et 0 dans le cas contraire.


## Résultats de soumission

submissions_01.csv - Score: 0.82837
submissions_02.csv - Score: 0.83573


## Installation

1. Cloner le repository

```bash
git clone https://github.com/Marjorie-J/NLP_Disaster_Tweets.git
cd NLP_Disaster_Tweets
```

2. Créer un environnement

```bash
python -m venv nlp_dt_env
source nlp_dt_env/bin/activate
```

3. Installer les dépendances

```bash
pip install -r requirements.txt
```


## Structure du Repository

```
.
└── NLP_Disaster_Tweets/
    ├── datas/
    ├── src/
    ├── .gitignore
    ├── README.md
    └── requirements.txt