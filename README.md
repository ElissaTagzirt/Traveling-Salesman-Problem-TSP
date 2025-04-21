# 🧭 Traveling-Salesman-Problem (TSP) - Approches et Implémentations

Ce projet regroupe cinq approches progressives pour résoudre le **problème du voyageur de commerce (TSP)**, un problème classique d'optimisation combinatoire.

## 📂 Organisation du projet

| Dossier | Description |
|--------|-------------|
| `TP1_Branch_and_Bound` | 🔍 Résolution exacte via l’algorithme **Branch and Bound**. Adapté aux petits graphes. |
| `TP2_heuristique` | ⚙️ Implémentation d’**heuristiques de construction** (NN, DNN, NLN, DNLN, Christofides). |
| `TP3_RL` | 🔄 **Recherche locale** et heuristiques d'amélioration (2-opt). Optimisation sur solution initiale. |
| `TP4_AS` | 🐜 **Ant Colony Optimization (ACO)**, une métaheuristique bio-inspirée utilisant des traces de phéromones. |
| `TP5_Hyper-Heuristiques` | 🤖 **Hyper-heuristiques hybrides**, combinant ACO, machine learning et TS-ILS pour un choix dynamique des heuristiques. |

---

## 🧠 Schéma des Méthodes Approximatives

Voici l’architecture globale des méthodes testées dans ce projet :

![Méthodes Approximatives pour le TSP](./article/5c325859-5f94-4fb3-804d-d658cfabdadb.png)

Cette revue couvre :

- **Heuristiques simples** (construction et amélioration)
- **Métaheuristiques** (Simulated Annealing, Tabu Search, ACO, GA)
- **Hyper-heuristiques** : niveau supérieur pour combiner intelligemment les heuristiques existantes.

---

## 🔍 Objectif

Explorer les performances de différentes approches pour résoudre le TSP :

- Comparaison des résultats (coût, temps)
- Évaluation sur des benchmarks (PR76, EIL101, GIL262)
- Analyse des compromis qualité/temps d’exécution

---

## ✅ Résultats principaux

- **Heuristiques** : simples et rapides, mais souvent sous-optimales.
- **Métaheuristiques** : meilleures solutions mais plus coûteuses en temps.
- **Hyper-heuristiques** : flexibles, adaptatives et très efficaces sur des cas variés.

---

## 📊 Benchmarks utilisés

- **PR76** (76 villes)
- **EIL101** (101 villes)
- **GIL262** (262 villes)

Source : [TSPLIB](http://comopt.ifi.uni-heidelberg.de/software/TSPLIB95/)

