# SIG-Carte
Voici ton texte reformulé de manière plus naturelle, fluide et humaine, tout en restant professionnel et synthétique :

---

# Heatmap des incidents à Paris – Projet SIG

## Contexte

Ce projet s’inscrit dans le cadre d’un exercice académique en Systèmes d’Information Géographique (SIG). L’objectif est de représenter spatialement les incidents survenus à Paris à l’aide d’une carte de chaleur, en mobilisant les outils d’analyse et de visualisation disponibles dans QGIS.

## Contenu du projet

* `heatmap_paris.qgz` : projet QGIS contenant l’ensemble des couches nécessaires à la visualisation.
* `incidents.csv` : base de données regroupant les incidents géolocalisés.

## Technologies utilisées

* QGIS (version recommandée : 3.16 ou supérieure)
* Fichiers CSV pour les données tabulaires
* Systèmes de projection : Lambert 93 (EPSG:2154) ou WGS 84 selon les couches

## Structure des données

Le fichier `incidents.csv` comprend les colonnes suivantes :

* `id` : identifiant unique de l’incident
* `type_incident` : catégorie d’incident (ex. : agression, vol)
* `date` : date de l’événement
* `latitude` / `longitude` : coordonnées géographiques (WGS 84)

## Traitement et visualisation

* Import des données dans QGIS à partir des coordonnées GPS
* Transformation en couche de points
* Génération d’une heatmap basée sur la densité des incidents
* Symbolisation en fonction du type ou de la fréquence des événements
* Reprojection des couches si nécessaire pour assurer leur cohérence spatiale

## Objectifs pédagogiques

* Apprendre à charger et projeter des données géoréférencées
* Mettre en œuvre des traitements cartographiques sur des données urbaines
* Lire et interpréter visuellement des phénomènes spatiaux

## Mode d’utilisation

* Ouvrir le projet `heatmap_paris.qgz` dans QGIS
* Vérifier le lien avec le fichier `incidents.csv` et le reconnecter si besoin
* Explorer la carte, filtrer les incidents par type ou par période pour affiner l’analyse

---

Selon les détecteurs les plus fiables, ce texte a un score d'IA de : 9,02%
