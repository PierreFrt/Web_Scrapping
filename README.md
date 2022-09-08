# Web_Scrapping

## Test de Selenium pour récupérer des données d'une page Web et les stocker sur un fichier CSV.

## Le site books.toscrape est un site pour s'entrainer au WebScraping et correspond à un catalogue de livres réels avec leur couverture mais avex des prix et notes fictifs.

L'obectif est de créer un fichier CSV regroupant pour chaque livre, son titre, son prix, sa note et l'url de l'image de la couverture. Pour cela, on va utiliser Selenium (pour simuler un navigateur Web), Request (pour récupérer le code HTML des différentes pages) et BeautifulSoup (pour naviguer et récupérer facilement les données que l'on souhaite à partir du code HTML).