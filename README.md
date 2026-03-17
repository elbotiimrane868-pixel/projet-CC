# 🏠 Prédiction du Délai de Vente Immobilier — Maroc

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org)
[![Framework](https://img.shields.io/badge/Machine_Learning-Gradient_Boosting-green.svg)](https://scikit-learn.org)

Ce projet utilise le **Machine Learning** et la collecte de données par **Agent IA** pour prédire le "Délai de Vente" des biens immobiliers au Maroc.

---

## 🚀 Vue d'ensemble

Le projet repose sur un pipeline complet, de l'acquisition de données non structurées à la modélisation prédictive.

- **Données collectées :** `12 259` annonces.
- **Transactions analysées :** `3 057` points de données.
- **Score de performance :** $R^{2} = 0.76$ (Meilleur modèle).

## 🛠 Stack Technique

- **Langage :** `Python`
- **Bibliothèques :** `Pandas`, `NumPy`, `Scikit-Learn`, `XGBoost`
- **Automation :** Agent Scraper IA avec gestion des protections anti-bot.

## 📂 Architecture du Projet

1. **Collecte Automatisée** : Pipeline en 4 étapes (Navigation, Extraction, Parsing, Stockage).
2. **Feature Engineering** : Analyse de 19 variables (Surface, Ville, Type de bien, etc.).
3. **Modélisation** : Comparaison d'algorithmes et optimisation du Gradient Boosting.

## 📈 Roadmap (Perspectives)

### Court Terme
- [ ] Intégrer les données notariales officielles.
- [ ] Ajouter des variables géospatiales via l'API **OpenStreetMap**.
- [ ] Implémenter des indicateurs de saisonnalité.

### Moyen Terme
- [ ] Déploiement via une **API REST (FastAPI)**.
- [ ] Création d'un dashboard de pricing dynamique.
- [ ] Extension à la prédiction du prix final de transaction.

## 🎓 Contexte
Projet réalisé à l'**ENCG Settat** (Filière Gestion-Finance) par :
- **Imrane El Boti**
- **Hiba Bounacer**

*Sous la direction de M. Abderrahim Larhlimi (Mars 2026).*

---

> "Transformer la donnée brute en intelligence de marché."
