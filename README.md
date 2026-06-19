# GeoSpatial Analysis Portfolio

This repository contains geospatial analysis projects completed using Python, GeoPandas, Pandas, Matplotlib, and spatial datasets. The focus of these projects is to solve real-world problems using geographic data and visualization techniques.

## Tools & Technologies

* Python
* Pandas
* GeoPandas
* Matplotlib
* Shapely
* Coordinate Reference Systems (CRS)
* Spatial Analysis

---

## Case Study 1: Philippines Accessibility Analysis

### Business Question

Where should a global non-profit expand its reach in remote areas of the Philippines?

### Techniques Used

* KML data processing
* GeoDataFrame creation
* Point geometry analysis
* Geographic visualization

### Key Finding

Mindoro was identified as a potential expansion location due to the absence of existing Field Partner coverage in the dataset.

---

## Case Study 2: Purple Martin Migration Analysis

### Research Question

How do Purple Martins, a threatened bird species, travel between North and South America? Are the birds travelling to conservation areas?

### Techniques Used

* GeoDataFrame creation
* Point and LineString geometries
* CRS implementation (EPSG:4326)
* Migration route visualization
* Protected area analysis

### Key Finding

Several migration locations overlap with protected conservation regions in South America, highlighting the importance of these areas for migratory bird species.

---

## Repository Structure

GeoSpatialAnalysis/

├── Notebooks/

│   ├── 01_Philippines_Accessibility.ipynb

│   └── 02_Purple_Martin_Migration.ipynb

├── Images/

│   ├── CaseStudy1/

│   └── CaseStudy2/

├── README.md

└── .gitignore
