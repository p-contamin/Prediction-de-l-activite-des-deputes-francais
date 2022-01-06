# Projet Python sur l'activité parlementaire des députés français

Bienvenue sur le Github de notre projet Python Pour le Data Scientist:

L'objectif de ce projet est de prédire l'activité parlementaire des députés de la XVe législature. 

Notre projet se divise en 3 étapes : 

## La récupération des données 

Les données que nous utilisons sont issues de quatre sources : 

1. Les données fournies par l'INSEE sur les caractéristiques socio-démographiques des circonscriptions en 2013 ainsi que le détail du résultat des élections législatives de 2017 au premier et second tour. 

2. Les données issues de l'API du site nosdeputes.fr qui recense l'activité parlementaire des députés de la XVe législature. 

3. Les données récupérées par webscrapping du site foller.me qui répertorie l'activité des utilisateurs sur Twitter. 

La base de données qui combine toutes ces informations s'appelle tab_final.csv. Elle est disponible dans l'onglet "rassemblement des données" de notre repository. 

## L'analyse descriptive 

Notre analyse s'effectue en 2 temps : 

1. Une analyse classique : on s'intéresse aux caractéristiques classiques des députés pour vérifier que la base de donnée est cohérente puis on regarde les corrélations entre certains groupes de variables (les caractéristiques des électeurs, les participations parlementaires, les activités sur Twitter, les conditions d'élection). L'objectif est de créer des indices pour les variables fortement corrélées au besoin et 

2. Une analyse avec cartographie : l'objectif est de regarder si les caractéristiques des députés et leur activités (parlementaires et médiatiques) sont réparties ou non uniformément sur le territoire et regarder 

## La modélisation 

La modélisation se décompose en trois parties : 

1. Une ACP : elle permet de créer un indice synthétique de participation parlementaire pour les députés. 

2. Un clustering : avec toutes les variables qui caractérisent les députés. Nous avons utilisés deux modèles de clustering qui rendent des résultats similaires. 

3. Une régression : essayer de prédire l'indice synthétique de participation parlementaire en fonction des caractéristiques des députés recensées dans la base de donnée tab_final. 


