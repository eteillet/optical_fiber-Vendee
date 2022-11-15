## Exploratory data analysis
##### _Optical fiber - Vendee_
---
The goal of this project is to clean and process the dataFrame (csv) to extract usable information on the deployment of optical fiber.
The second step is to use the potential of the Folium library to make it an impactful and dynamic visualization.

Github cannot render the interactive features of this notebook. So to visualize entire notebook with maps, please follow this link to [nbviewer](https://nbviewer.org/github/eteillet/optical_fiber-Vendee/blob/main/map.ipynb), a very useful open source project for displaying notebooks.

### Technology stack
    - Jupyter Notebook
    - Python3:
        - Pandas
        - Folium

### Data
ftth-en-pays-de-la-loire.csv (open data: [https://data.vendee.fr/ftth](https://data.vendee.fr/explore/dataset/234400034_001-002_deploiement-de-la-fibre-optique-ftth-en-pays-de-la-loire%40paysdelaloire/export/))

communes-vendee.geojson (open data: [https://data.vendee.fr/cities](https://data.vendee.fr/explore/dataset/234400034_communes-des-pays-de-la-loire%40paysdelaloire/export/?disjunctive.insee_comm&disjunctive.nom_comm&refine.insee_dep=85))

epci-vendee.geojson (open data: [https://data.vendee.fr/epci](https://data.vendee.fr/explore/dataset/234400034_groupement-de-communes-epci-en-pays-de-la-loire%40paysdelaloire/export/?disjunctive.type_epci&refine.dep_epci=85))
