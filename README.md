# Analyse_financiere_sur_la-toile
Du webscraping avec Beautiful Soup

## Présentation:
Nous avons décidé de traiter les données du site Boursorama pour pratiquer du WebScraping sur des données financières.

## Le choix des technologies:

Afin de récupérer et préparer les données sur le site internet, nous avons utilisé deux modules de Python: Requests et Beautiful Soup.
En ce qui concerne la représentation graphique nous avons opté pour Grafana. Ce dernier présente l'avantage d'exporter en JSON des représentation graphiques, en plus de son érgonomie pour executer des requêtes.

Nous avons également utilisé Docker pour mettre en place un container contenant MySQL, pour stocker la base de données et un container grapahana. Cela a été réalisé plus facilement grace à la création d'un fichier Docker-compose.

