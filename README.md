# Analyse de l’Espérance de Vie en Afrique Subsaharienne

## Description

Ce projet explore les déterminants de l'espérance de vie en Afrique subsaharienne, en analysant les facteurs socio-économiques et sanitaires influençant cet indicateur. L'objectif est de comprendre comment des éléments tels que l'éducation, le revenu, l'accès aux soins de santé et l'environnement socio-économique affectent la longévité dans cette région.

## Objectif

- Étudier les déterminants de l'espérance de vie en Afrique subsaharienne.
- Analyser les facteurs socio-économiques et sanitaires influençant l'espérance de vie.
- Utiliser des méthodes de modélisation statistique et d'analyse de données de panel pour identifier les variables les plus influentes sur l’espérance de vie.
- Formuler des recommandations pour améliorer les politiques publiques de santé et de développement.

## Méthodologie

1. **Collecte des données** : Les données utilisées dans ce projet proviennent de Kaggle : [Life Expectancy and Socio-economic World Bank](https://www.kaggle.com/datasets/mjshri23/life-expectancy-and-socio-economic-world-bank).
   
### Région étudiée
Ce projet se concentre sur l'Afrique subsaharienne, avec des données filtrées sur plusieurs années et pays.
### Observations
Les données sont filtrées pour inclure uniquement les pays d'Afrique subsaharienne, sur une période de plusieurs années.

2. **Modélisation statistique** : Une analyse des données de panel sera effectuée pour identifier les variables ayant un impact significatif sur l'espérance de vie.
3. **Analyse des résultats** : Identification des facteurs les plus influents et formulation de recommandations basées sur les résultats.

## Résultats Attendus

Les résultats devraient permettre d’identifier les principaux facteurs influençant l’espérance de vie en Afrique subsaharienne et de proposer des recommandations pour améliorer les politiques publiques de santé et de développement dans la région.

## Prérequis

- R (version 4.x ou supérieure)
- Packages R nécessaires :
  - `plm`
  - `ggplot2`
  - `dplyr`
  - `lmtest`
  - `car`
  - `readr`
  - `ggplot`
  - `corrplot`
  - `FactoMineR`
  - `tseries`
  - `sandwich`

## Installation

Clonez ce dépôt et installez les dépendances en exécutant le code suivant :

```bash
git@github.com:Naofal03/Analyse-de-l-Esperance-de-Vie-en-Afrique-Subsaharienne.git```
```
```R
install.packages(c("plm", "ggplot2", "dplyr", "lmtest", "car", "readr", "ggplot", "corrplot", "FactoMineR", "tseries", "sandwich" ))
```

## Comment Exécuter
1. Clonez le dépôt.
2. Exécutez le fichier sub_saharan_africa_esperance.rmd dans RStudio pour générer les résultats.



