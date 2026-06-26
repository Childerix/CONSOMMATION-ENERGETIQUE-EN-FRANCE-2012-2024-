# CONSOMMATION-ENERGETIQUE-EN-FRANCE-DE-2012-2024-

Ce projet vise à analyser les consommations énergétiques des grandes régions urbaines françaises sur la période 2015-2024. L'objectif est de comprendre la structure énergétique de ces territoires et d'identifier les tendances sectorielles.

## Données utilisées

Le dataset contient des informations sur les consommations énergétiques par région, secteur et année. Les secteurs couverts sont :

- Agriculture
- Industrie
- Residentiel
- Tertiaire
- Autres

Les consommations sont disponibles en MWh pour différentes énergies : totale, electricite et gaz.

## Principales etapes de l'analyse

1. Nettoyage et filtrage des donnees
2. Regroupement par region et calcul des sommes par secteur
3. Calcul des parts sectorielles dans la consommation totale
4. Identification des disparites regionales
5. Analyse des evolutions temporelles

## Principaux resultats

- Les grandes regions urbaines reposent principalement sur trois secteurs : le residentiel, l'industrie et le tertiaire.
- Des écarts ont été constatés entre la somme des consommations sectorielles et le total affiche dans le dataset, suggérant des ajustements statistiques ou des pertes reseau.
- Certaines regions presentent des donnees manquantes ou nulles pour certains secteurs sur certaines annees, probablement dues a des limites de collecte.
- L'agriculture, bien que vitale, pese peu dans les bilans energetiques compares a l'industrie et au residentiel.


## Langage utilisé: R
