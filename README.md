## Barangay Names in the Philippines

*Barangays* (similar to villages or boroughs) is the smallest administrative unit in the Philippines. There are over 42,000 barangays located within 1,642 cities and municipalities in 81 provinces.

For this project, and after a number of iterations, I've decided to look into Mega Manila – the metropolitan region that includes the capital region and neighboring provinces.

The Mega Manila region has about 4,000 barangays.

Data source is Humanitarian Data Exchange from the UN OCHA, which cites the Philippine Statistics Authority and the National Mapping and Resource Information Authority as sources. Excel and Shape files are available and have been downloaded at: https://data.humdata.org/dataset/cod-ab-phl 

The original data contains the name and Philippine Standard Geographic Code or PSGC of each administrative level, in addition to other information:
* ADM_4 - Barangay
* ADM_3 - City/Municipality
* ADM_2 - Province
* ADM_1 - Region
* ADM_0 - Country
* Area in square kilometers

**What I want to do is to create a toponymic map of barangays, looking at the following:**
* Which barangay names are the most common?
* Put them in categories and count to get a sense of how barangays are named across the country. Example: Religious (saints) or Historical figures (national heroes) or politicians
* After putting them into categories, look at possible subcategories (or vice versa)
* Look at other interesting information

**To achieve what I want to do, I will be using the following:**
* Pandas
* RegEx
* OpenAI API
* QGIS
* Mapbox

Based on my analysis of the data, 4 in 10 barangays are named after administrative functions – such as "Barangay," "Town Proper," "Poblacion.' It is no surprise then, that "barangay" also comes up as the most common name, given that some villages follow this naming convention: Barangay + number. Religious names, meanwhile, take up around 10% and these names dominate the Top 10 common barangay names.
