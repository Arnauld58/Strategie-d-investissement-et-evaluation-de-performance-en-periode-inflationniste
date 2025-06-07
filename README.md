# Strategie-d-investissement-et-evaluation-de-performance-en-periode-inflationniste

# 📈 Portfolio Backtesting avec Données Bloomberg (2017–2023)

Ce projet Python permet de tester différentes stratégies d’allocation d’actifs à partir de **données journalières de 30 titres extraites de Bloomberg**, couvrant la période 2017 à 2023.

Il compare notamment les performances **avec et sans matières premières** en période normale (2017-2020) et en période inflationniste (2020-2023), à l’aide de métriques standards (Sharpe, Sortino, volatilité, drawdown, etc.).

---

## 🧰 Contenu du projet

- `Données_essai.xlsx` : données de prix ajustés de 30 titres (actions, obligations, matières premières)
- `backtest.py` : script principal de simulation et d’analyse
- `README.md` : documentation du projet
- `requirements.txt` : liste des dépendances Python

---

## 🔍 Objectif

Explorer et comparer l'efficacité de différentes stratégies d'allocation, dont :

- 📊 **Égalitaire**
- 📈 **Momentum**
- 🔻 **Minimum Volatilité**
- 🏆 **Maximum Sharpe**
- 🧺 **60/30/10**
- 🛡️ **Inflation Hedged** (en fonction de la corrélation avec l’indice des prix)

---

## 📁 Organisation des titres

- **Actions** : AAPL, MSFT, KO, PG, etc.
- **Obligations** : TLT, TIP, IEF, SHY, HYG
- **Matières premières** : GLD, SLV, USO, PDBC, DBA, etc.

---
