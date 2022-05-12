# Mangiapane_Gianluca_BurmesePythons_Everglades
This project is my Independent Research Capstone for the Masters program in Urban Spatial Analyis at the Unviersity of Pennsylvania. In this project, I chose to study the spatial relationship of Burmese Python sightings in Florida. I am fascinated by the nature and explosive properties of invasive species, and how detrimental it can be to local wildlife. Burmese Pythons are magnificent creatures, and are prime hunters that evolved to be as efficient as possible. In the area of South Florida, they easily claim prey that have no instinctual fear of an animal of that caliber. As an animal lover, I struggle with villianizing invasive species for the harm they can cause to local ecosystems, especially in the case of the Burmese Python, for they didn't choose to invade the Florida everglades. The first known cases of Burmese Pythons being sighted in Southern Florida in 1979 were due to being released as unwanted pets, a sad byproduct of the exotic pet trade in the state. As more and more python pets were released, the population has steadily grown. Due to their elusive nature, scientists have trouble estimating their population, with numbers ranging between 10,000 to 100,000 in the last twenty years. Traditional methods of detection, such as remote sensing and detector dogs yield low success rates, yet novel techniques such as Enviromental DNA can help confirm general locations of where pythons travelled through, to further search efforts. My project looks to model relationships between various spatial and ecological variables along with known python sightings, to assess correlation and help provide more localized areas in which Environmental DNA samples should be concentrated. This can save time and resources for the envirnmental DNA sampling team by guiding them to specific areas to sample, instead of the whole state. 


# Data Sources 

1. Python Count data was compiled by the University of Georgia - Center for Invasive Species and Ecosystem Health, published as an EDD map, which can be found here at https://www.eddmaps.org/distribution/viewmap.cfm?sub=20461

2. The following datasets are from the Florida Geospatial Open Data portal https://geodata.floridagio.gov/ 

   - Bird Sanctuary Sites
   - Eagle Nests
   - Bird Nest Sites from 2000
   - Land Mammal Habitats
   - Bird Habitat Areas from 2003
   - Shorebird Habitats 
   - Snowy Plover Nests 
   - Wading Bird Colonies
   - Urban Boundaries
   - Lakes
   - Springs
   - Rivers
   - Flowing Water
   - Wading Bird Rookeries
   - Stormwater Activity Sites 
   - Waterbodies
   - Submerged Lands

3. Traffic Data and Florida County data was found at the Florida Traffic Online data portal https://tdaappsprod.dot.state.fl.us/fto/ 

4. Census data was taken from the 2016 ACS API through the Cenpy library in Python 


# Folders 

- See [/raw_data](https://github.com/CPLN-680-Spring-2022/Mangiapane_Gianluca_BurmesePythons_Everglades/tree/main/raw_data) for identified datasets from above. For 2003 Bird Colonies and Waterbodies, the dataset is too large for Github, but the data can be found at the Florida Geospatial Open Data portal

- See [/scripts](https://github.com/CPLN-680-Spring-2022/Mangiapane_Gianluca_BurmesePythons_Everglades/tree/main/Scripts) for feature engineering for the data and the negative binomial regression model and spatial autocorrelaiton in jupyter notebooks 

- See [/plots](https://github.com/CPLN-680-Spring-2022/Mangiapane_Gianluca_BurmesePythons_Everglades/tree/main/Plots) for plots in the final report

- See [/documents](https://github.com/CPLN-680-Spring-2022/Mangiapane_Gianluca_BurmesePythons_Everglades/tree/main/Documents) for the progress of my reports, presentations, and peer code edits 

- See [Mangiapane_BurmesePythons_Everglades](https://github.com/CPLN-680-Spring-2022/Mangiapane_Gianluca_BurmesePythons_Everglades/blob/main/Mangiapane_BurmesePythonsEverglades_Report%20.pdf) for my final report
