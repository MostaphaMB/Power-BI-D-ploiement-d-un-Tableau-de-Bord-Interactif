📊 Projet : Déploiement d'un Tableau de Bord Interactif Power BI

🏢 Contexte du Projet:
Ce projet s'inscrit dans une démarche de modernisation de la prise de décision au sein d'une entreprise. L'objectif est de remplacer des fichiers Excel statiques et manuels par une solution de Business Intelligence dynamique et centralisée.


🎯 Objectifs Majeurs:

Centralisation : Structurer les données provenant de plusieurs sources opérationnelles.

Analyse Segmentée : Permettre une exploration par clients, produits, fournisseurs et localisation.

Aide à la Décision : Fournir des KPI dynamiques et des visuels interactifs pour un suivi efficace.


🏗️ Architecture & Modélisation:

Le modèle de données a été conçu pour garantir performance et fiabilité :

Schéma en Étoile : Organisation optimisée avec une table de faits centrale et des tables de dimensions.

Table de Dates : Création d'une table calendaire personnalisée pour des analyses temporelles précises (année, mois, trimestre).

Nettoyage (Power Query) : Correction des types de données et masquage des champs inutiles pour alléger le modèle.


📈 Visualisations & Fonctionnalités:

Le rapport est structuré en plusieurs sections interactives :

Page d'Accueil : Navigation intuitive via des boutons et une interface graphique harmonisée.

KPI Dynamiques : Cartes affichant les totaux, volumes et délais de livraison.

Analyse Top 5 : Histogramme dynamique affichant les 5 meilleurs produits/fournisseurs avec calcul cumulé en sous-titre.

Évolution Temporelle : Courbes de tendance pour identifier les variations de l'activité.

Interactivité Avancée : Utilisation de signets (bookmarks) pour le storytelling, de filtres croisés et d'infobulles (tooltips) détaillées.


🧪 Intelligence de Données (DAX):

Le projet exploite des mesures DAX (Data Analysis Expressions) pour répondre aux questions métier:

Calculs de performance par segment.

Détection des tendances et anomalies de ventes.

Analyse de l'impact des délais de livraison sur la performance globale.


💡 Insights Clés & Recommandations:

Performance Produit : Identification des familles dominantes (ex: Fabaceae) et des produits "stars".

Optimisation Logistique : Analyse des délais moyens pour améliorer la satisfaction client.

Opportunités Marché : Détection des régions à fort potentiel de croissance.
