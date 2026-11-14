# 📊 Analyses & Benchmarks IA

Ce dépôt regroupe mes études, benchmarks et expérimentations techniques autour des modèles de langage (LLM) et de l'intelligence artificielle en local.

## 📁 Études disponibles

### 🏷️ [6 LLM locaux, 141 textes à classer : lesquels sont crédibles ?](./LLM-locaux-2026-classification/)
* **Date :** Novembre 2026
* **Sujet :** Benchmark de 6 LLM locaux face à des tâches variées de classification de textes en français.
* **Périmètre :** 141 propositions réparties sur 8 tâches (sentiment, thème, intention, avis multi-aspects et multi-thèmes) et 4 niveaux de difficulté, testées 5 fois de suite à température 0 avec permutation des modalités (soit **4 230 réponses analysées**).
* **Axes d'analyse :** Score global (exact et Jaccard), précision et rappel sur les choix multiples, stabilité sur 5 passages, temps de réponse (échelle logarithmique) et grille de crédibilité par tâche.

### 🌍 [Et en anglais ? Les mêmes 9 LLM, les mêmes 30 questions](./LLM-locaux-2026-anglais/)
* **Date :** Novembre 2026
* **Sujet :** Comparaison statistique des performances des 9 petits LLM locaux entre le français et l'anglais.
* **Périmètre :** Les mêmes 30 questions traduites en anglais, testées 5 fois de suite à température 0 (soit **2 700 réponses comparées** au total : 1 350 par langue).
* **Axes d'analyse :** Écarts de justesse question par question (tests de permutation appariés et correction de Holm), asymétrie de bascule vers l'anglais, comparaison des temps de réponse et évolution domaine par domaine.

### 🤖 [9 petits LLM, 30 questions : lesquels tiennent la route ?](./LLM-locaux-2026/)
* **Date :** Novembre 2026
* **Sujet :** Benchmark de 9 LLM locaux de petite taille (moins de 8B paramètres) en français. 
* **Périmètre :** 30 questions réparties sur 6 domaines, testées 5 fois de suite à température 0 (soit **1 350 réponses analysées**).
* **Axes d'analyse :** Justesse globale, constance et taux de réponses impeccables, vitesse et régularité (boîtes à moustaches), performances domaine par domaine et questions pièges.

---

## 🚀 Accès en ligne (GitHub Pages)

Vous pouvez consulter l'ensemble de ces analyses sous forme de pages web interactives directement ici :
👉 [https://eric2mangel.github.io/Analyses/](https://eric2mangel.github.io/Analyses/)

---
*Projet hébergé via GitHub Pages.*