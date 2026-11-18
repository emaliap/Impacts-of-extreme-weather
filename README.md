# Identifying the impacts of extreme weather
EDS 223 HW4

## Repository purpose

Contains the script **texas_blackout.qmd** for developing maps estimating the number of homes in Houston, Texas that lost power from 2021 severe winter storms. 

The analysis uses remotely-sensed night lights data, acquired from the Visible Infrared Imaging Radiometer Suite (VIIRS) onboard the Suomi satellite.

## Repository Structure

```{}
.
├── data
│   ├── gis_osm_buildings_a_free_1.gpkg
│   ├── gis_osm_roads_free_1.gpkg
│   └── VNP46A1
├── README.md
├── texas_blackout.pdf
└── texas_blackout.qmd
```

## Data access

**.gitignore** removes **data/** from this repository

To download the data yourself, click on this [Google Drive link](https://drive.google.com/file/d/1bTk62xwOzBqWmmT791SbYbHxnCdjmBtw/view) 

Data files used in **texas_blackout.qmd** analysis include:

1) Within the `VNP46A1` folder:
    - `VNP46A1.A2021038.h08v05.001.2021039064328.tif`: tile h08v05, collected on 2021-02-07
    - `VNP46A1.A2021038.h08v06.001.2021039064329.tif`: tile h08v06, collected on 2021-02-07
    - `VNP46A1.A2021047.h08v05.001.2021048091106.tif`: tile h08v05, collected on 2021-02-16
    - `VNP46A1.A2021047.h08v06.001.2021048091105.tif`: tile h08v06, collected on 2021-02-16
2) `gis_osm_roads_free_1.gpkg`
3) `gis_osm_buildings_a_free_1.gpkg`

## Author

Emalia Partlow

## References

The `gis_osm_roads_free_1.gpkg` and `gis_osm_buildings_a_free_1.gpkg` data were sourced from **[OpenStreetMap (OSM)](https://planet.openstreetmap.org/)** and downloaded from **[Geofabrik](https://download.geofabrik.de/)**

The `VNP46A1` data was sourced from **[NASA’s Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC)](https://ladsweb.modaps.eosdis.nasa.gov/)**