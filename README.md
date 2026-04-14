# sales-dashboard-powerbi

 ## <img width="30" height="30" alt="image" src="https://github.com/user-attachments/assets/f3133b1d-2171-43f3-a10f-d6e3fa464a18" /> Objectif


Ce projet consiste à concevoir un tableau de bord interactif permettant d’analyser les performances financières d’une entreprise et de faciliter la prise de décision.

## Problématique

L’analyse vise à répondre aux questions suivantes :

* Quel mois et quelle année ont généré le plus de bénéfices ?
* Quelle région est la plus performante ?
* Quels produits et segments sont les plus rentables ?

## Outils et technologies

* Power BI Desktop
* Excel (jeu de données financier)
* Power Query pour la préparation des données
* DAX pour la modélisation

## Données

Les données utilisées proviennent d’un fichier Excel contenant des informations sur les ventes, les profits, les produits, les segments et les zones géographiques.

## Préparation des données

Plusieurs étapes de transformation ont été réalisées :

* Conversion des types de données (notamment les unités vendues en nombres entiers)
* Nettoyage et formatage des colonnes
* Suppression des données non pertinentes
* Harmonisation des valeurs pour améliorer la lisibilité

## Modélisation

* Création d’une mesure pour calculer le total des unités vendues
* Mise en place d’une table calendrier en DAX
* Création des relations entre les tables

## Visualisations

Le tableau de bord comprend :

* Un graphique montrant l’évolution des bénéfices par mois et par année
* Une carte permettant d’identifier les performances par région
* Un graphique comparant les ventes par produit et segment
* Un filtre temporel pour affiner l’analyse

## Résultats

L’analyse met en évidence plusieurs points importants :

* Le mois de décembre 2014 présente le niveau de bénéfice le plus élevé
* L’Europe est la région la plus performante, notamment la France et l’Allemagne
* Le produit Paseo se démarque en termes de performance
* Les segments les plus rentables sont les petites entreprises et le secteur public

## Conclusion

Ce projet illustre la capacité à transformer des données brutes en informations exploitables grâce à Power BI, en combinant préparation des données, modélisation et visualisation.

## Fichier

* sales_dashboard.pbix
