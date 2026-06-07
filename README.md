# CarPulse - Prévision Commerciale Automobile

## Description du projet

Ce projet s'inscrit dans le cadre d'un système de Business Intelligence (BI) visant à analyser et prévoir les tendances commerciales d'une entreprise automobile fictive nommée **CarPulse**.

Les données sont stockées au format XML et couvrent la période **2016 à 2025**.

L'objectif est d'utiliser ces données historiques afin de :

* analyser l'évolution des ventes ;
* calculer des indicateurs statistiques ;
* produire des prévisions commerciales ;
* générer un rapport HTML automatisé.

---

## Structure des données

Le fichier `ventes.xml` contient :

* 10 années d'historique (2016–2025) ;
* 12 mois par année ;
* le nombre total de véhicules vendus ;
* la répartition par motorisation ;
* le chiffre d'affaires mensuel.

### Exemple

```xml
<mois nom="Janvier"
      vehicules="26"
      thermique="10"
      hybride="8"
      electrique="8"
      montant="787500"/>
```

---

## Motorisations

Les véhicules sont répartis en trois catégories :

* Thermique
* Hybride
* Électrique

Le dataset simule une transition progressive du marché automobile vers les véhicules électrifiés.

---

## Fichiers du projet

| Fichier       | Description                       |
| ------------- | --------------------------------- |
| ventes.xml    | Données historiques des ventes    |
| ventes.xsd    | Validation du fichier XML         |
| prediction.py | Analyse statistique et prévisions |
| rapport.xsl   | Transformation XML vers HTML      |
| rapport.html  | Rapport généré                    |

---

## Scénario métier

CarPulse est une entreprise fictive spécialisée dans la vente de véhicules neufs et d'occasion.

Le jeu de données a été conçu pour reproduire :

* une croissance régulière des ventes ;
* une baisse d'activité en 2020 ;
* une reprise progressive à partir de 2021 ;
* une augmentation des ventes de véhicules hybrides et électriques.

---

## Technologies utilisées

* XML
* XSD
* Python
* XSLT
* HTML

---

## Équipe du projet

| Membre          | Responsabilité                           |
| --------------- | ---------------------------------------- |
| Largou Ayman       | Conception et création du fichier XML    |
| Saadani Hassani Ghizlane | Validation des données avec XSD          |
| Amiry Aya | Analyse statistique et prévisions Python |
|Rhahla Mohammed-Ihab| Génération du rapport HTML via XSLT      |

---

## Répartition des tâches

### XML

Création du jeu de données historique de l'entreprise CarPulse couvrant la période 2016–2025.

### XSD

Définition du schéma XML et validation de la cohérence des données.

### Python

Calcul des indicateurs statistiques, moyenne mobile, tendance linéaire et prévisions.

### XSLT / HTML

Transformation des données XML en rapport HTML interactif avec tableaux et graphiques.

### Documentation

Rédaction du rapport technique, tests et validation finale du projet.

