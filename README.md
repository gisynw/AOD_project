# AOD_project
Data Sources
Predicted AOD Imagery
Predicted AOD imagery is loaded from ArcGIS Online item IDs for time steps T21-T25.

Population
Population exposure uses 2020 Census Block Groups:

Layer: USA Census Block Groups
REST service: https://services.arcgis.com/P3ePLMYs2RVChkJx/arcgis/rest/services/USA_Census_BlockGroups/FeatureServer/0
Key fields:
POPULATION_2020
POP20_SQMI
FIPS
Land Cover
Land cover uses the USA Annual NLCD Land Cover layer, filtered to 2020:

ArcGIS item ID: 32e2ccc6416746a9a72b4d216813f84f
Classes include developed land, forest, shrub/scrub, grassland, crops, wetlands, and open water.
Deployment With GitHub Pages
Create a GitHub repository.
Upload index.html and aod_flow_grid.js.
Go to repository Settings.
Open Pages.
Select the branch and folder to publish.
Save and wait for GitHub Pages to generate the site URL.
Notes
The map uses the ArcGIS Maps SDK for JavaScript from the ArcGIS CDN.
ArcGIS Online layers must be publicly accessible for anonymous users.
Some ArcGIS Living Atlas layers may require an ArcGIS Online organizational login depending on service permissions.
No OpenAI API key or backend server is required. The Map Assistant is a local rule-based query tool, not a full large language model.
Limitations
Population exposure is estimated from Census Block Group data.
Land cover is queried at clicked or analyzed points, not summarized over an area.
The Map Assistant currently supports simple AOD statistics and extreme-value queries.
Area-based drawing and population aggregation are not included in this version.
