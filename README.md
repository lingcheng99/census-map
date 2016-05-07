# census-map
<br>
**Data**

The Amercian Community Survey (ACS) is a fantastic database that provides aggregate social and economic characteristics about American individuals and families down to the block group level. The motivation of this project is to use spatial analysis and mapping tools in R to showcase census data in choroplet map at the census tract level. R has great packages for geospatial analysis, such as ggmap and rgdal.

To create maps, use the "Topologically Integrated Geographic Encoding and Referencing" (TIGER) spatial database created by the Census Bureau and US Geological Survey. TIGER/Line Shapefiles are the most comprehensive ones. For small-scale mapping projects, I download the ‘cb_2014_06_tract_500k’ for 2014 california at 500k scale

<br>
**Mapping**

Focus on three counties in the bay area, San Francisco, Alameda, and San Mateo

* 'census_income_map': high-income rate ($200,000 or more) with ACS_14_5YR_B19001 data
<br>
<br>
* 'census_poverty_map': poverty rate with ACS_14_5YR_B17001 data
<br>
<br>
* 'census_uninsured_map': uninsured rate with ACS_14_5YR_S2701 data
<br>



