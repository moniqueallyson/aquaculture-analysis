# Marine Aquaculture Suitability Function for Given and Chosen Species
## EDS 223: Assignment 3

<p align="center">
  <img src="image/marine_aquaculture.jpg" alt="Map making" width="600">
</p>

# Purpose of Repository 

This repository contains the materials for the [third homework assignment](https://eds-223-geospatial.github.io/assignments/HW3.html) for [EDS 223: Geospatial Analysis and Remote Sensing](https://bren.ucsb.edu/courses/eds-223), a course that is part of the Master of Environmental Data Science program completed at the Bren School of Environmental Science and Management.

# Background

Marine aquaculure can be a sustianable option for growing seafood to meet the growing demand in global food supply and steer from the more resource-intesive option of agricultural meat production (Hall, 2011).

# Data Information and Organization

Information on the oysters and blue mussel for the preferred was found on SeaLifeBase.

The **folders** are organized as the following:

```
EDS223-HWK1 
├── aquaculture_analysis.pdf
├── aquaculture_analysis.qmd
├── data
│   ├── average_annual_sst_2008.tif
│   ├── average_annual_sst_2009.tif
│   ├── average_annual_sst_2010.tif
│   ├── average_annual_sst_2011.tif
│   ├── average_annual_sst_2012.tif
│   ├── depth.tif
│   ├── wc_regions_clean.shp
└── README.md
```
All data was given by the instructor:

Inside the **data** folder, there are files for the `average annual sea surface temperature` from the years of `2008 to 2012`.  The file `depth.tif` is from a grided bathymetry data set which is a global terrain model for ocean and land that provides elevation data in meters. Lastly, `wc_regions_clean.shp` was used for the west coast regions in the U.S. to designate maritime boundaries.

The analysis can be read in the `aquaculture_analysis.pdf` and the code can be found in `aquaculture_analysis.qmd`

# Sources

"Blue Frontiers: Managing the Environmental Costs of Aquaculture", S. J. Hall, A. Delaporte, M. J. Phillips, M. Beveridge, and M. O’Keefe, [available here](https://digitalarchive.worldfishcenter.org/items/2d506b5a-74ca-4a3c-aa20-b2fa56feeb29)

"Daily Global 5km Satellite Sea Surface Temperature Anomaly (Version 3.1)", NOAA Coral Reef Watch, 2018, [available here](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php) [Accessed: Nov. 7, 2026]

"GEBCO_2022 Grid", GEBCO Compilation Group, British Oceanographic Data Centre, 2022, [available here](https://doi.org/10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c) [Accessed: Nov. 7, 2026]

"Maritime Boundaries and Exclusive Economic Zones", Flanders Marine Institute, MarineRegions.org, 2026, [available here](https://www.marineregions.org/eez.php) [Accessed: Nov. 7, 2026]

"Mytilus edulis, Blue Mussel", M. L. D. Palomares and D. Pauly (Eds.), SeaLifeBase, [available here](https://www.sealifebase.ca/summary/Mytilus-edulis.html) [Accessed: Nov. 7, 2026]

"Temperature but not ocean acidification affects energy metabolism and enzyme activities in the blue mussel, Mytilus edulis", O. B. Matoo, G. Lannig, C. Bock, and I. M. Sokolova, Ecology and Evolution, 2021, [available here](https://doi.org/10.1002/ece3.7289) [Accessed: Nov. 7, 2026]

