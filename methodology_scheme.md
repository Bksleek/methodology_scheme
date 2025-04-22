Methodology Scheme  
Research Title:  
Overview of Methods of Assessing the Impact of Transport Accessibility on the Efficiency of Urban Agriculture in Northern Cities of Nigeria


1. Indicator to Calculate  
The main indicator I aim to assess is:
Transport Accessibility Score vs Urban Agricultural Efficiency Index
This will help understand how transportation systems (like road access, proximity to markets, etc.) influence the success and productivity of urban agriculture in cities such as Kano, Kaduna, Sokoto, Maiduguri, and Bauchi.


2. Steps to Carry Out the Method
Step 1: Define and Delimit Study Area  
- Define boundaries of urban agricultural zones in the selected cities.
- Map out locations of transportation infrastructure (roads, markets, public transit points, etc.).

Step 2: Collect Data  
- Gather spatial and non-spatial data for transport and urban agriculture.

Step 3: Calculate Accessibility  
- Use tools like QGIS/ArcGIS to analyze proximity from farms to:
  - Nearest road
  - Nearest market
  - Nearest logistics/transport hubs

Step 4: Assess Urban Agriculture Efficiency  
- Consider factors such as:
  - Farm yield per area
  - Frequency of transport
  - Accessibility to urban market demand

Step 5: Integrate and Analyze  
- Compare and correlate accessibility score with urban agriculture outputs.
- Use statistical analysis or GIS-based visualization to draw insight.


3. Data Needed for Each Step

| Step                     | Data Type                       | Specific Data Needed                                   | Example Use Case                          |
|--------------------------|----------------------------------|--------------------------------------------------------|--------------------------------------------|
| Define Area              | Spatial                          | GIS shapefiles of cities and districts                 | Mapping urban boundaries                   |
| Transport Infrastructure | Spatial                          | Road network, transit hubs, market locations (geo data)| Analyzing proximity and connectivity       |
| Urban Agriculture Data   | Non-spatial / Spatial            | Farm size, crop types, yield data                      | Calculating efficiency                     |

| Flooding/Environmental   | Non-spatial / Raster             | NEMA flood zones, climate impact data                  | Risk overlay with agri zones               |
| Population / Urban Use   | Spatial / Statistical            | Population density, land use zoning                    | Context for agricultural demand and access |


4. Data Sources (All Open Source)

| Data Type                  | Source 1                                     | Source 2                                        |
|----------------------------|----------------------------------------------|--------------------------------------------------|
| Administrative Boundaries  | [GADM](https://gadm.org)                     | [GeoBoundaries](https://www.geoboundaries.org)   |
| Roads and Transport        | [OpenStreetMap](https://www.openstreetmap.org)| [Humanitarian Data Exchange](https://data.humdata.org) |
| Agriculture Data           | [NBS Nigeria](https://nigerianstat.gov.ng)   | [FAO](https://www.fao.org/statistics/en/)        |
| Flooding/Environmental     | [NEMA Nigeria](https://nema.gov.ng)          | [ReliefWeb](https://reliefweb.int/)              |
| Population                 | [WorldPop](https://www.worldpop.org)         | [UN Data](https://data.un.org/)                  |

5. Integration and Visualization Plan  
Once data is collected, I will:
- Process spatial data using QGIS
- Perform calculations and mapping of accessibility vs efficiency
- Highlight areas of poor transport access affecting productivity
- Use graphs, heatmaps, or visual dashboards for presentation