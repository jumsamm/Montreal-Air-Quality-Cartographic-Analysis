# Montreal Air Quality Cartographic Analysis
This project explores spatial patterns of PM2.5 air pollution levels across the city of Montreal using historical air quality monitoring station data (2022-2024). The goal is to visualize how these three different cartographic techniques are used to explore spatial patterns and demonstrate their influence on the interpretation of environmental data.
## Tools & Skills
- Tools : Kepler.gl and Excel
- Skills : Data Visualization on a Proportional Symbols map, a Grid Aggregation map and a Hexagonal Binning (with 3D extrusion) map.
## Data Source
[Données Montréal](https://donnees.montreal.ca/fr/dataset/rsqa-iqa-historique?) (Historial AQI Levels 2022-2024) & [Données Montréal](https://donnees.montreal.ca/en/dataset/rsqa-liste-des-stations) (List of Air Quality Stations and their Names)
- Data was obtained from the City of Montreal's open data portal and the main variables used were Station ID, Station Name, Latitude & Longitude, Average PM2.5 values and Elevation. This dataset was processed in Excel using pivot tables and attribute joins to link pollution readings with monitoring station coordinates.
## Maps
- Proportional Symbols Map
  Point-based visualization where symbol size and color represent PM2.5 pollution levels at each mmonitoring station. This method highlights variation between individual     stations.

Copy&Paste to view → file:///Users/jumana/Desktop/Proportional%20Symbols%20Map.html

  <img width="1184" height="785" alt="Screenshot 2026-03-12 at 7 19 15 AM" src="https://github.com/user-attachments/assets/f4606979-d232-4ab0-9dd7-5550e3347509" />

  
- Grid Aggregation Map
  Point data were aggregated into a regular grid to generalize pollution patterns across space. This technique reduces the visual dominance of individual stations but        smoothes out local variations.



Copy&Paste to view → file:///Users/jumana/Desktop/Grid%20Aggregation%20Map.html


  <img width="1358" height="789" alt="Screenshot 2026-03-12 at 7 22 59 AM" src="https://github.com/user-attachments/assets/e2c5750b-c771-4b5e-ad91-edceb11959ac" />
  
- Hexagonal Binning (with 3D extrusion) Map
  Hexagonal-shaped bins were used to aggregate monitoring station data. Vertical extrusion was applied using elevation values to produce a 3D representation. This technique, like the grid technique, introduces misleading spatial aggregation.



Copy&Paste to view → file:///Users/jumana/Desktop/Hex%20Bins%20Map.html


  <img width="1169" height="800" alt="Screenshot 2026-03-12 at 7 14 18 AM" src="https://github.com/user-attachments/assets/6a502993-d88e-488f-a50f-80b60db20ee9" />
