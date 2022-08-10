---
title: "About"
permalink: "/About me/"
layout: page
---

![This is an image](/images/ErasmusCopernicusLogo.png) 

# Copernicus Master in Digital Earth (EMJMD)

## Personal Motivation 
-	Curios eager to learner
-	Great program for professional skill development (summer schools, conferences, internship)
-	International environment 
-	Nature lover
	
#### 1. Objectives
	- Learn new skills
	- Get involved in geo – related research projects
	- Improving the scientific writing skill
	- Map generation and data analysis skill" for any scientific career"

#### 2. Interests
	- Geo- projects 
	- Integration of remote sensing and in situ measurements. 
	- Learning appropriate ways to communicate and visualize hazards and risks to be relevant for decision-making.	
	- Do user friendly: maps and data bases
	- Integrate extract more information of images (With all types of wavelengths e.g.: optical, radar, lidar, thermal)



## Background

GEOLOGIST BACHELOR'S DEGREE – Universitat de Barcelona		ERASMUS – Háskóli Íslands
- Degree in Geology interested on Remote Sensing techniques.


| Experience                      | Location                                                                  |
|---------------------------------|---------------------------------------------------------------------------|
| Junior InSAR Engineer           | Sixense Iberia, Dares Technology                                          |
| Junior Remote Sensing Geologist | Sixense Iberia, GEO3BCN-CSIC / Lítica , Dares Technology, Háskóli Íslands |
| Junior Geologist                | GeoServei, Litoclean, GEO3BCN-CSIC / Lítica                               |


- Junior InSAR Engineer: 
	- Interpretation of InSAR data and optical images in operational projects. SAR Interferometry (PSI) preprocessing and postprocessing. Multi-sensor (Sentinel-1 A/B, ERS/ENVISAT ASAR, TerraSAR-X,Radarsat-2). 
	- Reporting of operational projects for customers. 

- Junior Remote Sensing Geologist: 
	- Optical image processing (Sentinel-2, ASTER, Landsat-8).
	- Mining sector, ore estimation with portable laboratory cameras, images (optic, hyperspectral).
	- Integration optical multispectral data and sampling data gathered on the earth surface.
	- Working with the GPS points position taken on the monitoring of the fissure lava eruption.

- Junior Geologist:
	- Hydrogeology and edaphology mapping.
	- GIS consultant.
	- Assistant geotechnical projects.
	- Sampling in the mining sector
	- Assistant in water and soil remediation projects


PUBLICATIONS

'Machine Learning For Mineral Identification And Ore Estimation From Hyperspectral Imagery In Tin–Tungsten
Deposits: Simulation Under Indoor Conditions'
2021
Lobo, A.; Garcia, E.; Barroso, G.; Martí, D.; Fernandez-Turiel, J.-L.; Ibáñez-Insa, J. Machine Learning for Mineral
Identification and Ore Estimation from Hyperspectral Imagery in Tin–Tungsten Deposits: Simulation under Indoor
Conditions. Remote Sens. 2021, 13, 3258. https://doi.org/10.3390/rs13163258


## Outlook
-	Working with geo – related projects
-	Continue in academia?
-	Contribution to solving society necessities













##############################################################

library(leaflet)
set.seed(12345)
df <- data.frame(lat= runif(30, min = 19.07, max = 28.70), long=runif(30, min = 72.87, max = 77.10))
head(df)
##        lat     long
## 1 26.01230 76.22442
## 2 27.50370 72.89533
## 3 26.39826 73.66402
## 4 27.60338 75.75416
## 5 23.46591 74.43554
## 6 20.67216 74.39968
df %>%
  leaflet( width = 900) %>%
  addTiles() %>%
  addMarkers(clusterOptions = markerClusterOptions(), popup = "Hi")


```{r out.width='100%', echo=FALSE}
library(leaflet)
leaflet() %>% addTiles() %>%
  setView(-93.65, 42.0285, zoom = 17) %>%
  addPopups(
    -93.65, 42.0285,
    'Here is the <b>Department of Statistics</b>, ISU'
  )
```

## Screenshots

![screenshot](https://user-images.githubusercontent.com/4943215/109431850-cd711780-7a08-11eb-8601-2763f2ee6bb4.png)

![screenshot](https://user-images.githubusercontent.com/4943215/109431832-b6cac080-7a08-11eb-9c5e-a058680c23a1.png)

![screenshot](https://user-images.githubusercontent.com/4943215/73125194-5f0b8b80-3fa4-11ea-805c-8387187503ad.png)
