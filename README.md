# 📊 Analyse des compétences Data dans le marché du travail 2025

## 🎯 Objectif

Ce projet a été réalisé dans le but de mieux comprendre quelles compétences sont aujourd'hui les plus demandées dans les métiers de la Data en 2025. Face à une multitude d'offres d'emploi aux exigences variées, j'avais du mal à identifier clairement les compétences prioritaires, celles que je possédais déjà et celles à renforcer. Ce projet m'a permis de structurer cette information et de mieux positionner mon profil dans un marché en constante évolution.

## 🔍 Description du projet

Ce projet repose sur les étapes suivantes :

1. Scraping des annonces Data sur [Welcome to the Jungle](https://www.welcometothejungle.com/fr).
2. Extraction des compétences mentionnées dans les descriptions de poste.
3. Nettoyage et normalisation des compétences.
4. Comptage des occurrences pour évaluer les plus demandées.
5. Visualisation sous forme de WordCloud.

## 🛠️ Technologies utilisées

- Jupyter Notebook : environnement de développement interactif.
- Python : langage principal pour le scripting et l’analyse.
- Selenium : scraping dynamique des annonces d’emploi sur Welcome to the Jungle.
- Matplotlib & WordCloud : visualisation graphique des compétences extraites.

## 📁 Structure du projet

├── scrap_wttj_to_get_competence.ipynb  # Code principal : scraping, extraction et visualisation
├── data/
│   └── job_links.xlsx                       # Liens des annonces collectées
├── README.md                           # Description du projet
└── img/
    └── wordcloud.png                   # Image du nuage de mots généré

## 📸 Résultat

## 🚧 Challenges rencontrés

💥 Instabilités avec Selenium : certaines sessions se fermaient automatiquement, provoquant des erreurs InvalidSessionIdException. Résolu en lançant le scraping lien par lien.
⏱️ Temps d’exécution : l’optimisation via la parallélisation n'a pas été retenue dans la version finale pour assurer plus de stabilité.
🧹 Nettoyage des compétences : Une normalisation manuelle a été partiellement effectuée.

## 🚀 Prochaines étapes

- Étendre le scraping à d'autres plateformes (LinkedIn, HelloWork, Indeed…)
- Catégoriser les compétences : techniques, outils, soft skills…
- Comparer les tendances par type de poste (Data Analyst, Data Engineer, etc.)
- L’optimisation via la parallélisation n'a pas été retenue dans cette version. Inclure ThreadPoolExecutor pour assurer plus de stabilité et un temps d'exécution optimisé.
- Encore beaucoup de formulations similaires ou redondantes (ex : travail d'équipe vs collaboration et travail d'équipe). NLP à approfondir.
- Logging au lieu de print() afin de suivre l'exécution du programme.

## 🙋‍♀️ À propos

Ce projet a été réalisé en autonomie dans une optique de veille technologique, d’apprentissage et de portfolio.
Il m’a permis de croiser mes compétences avec celles demandées sur le marché, et de mieux orienter mes priorités de montée en compétence.

---

## 💬 Contact

Si vous avez des questions ou souhaitez échanger sur ce projet :
📧 sarachaieb@outlook.fr
 Linkedin : Sara C.