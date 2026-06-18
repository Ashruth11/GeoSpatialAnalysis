# GeoSpatial Analysis Portfolio

A collection of geospatial analysis case studies completed using Python, GeoPandas, Pandas, Matplotlib, and spatial datasets. Each project focuses on solving a real-world business, environmental, or public service problem through geographic data analysis and visualization.

## Tools & Technologies

* Python
* Pandas
* GeoPandas
* Matplotlib
* Shapely
* Coordinate Reference Systems (CRS)
* Spatial Analysis & Mapping

---

## Case Study 1: Philippines Accessibility Analysis

### Business Question

Where should a global non-profit expand its reach in remote areas of the Philippines?

### Approach

* Analyzed the locations of existing Kiva Field Partners.
* Visualized partner coverage across the Philippines using geospatial mapping.
* Identified underserved regions with limited access to microfinance services.

### Key Finding

Mindoro emerged as a promising candidate for expansion due to its relatively large population area and lack of existing Field Partner coverage.

---

## Case Study 2: Purple Martin Migration Analysis

### Research Question

How do Purple Martins, a threatened bird species, travel between North and South America? Are the birds travelling to conservation areas?

### Approach

* Converted GPS coordinates into Point geometries using GeoPandas.
* Applied CRS (EPSG:4326) for geographic mapping.
* Created migration routes using LineString geometries.
* Visualized migration paths across North and South America.
* Compared bird locations with protected conservation areas.

### Key Finding

Several migration locations overlap with protected regions in South America, highlighting the importance of conservation areas for migratory bird species.

---

## Upcoming Case Studies

### Case Study 3

Which areas of Japan could potentially benefit from extra earthquake reinforcement?

### Case Study 4

Which Starbucks stores in California are strong candidates for the next Starbucks Reserve Roastery location?

### Case Study 5

Does New York City have sufficient hospitals to respond to motor vehicle collisions? Which areas of the city have gaps in coverage?

---

## Repository Structure

GeoSpatialAnalysis/

├── Notebooks/

├── Images/

│ ├── CaseStudy1/

│ └── CaseStudy2/

├── README.md

└── .gitignore
