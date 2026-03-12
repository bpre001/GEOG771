# GEOG771 Lab01 Summary

## 1. Introduction to R and RStudio (`new-intro_2025.html`)
- RStudio interface navigation (console, editor, environment, plots panels)
- R fundamentals: variables, assignment (`<-`), object classes, vectors, factors
- Installing and loading packages
- Using help resources (`?`, `help()`, `example()`)

## 2. Data Manipulation (`Data_man_2025.html`)
- Data structures: matrices and data frames
- Importing data: `read.csv()`, `read.table()`, `read.delim()`
- Exploring data: `head()`, `dim()`, `str()`, `summary()`, `View()`
- Data type conversion (numeric, character, factor)
- Subsetting, grouping with `cut()`, and handling `NA` values

## 3. Descriptive Statistics (`Descriptive_Statistics_2025_fin.html`)
- Summary statistics: `mean()`, `sd()`, `median()`, `quantile()`
- Handling missing values with `na.rm=TRUE`
- Grouped statistics using `tapply()`
- Applied to real-world SIMD (Scottish Index of Multiple Deprivation) data

## 4. Charts and Graphs (`Charts_and_Graphs_2025.html`)
- Base R plots: `plot()`, `hist()`, `barplot()`, with customisation (titles, colours, legends)
- **ggplot2**: `qplot()` and `ggplot()` with `aes()` mappings
- Geom types: bar, histogram, point, smooth (loess/lm)
- Faceting and multi-layer plots

## 5. Mapping Areas (`Mapping_Areas_2025.html`)
- Choropleth maps in base R using shapefiles and `findColours()`
- Choropleth maps in **ggplot2** using `geom_sf()`
- **tmap** package: `tm_shape()`, `tm_fill()`, `tm_borders()`, `tm_dots()`
- Proportional symbol maps, interactive maps, and basemap overlays

## 6. Spatial Data Manipulation (`Spat2025.html`)
- Reading shapefiles with the **sf** package (`st_read()`, `st_geometry()`)
- Creating spatial point data from CSV coordinates (`st_as_sf()`)
- Subsetting, clipping with `st_intersection()`, writing with `st_write()`
- Merging tabular data onto spatial objects (`merge()`, `st_join()`)
- Geometric operations: `st_buffer()` for buffer zones, coordinate reference systems (CRS)

---

**Key takeaway:** Lab01 builds from R basics → data handling → descriptive statistics → visualisation → spatial mapping, equipping students with end-to-end quantitative GIS skills in R.
