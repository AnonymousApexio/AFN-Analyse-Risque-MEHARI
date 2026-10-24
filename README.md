# TP MEHARI – Analyse des risques SSI pour Alsace Formation Numérique (AFN)

[![Formation](https://img.shields.io/badge/Formation-BUT_3_Cybersécurité-blue.svg)](#)
[![Année](https://img.shields.io/badge/Année_Universitaire-2026--2027-orange.svg)](#)
[![Méthode](https://img.shields.io/badge/Méthode-MEHARI-red.svg)](#)

## 📋 Description

Ce dépôt contient l’ensemble des livrables réalisés dans le cadre d'une analyse basé sur la méthode **MEHARI**.

L’étude de cas porte sur une PME fictive, **Alsace Formation Numérique (AFN)**, spécialisée dans les formations professionnelles hybrides.  

L’objectif était de mener une analyse de risques structurée : identification des actifs critiques, évaluation des services de sécurité, sélection de scénarios de risque, estimation du risque résiduel et construction d’un plan de traitement proportionné.

Le TP a été réalisé en binôme. Ce README documente l’organisation du rendu et permet de naviguer facilement entre les différents composants de l'analyse.

## 🏢 Contexte de l’étude

- **Organisation** : AFN – 45 salariés, ~1 200 apprenants/an.
- **Services numériques** : site vitrine, plateforme LMS, messagerie collaborative, CRM, stockage cloud, facturation, postes administratifs.
- **Contraintes** : données personnelles et financières sensibles, dépendance forte aux services SaaS, télétravail, budgets limités, incidents récents (hameçonnage, indisponibilité SaaS, erreurs de partage, sauvegardes non testées).
- **Périmètre minimal** : processus d’inscription et gestion administrative, délivrance des formations à distance/hybrides, gestion des données personnelles/contractuelles/financières, messagerie/stockage/LMS/accès distant, postes de travail et sauvegardes.

## 📁 Structure du projet

```
TP1_MEHARI_AFN/
├── .dist/                               # (espace de distribution/build – non utilisé)
├── 00_source/                           # Documents de référence
│   ├── 20220824 Guide-Méhari-Standard-2022-Fr-Ed.2.pdf
│   ├── DB-Standard-2022-Ed.2.1-Fr-11-08-2022.xlsm
│   └── TP_MEHARI_analyse_des_risques_SSI.pdf
├── 01_classeur/                         # Classeur MEHARI complété
│   └── AFN_MEHARI_v04_2026-10-20.xlsm
├── 02_journal/                          # Journal des hypothèses
│   └── Journal_hypotheses_AFN.xlsx
├── 03_dossier/                          # Dossier d’analyse et registre des risques
│   ├── AFN_Registre_risques_et_feuille_de_route.xlsx
│   └── Dossier_analyse_MEHARI_AFN.pdf
└── 04_oral/                             # Support de restitution orale
    └── Restitution_MEHARI_AFN.pptx
```

### Détail des répertoires

- **`00_source/`** : contient le guide MEHARI, la base de connaissances MEHARI (fichier Excel macro-activé) et l’énoncé du TP.
- **`01_classeur/`** : classeur MEHARI complété (feuilles T1, T2, Expo, questionnaires, Services, Scénarios, Plans_action, etc.).  
- **`02_journal/`** : journal des hypothèses (H-01, H-02, …) avec impact sur l’analyse et validation requise.
- **`03_dossier/`** :  
  - `AFN_Registre_risques_et_feuille_de_route.xlsx` : registre des risques prioritaires et plan de traitement (actions, responsables, échéances, indicateurs).  
  - `Dossier_analyse_MEHARI_AFN.pdf` : dossier d’analyse complet structuré selon les consignes (résumé exécutif, contexte, méthode, actifs, diagnostic, registre, plan, conclusion, annexes).
- **`04_oral/`** : support de présentation pour la restitution orale.

## 🎯 Livrables attendus (rappel)

| Livrable | Fichier(s) |
|----------|------------|
| 1. Classeur MEHARI | `01_classeur/AFN_MEHARI_v04_2026-10-20.xlsm` |
| 2. Dossier d’analyse | `03_dossier/Dossier_analyse_MEHARI_AFN.pdf` |
| 3. Registre des risques | `03_dossier/AFN_Registre_risques_et_feuille_de_route.xlsx` (onglet Registre prioritaire) |
| 4. Feuille de route | `03_dossier/AFN_Registre_risques_et_feuille_de_route.xlsx` (onglet Feuille de route) |
| 5. Restitution orale | `04_oral/Restitution_MEHARI_AFN.pptx` |

## 🔍 Hypothèses et limites

- Toutes les informations absentes du cas ont été formulées comme **hypothèses explicites** et consignées dans le journal (`02_journal/Journal_hypotheses_AFN.xlsx`).
- Les notations de sécurité suivent une échelle **0 à 4** (0 = inexistant, 4 = mature et documenté).
- Les scénarios de risque retenus (10–20) sont reliés à un actif, un événement et une conséquence métier ; les scénarios hors périmètre ont été exclus.
- Les coûts/charges sont estimés de manière simple (faible / moyen / élevé).
- L’analyse ne prétend pas à l’exhaustivité mais vise la **cohérence**, la **justification** et l’**aide à la décision**.

## ⚙️ Prérequis pour consulter les fichiers

- **Excel** (ou LibreOffice Calc) avec prise en charge des macros pour ouvrir le classeur MEHARI (`.xlsm`).
- **Lecteur PDF** pour le dossier et les documents sources.
- **PowerPoint** (ou LibreOffice Impress) pour la présentation orale.
- Une connaissance minimale de la méthode MEHARI est un plus pour interpréter les feuilles du classeur.

## 📚 Références

- **MEHARI** - Guide standard 2022 (Éd. 2) et base de connaissances associée.
- Énoncé du TP : `00_source/TP_MEHARI_analyse_des_risques_SSI.pdf`.