# Case-Study-OSM-Austin

audit_and_mapping.py file finds overabbreviated street names and maps them to their unabbreviated name.

data.py prepares the data for its upload to SQL. It modifies the main XML file into separate csv files for each of the wanted SQL tables.
It also cleans up the data where needed.

the upload-to-SQL.py script is used to upload the csv files directly into SQL using a predetermined schema.

sample.osm is a small sample of the complete OSM data from Austin, Texas.
