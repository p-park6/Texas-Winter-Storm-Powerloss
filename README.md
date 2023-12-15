# Texas Winter Storm causing blackout and Powerloss

This repository covers the Texas blackouts caused by the intense Winter storms in February 2021. The University of Austin at Texas Energy Institute released a one hundred page document detailing what happened before the storm, during the storm, and after the storm. From the document, about 40% of the power provided by ERCOT was lost and not functional.[^1]


## What this notebook covers:
-   load vector/raster data from `.tif` files
-   simple raster and vector operations
-   spatial joins of `.tif` and `sf` files


## Note on reading in the data
Since the dataset is quite large to be pushed to Github, it is **highly recommended** to:

1. Download the data first
2. Upload it in the .rproj you are working in
3. Put the data file in the .gitignore file.

Data can be accessed [here](https://drive.google.com/file/d/1bTk62xwOzBqWmmT791SbYbHxnCdjmBtw/view)

## What is included in this Repo?

```
.
├── LICENSE
├── R
│   ├── Texas-Winter-Storm-Powerloss.html
│   ├── Texas-Winter-Storm-Powerloss.qmd
│   └── Texas-Winter-Storm-Powerloss_files
│       └── figure-html
│          ├── unnamed-chunk-16-1.png
│          ├── unnamed-chunk-16-2.png
│          ├── unnamed-chunk-2-1.png
│          ├── unnamed-chunk-2-2.png
│          ├── unnamed-chunk-3-1.png
│          └── unnamed-chunk-4-1.png
├── README.md
├── Texas-Winter-Storm-Powerloss.Rproj
└── data
    ├── ACS_2019_5YR_TRACT_48_TEXAS.gdb
    ├── VNP46A1
    ├── gis_osm_buildings_a_free_1.gpkg
    └── gis_osm_roads_free_1.gpkg

```

[^1]: University of Texas at Austin Energy Institute. (July 2021). The Timeline and Events of the February 2021 Texas Electric Grid Blackouts. 