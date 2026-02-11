# Health Facility Service Area Analysis

## Project Overview

This project analyzes geographic accessibility to health facilities by generating service areas based on travel distance. The goal is to assess how well communities are covered within selected LGAs.

## Objectives

- Filter selected LGA boundary
- Extract health facility locations
- Generate service areas (e.g., 5km radius or drive-time polygon)
- Export results as GeoJSON and CSV
- Visualize accessibility gaps

## Study Area

Selected Local Government Area (LGA): [Insert LGA Name]  
Country: Nigeria  

## Data Sources

- Nigeria LGA boundary dataset
- Health facility location dataset
- OpenRouteService API (for drive-time analysis)

## Tools & Technologies

- Python
- GeoPandas
- Shapely
- OpenRouteService API
- Folium / Matplotlib
- Jupyter Notebook

## Methodology

1. Load and filter LGA boundary.
2. Load health facility point dataset.
3. Generate service area polygons (5km or drive-time).
4. Overlay service area with LGA boundary.
5. Export final outputs.

## Outputs

- Filtered LGA boundary
- Health facility service area polygons
- Accessibility map
- CSV file for reporting

## Use Case

This analysis can support:
- Health planning
- Emergency response planning
- Resource allocation
- Identifying underserved communities

## How To Run

1. Clone repository
2. Install dependencies:
   pip install geopandas openrouteservice folium
3. Add your OpenRouteService API key
4. Run the notebook
## Sample Output

![Service Area Map] <img width="1366" height="683" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/cbd1be59-625e-4d3c-8c16-95dd445668bf" />

