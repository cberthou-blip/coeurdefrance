# Corpus Coeur de France

Corpus de donnees structurees extrait du dossier Coeur de France.

Ce dossier ne contient aucune reference a l'ancien projet personnel de simulation politique.

## Fichiers

- `coeur_de_france_corpus.json` : corpus canonique complet.
- `mesures.csv` : table exploitable des mesures programmatiques.
- `budget.csv` : table exploitable du chiffrage budgetaire.
- `arbitrages.csv` : points a trancher avant publication ou consolidation.

## Usages prevus

- alimenter un site vitrine ;
- construire une base de donnees politique ;
- produire des fiches par domaine ;
- generer des notes de synthese ;
- suivre les arbitrages et incoherences a corriger.

## Conventions

- Les montants budgetaires sont exprimes en milliards d'euros par an.
- Les mesures sont classees par domaine et par ministere/portefeuille possible.
- Le champ `statut` distingue les elements consolides, a auditer, ou a arbitrer.
- Les champs `risques` et `points_attention` signalent les fragilites politiques, juridiques, budgetaires ou de communication.
