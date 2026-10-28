# 📐 Fiche de référence statistique — UX Research

> **EN:** An interactive statistical reference sheet for UX research. User tests & experimental studies: which test to use, why, and under what conditions. Single self-contained HTML file, zero dependencies.

**🌐 Voir la fiche en ligne : [antoineau.github.io/UX-Statistical-reference-sheet](https://antoineauchet.github.io/UX-Statistical-reference-sheet/)**

[![Licence: MIT](https://img.shields.io/badge/Licence-MIT-0d6e5e.svg)](./LICENSE)
[![Format](https://img.shields.io/badge/format-HTML5%20autonome-2E6F8E.svg)](./fiche_stats_ux.html)

---

## 📖 À propos

Cette fiche de référence interactive accompagne la conduite d'études UX et de protocoles expérimentaux en psychologie cognitive. Elle répond aux trois questions que se pose toute équipe recherche à la fin d'une campagne de tests :

1. **Quel test choisir** selon la nature des données, le nombre de groupes et le plan expérimental ?
2. **Sous quelles conditions** un test est-il valable (normalité, homoscédasticité, effectifs minimum) ?
3. **Comment interpréter** les résultats au-delà de la p-value : tailles d'effet, significativité pratique, zones grises ?

La fiche est née d'un besoin concret d'analyse de données utilisateurs (évaluation du player OP3FT, Vivatech 2026) et est publiée ici comme outil de travail réutilisable.

## ✨ Contenu de la fiche

**20 fiches tests** organisées en 5 catégories :

| # | Catégorie | Tests couverts |
|---|-----------|----------------|
| 1 | Tests de présupposés | Shapiro-Wilk, Levene, Q-Q plot |
| 2 | Statistiques descriptives | Moyenne & médiane, écart-type & intervalles de confiance |
| 3 | Comparaison de groupes | t-test (indépendant / apparié), ANOVA (one-way / mesures répétées), Mann-Whitney U, Wilcoxon, Kruskal-Wallis, Chi², Tukey HSD |
| 4 | Association & corrélation | Pearson, Spearman, régression linéaire |
| 5 | Fiabilité & cohérence interne | Alpha de Cronbach, ICC, Kappa de Cohen |

Pour chaque test : hypothèses H₀ / H₁, conditions d'application, formule, effectif minimal recommandé, **taille d'effet avec jauge visuelle** (d de Cohen, η², r, V de Cramér, α, ICC, κ), **exemple chiffré appliqué à l'UX** (SUS, UMUX, NASA-TLX, temps de tâche...), extrait Python (`scipy`, `statsmodels`, `pingouin`) et pistes d'interprétation (significatif / non significatif / zone grise).

Fonctionnalités :

- 🌳 **Arbre de décision interactif** « Quel test choisir ? », avec navigation directe vers les fiches
- 🏷️ Filtres par catégorie et par type (paramétrique / non paramétrique)
- 🌙 Thème clair / sombre, design responsive
- 📦 **Fichier HTML autonome** : aucune dépendance, aucun tracker, fonctionne hors ligne

## 🚀 Utilisation

- **En ligne** : ouvrez [antoineau.github.io/UX-Statistical-reference-sheet](https://antoineau.github.io/UX-Statistical-reference-sheet/)
- **Hors ligne** : téléchargez `fiche_stats_ux.html` et ouvrez-le dans un navigateur. Filtres, arbre de décision et thème fonctionnent en local.

## 🎯 Public & cas d'usage

UX researchers, ergonomes, ingénieurs pédagogiques, étudiants en master ou doctorat, partout où il faut :

- analyser des résultats de tests utilisateurs (A/B testing, mesures répétées, comparaisons inter-groupes) ;
- valider la fiabilité d'instruments de mesure (SUS, UMUX, NASA-TLX) avant d'interpréter les scores ;
- justifier le choix d'un test statistique dans un protocole ou une publication.

## 📁 Structure du dépôt

```text
fiche_stats_ux.html   → la fiche complète (HTML autonome)
index.html             → redirection vers la fiche (point d'entrée GitHub Pages)
.nojekyll              → sert les fichiers tels quels, sans build Jekyll
LICENSE                → MIT
```

## 📚 Références

Brooke (1996) · Bangor et al. (2009) · Sauro & Lewis (2012) · Finstad (2010) · Cohen (1988) · Field (2018) · Koo & Li (2016)

## 📌 Citer ce projet

```bibtex
@misc{auchet2026fiche,
  author = {Auchet, Antoine},
  title  = {Fiche de référence statistique — UX Research},
  year   = {2026},
  url    = {https://github.com/AntoineAu/UX-Statistical-reference-sheet},
  note   = {Fiche interactive, licence MIT}
}
```

## ✍️ Auteur

**Antoine Auchet** — UX Researcher · Ingénieur en ergonomie cognitive & IHM

- 💼 [LinkedIn](https://www.linkedin.com/in/antoine-auchet/)
- 🐙 [GitHub — @AntoineAu](https://github.com/AntoineAu)
- 🔧 Freelance UX Research — [Malt](https://www.malt.fr/profile/antoineauchet)

## 📄 Licence

[MIT](./LICENSE) © 2026 Antoine Auchet. Librement réutilisable avec mention de l'auteur.
