Prepared for: Evergreeners
Date: Ffebruary, 2024
Contributors:
- Obongofon Udombat, obongofonekpeu2018@gmail.com


- GeoJSON File (uspvdbGeoJSON.zip):

CHANGELOG.txt: Likely contains information about the updates or changes made in this dataset.
uspvdb_v1_0_20231108.geojson: This is the GeoJSON file containing spatial data. GeoJSON is useful for mapping and spatial analysis, particularly in web applications.
CSV File (uspvdbCSV.zip):

CHANGELOG.txt: Similar to the one in the GeoJSON archive, it probably details changes in the dataset.
uspvdb_v1_0_20231108.csv: This is a CSV file, which is a tabular representation of the data. It's great for data analysis, manipulation, and can be easily imported into many data processing tools.
Shapefile (uspvdbSHP.zip):

CHANGELOG.txt: As in the other files, detailing dataset changes.
Shapefile components (uspvdb_v1_0_20231108.dbf, .prj, .sbn, .sbx, .shp, .shx, .xml): These are various components of a shapefile, a popular format for GIS software. It's used for storing the location, shape, and attributes of geospatial data.

Next, I'll perform an initial analysis of the CSV and GeoJSON files to understand the data structure. This analysis will help in determining what kind of dashboard or metrics might be useful for the US Department of Energy's project. Let's start by examining the CSV file to get an overview of the data.

The CSV file contains a variety of columns related to solar power projects. Here are some key columns and their possible meanings:

case_id: Unique identifier for each project.
multi_poly: Indicates if the project covers multiple geographical areas.
eia_id: Energy Information Administration (EIA) identifier.
p_state: State where the project is located.
p_county: County where the project is located.
ylat, xlong: Latitude and longitude coordinates.
p_area: Area covered by the project.
p_img_date: Date of the image or data capture.
p_dig_conf: Digital configuration or quality score.
p_tech_sec: Secondary technology used in the project.
p_axis: Axis type for solar panels.
p_azimuth: Azimuth angle of solar panels.
p_tilt: Tilt angle of solar panels.
p_battery: Information about battery storage.
p_cap_ac, p_cap_dc: AC and DC capacity of the project.
p_type: Type of the project (e.g., greenfield, brownfield).
p_agrivolt: Whether the project is agrivoltaic (combination of agriculture and photovoltaics).
p_zscore: A statistical measure, possibly indicating the project's performance or efficiency relative to others.

For the dashboard, we could consider:
Panel-to-Capacity Conversion Tool: Converts the number of solar panels to the total capacity in megawatts.
Operational Year Analysis Tool: Visualize the distribution of solar facilities based on their year of operation.
Technology and Efficiency Analysis: Analyze which technologies are most prevalent and which are performing best. This could inform recommendations for technology adoption in future projects.
A visualization (e.g., pie chart, bar graph) showing the prevalence of different solar panel technologies across the facilities.
This is perhaps the one we can incorporate the technology = the raw material calculations; glass, aluminum, copper, etc., there may be multiple tabs for this one ; one for each material isolated and defined Carly can provide these calculations and figures when we arrive to that part.
