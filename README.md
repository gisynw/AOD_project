# AOD_project
## Data Sources

1. Predicted AOD Imagery
Predicted AOD imagery is loaded from ArcGIS Online item IDs for time steps T21-T25.

2. Population
Population exposure uses 2020 Census Block Groups:
Layer: USA Census Block Groups
REST service: https://services.arcgis.com/P3ePLMYs2RVChkJx/arcgis/rest/services/USA_Census_BlockGroups/FeatureServer/0
Key fields:
POPULATION_2020
POP20_SQMI
FIPS

3. Land Cover
Land cover uses the USA Annual NLCD Land Cover layer, filtered to 2020:
ArcGIS item ID: 32e2ccc6416746a9a72b4d216813f84f
Classes include developed land, forest, shrub/scrub, grassland, crops, wetlands, and open water.

## Notes
The map uses the ArcGIS Maps SDK for JavaScript from the ArcGIS CDN.
