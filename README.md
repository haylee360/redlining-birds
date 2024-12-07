# Analyzing Bird Diversity Across Historically Redlined Districts in Los Angeles County 
![redlining-image](https://knowledge.luskin.ucla.edu/wp-content/uploads/2023/09/IMG_0239.jpeg)
Source : [UCLA Center for Neighborhood Knowledge](https://knowledge.luskin.ucla.edu/2023/09/19/beyond-redlining-holc-spaces-development-in-los-angeles-county/)

This repository houses a set of maps, tables, and figures that illustrate redlined districts across LA County and how bird biodiversity observations are tracked across districts. 

## Skills
This analysis highlights

- Working with vector data using `sf` 
- Working with biodiversity data and socio-economic data
- Vector algebra and data cleaning
- Mapmaking, plotting, and data visualization using `tmap` and `ggplot`

## Description
File map
```
├── redlining-birds_files/
├── .gitignore
├── README.md                         
├── redlining-birds.Rproj
├── redlining-birds.html
└── redlining-birds.qmd   # Analysis quarto document                  
         
```
## Data access
Data in this project were pulled from  
- [US EPA's EJSCREEN tool](https://www.epa.gov/ejscreen/download-ejscreen-data)
- HOLC redlining data from the [Digital Scholarship Lab](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58&text=downloads)
- Bird diversity observations from the [Global Biodiversity Information Facility](https://eds-223-geospatial.github.io/assignments/gbif.org)

All relevant data available [here](https://drive.google.com/file/d/14CauXFZkVh_6z2Euq0m1Sq1kHQ31fiMk/view?usp=drive_link).

## References and Acknowledgements
All materials were created by [Ruth Oliver](https://github.com/ryoliver) for EDS-223. 

### Citations

- Global Biodiversity Information Facility, GBIF.org (13 October 2024) GBIF Occurence Download. 
- HOLC Redlining Data. Nelson, R. K., Winling, L, et al. (2023). Mapping Inequality: Redlining in New Deal America. Digital Scholarship Lab. https://dsl.richmond.edu/panorama/redlining 
- EJScreen: Environmental Justice Screening and Mapping Tool. United States Environmental Protection Agency. 2024 version. EJScreen. Retrieved: 10/4/24 from www.epa.gov/ejscreen. 
