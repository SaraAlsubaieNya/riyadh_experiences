#  Riyadh Experiences × Transit
 
**Can you actually reach Riyadh's best places by metro or bus?**
 
A spatial analysis of 38 experiences across Riyadh : museums, parks, palaces, mosques, malls  mapped against the city's metro stations and bus stops to answer one question: **how many are actually reachable without a car?**
 
##  What's inside
 
-  **38 geocoded experiences** across 10 categories
-  Buffer analysis: within **500 m / 1 km** of a metro
-  Bus access: within **300 m** of a stop
-  DBSCAN clustering to find experience hotspots
-  Interactive Folium map with colored metro lines
-  Gradio dashboard with KPIs, charts & tables
##  Built with: 
 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=for-the-badge&logo=pandas&logoColor=white)
![Shapely](https://img.shields.io/badge/Shapely-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-77B829?style=for-the-badge&logo=leaflet&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=for-the-badge&logo=gradio&logoColor=white)
 
##  Run it
 
```bash
pip install -r requirements.txt
jupyter notebook code.ipynb
```
 
##  Data
 
Experience coordinates hand-collected from Google Maps. Metro & bus data from [Riyadh Open Data](https://www.data.gov.sa/).
 
---
 
*Built as a spatial data science project exploring Riyadh's transit accessibility.*
