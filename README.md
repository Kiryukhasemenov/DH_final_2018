# DH_final_2018
maps with names of settlements related to colours

### Files:

each file is dedicated to a color, except China, where all colors are on one map.

### Presentation:

its name is "In Search of Emerald City"

### All other materials used for research:

you can find it here

https://drive.google.com/drive/folders/1XuUbWIgNqg8HZ-TaQHRbb-NWRvlf_LCP?usp=sharing

## The working process:

### Data source:

We used Wikidata queries made with SPARQL language, and for Chinese we also checked the Google maps and added some cities to our maps thanks to this source

### Process: 

1. Use of Wikidata Query similar to that in the repository (wikidata.txt).  The codes of countries and colours are in the table "база_данных.xls" in the Google Drive.

2. Creating the Python code to transfer the .csv results of wikidata query to .geojson. The code is in the repository (unpacking.ipynb)

3. Manual check of the results (in order to avoid homonimy)

4. Creating the Python code to visualise the  data (matplotlib.pyplot library). The code is in unpacking.ipynb as well.
