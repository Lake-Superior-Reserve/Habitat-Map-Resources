# Habitat-Map-Resources
This repository links to external resources all related to the Lake Superior National Estuarine Research Reserve's Habitat Map - completed in 2025

# Habitat Map
This product was funded by the National Estuarine Research Reserve System Science Collaborative.
It is a high resolution habitat map of the St. Louis River Estuary, covering 57,000 acres and the
lower twenty-one miles of the St. Louis River.
- Viewable web map: To [view the habitat map](https://uw-mad.maps.arcgis.com/apps/mapviewer/index.html?webmap=dd5649dccb664124907db532d8cb24e3) without downloading
- Downloadable map: The habitat map can be downloaded, along with the datasets and
  intermediate products used to develop the map at [GeoData@Wisconsin](https://geodata.wisc.edu/catalog/4BEDD9CC-8E09-477D-B372-151BD36E9FFA)

## Methodology
For detailed methodology, please refer to these GitHub repositories
[Phase I](https://github.com/umn-uspa/StLouisEstuary_LandCover): Remote-sensing methodology. This step derived land cover from NAIP mosaic
using the machine-learning algorithm U-Net
[Phase II](https://github.com/WIStCart/StLouisEstuary-HabitatMap): This step refined the output from Phase I using geospatial rules to derive the
final habitat map

## Selected related products and datasets
### Drone Imagery: 
NRRI flew drone surveys at 4 sites in August and September 2024
- Bands: RGB (2cm resolution), and multispectral (including Red-edge and NIR at 4cm resolution)
- NDVI and surface model elevation derived
- Viewable web maps
1[Weasel (South Duck Hunter) and North Bays](https://umn.maps.arcgis.com/apps/mapviewer/index.html?webmap=8b84ade075d24121b4a8a37a1c2e8d11)
2[Pokegama Bay](https://umn.maps.arcgis.com/apps/mapviewer/index.html?webmap=12458ec7e8294025ba6e457b1cbca25d)
3[Rask Bay](https://umn.maps.arcgis.com/apps/mapviewer/index.html?webmap=ab4fd57076c14313b3e8585cbf2aaaf7)
4[Nemadji River](https://umn.maps.arcgis.com/apps/mapviewer/index.html?webmap=0fa05f3d6e3c40de9ecbf65867613490)
-Link to [download drone imagery](https://geodata.wisc.edu/catalog/A2B11A46-9B56-4187-8B60-A2C0DF6D193B) from GeoData@Wisconsin

### NAIP mosaic of the study area 
This resource can be downloaded from the Phase I Github, or [directly at this link](https://s3.msi.umn.edu/stlouis-estuary-habitat/NAIP_summer_mosaic_cropped.tif)
### Training data from field surveys 
This resource can be downloaded as part of the [GeoData@Wisconsin package](https://geodata.wisc.edu/catalog/4BEDD9CC-8E09-477D-B372-151BD36E9FFA) (Training_polys) that includes the final habitat map. 
This dataset includes:
- 1700 polygons from 2023 and 2024
- NERRS system, subsystem, class, and subclass
- Dominant species
- Invasive Species presence/absence for selected species (buckthorn, honeysuckle, cattail, yellow iris, purple loosestrife, and phragmites)

## Project webpage: 
[https://nerrssciencecollaborative.org/project/Veregin23/](https://nerrssciencecollaborative.org/project/Veregin23/)
All of the information in this handout (and more) can be found through the project webpage on
the NERRS Science Collaborative site. This page also includes an overall project summary and
details about the project team. Two links at the bottom of the page include detailed descriptions
of the datasets and final products (Data link) and methodology (Reports link)
