# Piracy_indonesia
A database of Maritime Pirate Attacks focused on Indonesian Waters.

# Provenance of the Data
The original data was sourced from the International Maritime Bureau (IMB) and supplemented with additional information gathered from reputable maritime security sources and relevant governmental agencies. The dataset covers reported piracy incidents spanning the period from January 1993 to December 2020, focusing specifically on the Indonesian maritime region.
# Data Model
The dataset comprises essential attributes related to reported pirate attacks, incorporating the following variables:

Longitude: Indicates the geographical longitude of the attack location, providing specific spatial coordinates.
Latitude: Represents the geographical latitude of the attack location, providing precise spatial coordinates.
Attack Type: Categorizes the type of attack as either ‘Attempted’, ‘Boarding’, ’Boarded’ ‘Hijacked’, ’Suspicious’ or ‘NA’ for missing data.
Location Description: Provides a textual description of the attack location, offering context-specific details considering the maritime nature of the attacks.
Nearest Country: Includes the country code corresponding to the nearest shore to the attack location, facilitating proximity-based analysis.
EEZ Country: Encompasses the Exclusive Economic Zone (EEZ) country code within which the attack occurred, providing insights into territorial boundaries and maritime jurisdiction.
Shore Distance: Quantifies the distance in kilometers from the attack location to the nearest shore, offering valuable spatial information about the attacks in relation to coastal areas.
Shore Longitude: Specifies the geographical longitude of the closest point on the shore to the attack location, aiding in the precise delineation of proximity to land.
Shore Latitude: Specifies the geographical latitude of the closest point on the shore to the attack location, facilitating accurate spatial mapping of the incidents.
Attack Description: Provides a textual account of the attack, offering additional details and context regarding the nature and circumstances of the incident.
Vessel Name: Identifies the name of the attacked ship if available, enabling traceability and identification of specific vessels involved in the incidents.
Vessel Type: Specifies the type of vessel that was attacked, providing insights into the characteristics and classifications of the targeted ships.
Vessel Status: Indicates the status of the vessel at the time of the attack, categorizing it as 'Berthed,' 'Anchored,' 'Steaming,' or 'NA' for missing data, contributing to a comprehensive understanding of the operational context surrounding the incidents.

# Data Curation and Annotation
The curation process involved meticulous data cleaning to ensure data integrity and reliability. Irrelevant entries were removed, and missing values were either imputed using appropriate techniques or excluded from the analysis, depending on the specific context. Emphasis was placed on maintaining data consistency and accuracy throughout the curation process.
Enrichment Methods
The dataset was enriched with geospatial data to facilitate spatial analysis and visualization. Geospatial coordinates were utilized to create interactive maps using the R Leaflet library, enhancing the understanding of piracy incidents in relation to geographical locations and proximity to shorelines.
# Tools Used
The data curation and enrichment processes were predominantly carried out using the R programming language, leveraging various R libraries such as spatstat, dbscan, spdep, and R Leaflet for spatial analysis, data manipulation, and interactive visualization.

