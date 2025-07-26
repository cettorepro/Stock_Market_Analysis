# Stock_Market_Analysis

Ce projet consiste à prendre les données financiers des plus grandes capitalisations boursières américaines et d'analyser leur données sur une période de 5 ans de 2018 à 2023. 
J'ai utilisé la librairie d'Apache Spark pour analyser ce grand volume de données.

Les données proviennent de Kaggle (https://www.kaggle.com/datasets/iveeaten3223times/massive-yahoo-finance-dataset?resource=download) et compte plus de 600 000 lignes.


Les colonnes de ce tableau sont : 
- 
-
-



Les défis que j'ai pu rencontré dans ce projet sont les suivants :

- L'incompatibilité de version de python entre le driver et le worker node.
- Les colonnes bruts du fichier CSV était tous sous forme de string donc utilisation des UDF types (user defined functions types)
- La non reconnaissance des dates car présence du fuseau horaire

Les étapes clés ont été : 
- 
-
-
-
