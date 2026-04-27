# 📊 Déploiement d'un Tableau de Bord Interactif Power BI

<img width="1205" height="676" alt="Capture d’écran-POWER BI 01" src="https://github.com/user-attachments/assets/c342e7c5-f029-4c9b-b315-527619d50c03" />


## 🏢 Contexte du Projet
Ce projet s'inscrit dans une démarche de modernisation de la prise de décision au sein de l'entreprise. L'objectif est de remplacer les processus manuels et les fichiers Excel statiques par une solution de **Business Intelligence (BI) dynamique**, centralisée et automatisée.

## 🎯 Objectifs Majeurs
* **Centralisation** : Structurer et unifier les données provenant de plusieurs sources opérationnelles.
* **Analyse Segmentée** : Offrir une exploration granulaire par clients, produits, fournisseurs et localisation géographique.
* **Aide à la Décision** : Fournir des indicateurs clés (KPI) dynamiques pour un pilotage efficace de l'activité.

## 🏗️ Architecture & Modélisation
Le modèle de données a été optimisé pour garantir performance et fiabilité :

* **Schéma en Étoile (Star Schema)** : Organisation structurée avec une table de faits centrale connectée à ses tables de dimensions.
* **Table de Dates** : Création d'une table calendaire personnalisée permettant des analyses temporelles avancées (YTD, QTD, mensualisation).
* **Nettoyage Power Query** : Transformation des données, correction des types et suppression des champs inutiles pour maximiser la réactivité du modèle.

---

## 📈 Visualisations & Fonctionnalités
Le rapport est conçu pour une navigation intuitive et un storytelling efficace :

* **Page d'Accueil** : Interface graphique harmonisée avec navigation par boutons.
* **KPI Dynamiques** : Cartes visuelles affichant les totaux, volumes et délais de livraison en temps réel.
* **Analyse Top 5** : Histogrammes dynamiques présentant les meilleurs produits et fournisseurs avec calculs cumulés.
* **Évolution Temporelle** : Courbes de tendances pour identifier les cycles et variations de l'activité.
* **Interactivité Avancée** : Utilisation de **signets (bookmarks)** pour changer de vue, de **filtres croisés** et d'**infobulles (tooltips)** détaillées au survol des données.

## 🧪 Intelligence de Données (DAX)
Le projet exploite la puissance du langage **DAX** pour extraire des insights métier critiques :
* Mesures de performance par segment de marché.
* Algorithmes de détection de tendances et d'anomalies de ventes.
* Analyse de corrélation entre les délais de livraison et la performance globale.

## 💡 Insights Clés & Recommandations
* **Performance Produit** : Identification des familles dominantes (ex: *Fabaceae*) et des références à forte rentabilité.
* **Optimisation Logistique** : Analyse des points de friction dans les délais pour améliorer la satisfaction client.
* **Opportunités Marché** : Détection des zones géographiques présentant un fort potentiel de croissance.

## 📁 Livrables
* **Fichier Power BI** : Rapport final (`.pbix`).
* **Documentation** : Dictionnaire des données et guide des mesures DAX.

---
*Projet réalisé dans une optique de transformation digitale et d'optimisation de la performance.*
