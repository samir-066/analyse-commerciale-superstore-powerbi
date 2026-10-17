# Analyse des performances commerciales – Power BI

##### Projet personnel | Business Intelligence \& Analyse de données

###### Technologies : Power BI, Power Query, DAX, et Modélisation de données



#### Présentation du projet

Ce projet consiste à concevoir un tableau de bord décisionnel permettant d’analyser les performances commerciales d’une entreprise fictive à partir d’un jeu de données public : Sample Superstore.

L’objectif est de transformer des données de ventes en indicateurs de performance afin d’identifier les leviers de rentabilité, les produits déficitaires, et les segments de clientèle les plus performants.

Le rapport a été développé avec Power BI Desktop et comprend trois pages interactives.





### 1\. Objectifs métier

Le tableau de bord cherche à répondre aux questions suivantes : 

* Comment évoluent le chiffre d’affaires et la rentabilité de l’entreprise ?
* Quelles catégories de produits génèrent le plus de bénéfices ?
* Quels produits présentent des pertes cumulées ?
* Quelle relation observe-t-on entre les remises commerciales et les marges ?
* Quels segments de clientèle contribuent le plus aux résultats ?







### 2\. Présentation du dashboard

##### Page 1 – Vue d’ensemble 

Cette page présente les principaux indicateurs commerciaux :

* Chiffre d'affaires et bénéfice total
* Marge bénéficiaire
* Nombre de commandes
* Croissance annuelle du chiffre d'affaires
* Évolution mensuelle des ventes
* Performances par catégorie et région



##### Page 2 – Rentabilité des produits

Cette page permet d'identifier les produits et sous-catégories qui contribuent positivement ou négativement au résultat.

Elle comprend :

* Le nombre et la proportion de références déficitaires
* Le bénéfice par sous-catégorie
* La marge bénéficiaire selon les tranches de remise
* Le classement des produits les plus déficitaires



##### Page 3 – Analyse des clients

Cette page est consacrée à la segmentation commerciale :

* Nombre de clients distincts
* Chiffre d'affaires moyen par client
* Chiffre d'affaires par segment
* Marge par segment
* Classement des clients les plus rentables







### 3\. Principaux résultats

Résultats observés sur l’ensemble de la période étudiée, sans filtre supplémentaire

&#x09;

|Indicateur|Résultat|
|-|-|
|Chiffre d’affaires|2.30 M|
|Bénéfice total|286.40 K|
|Marge bénéficiaire|12.47%|
|Clients distincts|793|
|Références déficitaires|299 (16,06%)|



##### Analyse 1 – Rentabilité des Tables  

La sous-catégorie **Tables** présente une perte cumulée de 17.73K, alors que les transactions sans remise affichent une marge positive de 29.51%

Cette différence suggère que les conditions commerciales, notamment les remises, pourraient contribuer aux pertes.

Recommandation : analyser les transactions déficitaires et réexaminer les politiques de remise appliquées à cette sous-catégorie.



##### Analyse 2 – Impact des remises 

Les transactions bénéficiant de remises supérieures à 60% présentent une marge bénéficiaire de -122.63%.

Ce résultat met en évidence une association entre les remises élevées et les pertes.

Recommandation : examiner les ventes fortement remisées, identifier les catégories concernées et évaluer des seuils de remise adaptés à leur rentabilité.



##### Analyse 3 – Produits rentables

La sous-catégorie **Copiers** génère environ 66 .62K de bénéfice cumulé, ce qui en fait un contributeur important à la rentabilité globale.

Recommandation : identifier les références et segments clients responsables de cette performance afin d’évaluer les opportunités commerciales.







### 4\. Méthodologie 

###### Préparation des données – Power Query

Importation du dataset, contrôle des types, vérification de la qualité des données et préparation des colonnes nécessaires à l’analyse.

&#x20;

###### Modélisation – Power BI 

Création d’une table calendrier, gestion des relations, et préparation des dimensions temporelles.



###### Calculs – DAX 

Création de mesures pour le chiffre d’affaires, le bénéfice, la marge, la croissance annuelle, les clients distincts, et les références déficitaires.



###### Visualisation

Conception de trois pages interactives avec des filtres temporels, géographiques, et commerciaux, ainsi qu’une mise en forme conditionnelle pour identifier les pertes.







### 5\. Limites de l'analyse

Ce projet repose sur un jeu de données public utilisé à des fins pédagogiques.



Les données ne permettent pas d'étudier précisément les coûts de stockage, de transport ou de manutention.



Les relations observées entre remises et rentabilité ne suffisent pas à établir une causalité. Les recommandations proposées constituent donc des pistes d'investigation et non des décisions commerciales définitivement validées.







### 6\. Compétences mobilisées



Préparation et transformation de données avec Power Query

Création de mesures et indicateurs avec DAX

Modélisation de données dans Power BI

Conception de tableaux de bord interactifs

Analyse de rentabilité et segmentation commerciale

Formulation de recommandations métier







### 7\. Source des données

Kaggle : Sample Superstore - Vivek Chowdhury

Les données sont utilisées uniquement dans le cadre d'un projet personnel de démonstration de compétences en Business Intelligence.











#### Auteur

Projet personnel réalisé dans le cadre du développement de compétences en Business Intelligence et Business Analysis.

