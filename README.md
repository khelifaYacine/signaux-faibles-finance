# 🔎 Détection de Signaux Faibles Financiers  
### Analyse des données BCE‑INPI (Projet Signaux Faibles – Data.gouv)

## 📌 Contexte du projet
Ce projet a pour objectif d’identifier les **signaux faibles financiers** des entreprises françaises à partir des données officielles BCE‑INPI, utilisées par l’État dans le cadre du programme **Signaux Faibles**.

Les données proviennent de :  
➡️ https://www.data.gouv.fr/fr/datasets/ratios-financiers-bce-inpi/  
(Mise à jour : février 2026)

Elles contiennent :
- les bilans comptables (liasse fiscale 2033 / 2050)
- les valeurs brutes des postes financiers
- les ratios calculés par l’État
- un identifiant unique (SIREN)
- la date de clôture de chaque exercice

Ce projet reproduit une démarche réelle d’analyse financière et de détection précoce des risques.

---

## 🎯 Objectifs
- Charger et explorer un fichier **.parquet** volumineux  
- Extraire les champs financiers pertinents  
- Calculer les **ratios financiers clés**  
- Détecter les **signaux faibles** (variations anormales, risques)  
- Construire un **score de risque** simple  
- Préparer un dataset propre pour un futur dashboard Power BI  

---

## 🧠 Compétences démontrées
- Manipulation de données volumineuses (format parquet)
- Analyse financière (solvabilité, liquidité, rentabilité…)
- Détection d’anomalies et signaux faibles
- Python (Pandas, NumPy, Matplotlib/Seaborn)
- Structuration d’un projet Data Analyst
- Préparation de données pour la visualisation (Power BI)

---

## 📂 Structure du projet

