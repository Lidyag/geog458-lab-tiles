# GEOG 458 Tile Map Project

## Web Map URL
 https://lidyag.github.io/geog458-lab-tiles/

## Examined Geographic Area
This project focuses on the University of Washington (UW Seattle) campus and the surrounding University District area.  
The thematic data represents point locations of UW campus buildings that I digitized myself in QGIS.

### Tile Set 1 – Basemap  
This tile set is a basemap created in QGIS from Mapbox layers.  
It shows general geographic context such as roads, buildings, and campus layout without any thematic information. The purpose of this layer is to provide a neutral background for other data.
<img width="3783" height="1764" alt="image" src="https://github.com/user-attachments/assets/1ca13780-2879-4aa4-9b27-fee26c7c38aa" />

### Tile Set 2 – UW Building Points (Self-Created Dataset)  
This thematic layer is based on a dataset that I **digitized myself in QGIS** rather than downloaded from an external source.  
I manually created point locations for University of Washington campus buildings, including the building I attend classes in and other important landmarks.  
This follows the assignment option that allows using a self-created geospatial dataset.
<img width="3814" height="1782" alt="image" src="https://github.com/user-attachments/assets/40ff8977-e4e7-469c-bc9e-cb6258f2a25d" />


### Tile Set 3 – Combined Basemap + Points  
This tile set combines the basemap (Tile Set 1) with the UW building points (Tile Set 2).  
It demonstrates how thematic information can be overlaid on a basemap to provide more meaningful spatial context.
<img width="3814" height="1811" alt="image" src="https://github.com/user-attachments/assets/120acaf3-f271-4c10-98e4-c266b6d8ba25" />

## Tile Set 4 – Mapbox Studio Style Map  
This tile set was created in Mapbox Studio with the goal of adding custom styles such as color changes, icons, and labels related to the UW campus theme.  
Due to repeated software crashes in QGIS and VS Code, the customization is basic, but the required workflow of creating a Mapbox-based layer and integrating it into the final web map was completed.
<img width="2875" height="1626" alt="image" src="https://github.com/user-attachments/assets/323969e1-532a-4d72-bcb0-e779c2d6423b" />

## Zoom Levels
All tile sets were generated using zoom levels **15- 18** to keep the tile size manageable while showing enough campus detail.
