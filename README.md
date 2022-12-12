# The effect of greenspace on air quality: an analysis of Jefferson County, Kentucky

## Link to Map

The map for this project can be viewed at https://smda250.github.io/louisville-aqi/

## Map Description and Background

This map is created to produce a visual representation to support studies that indicate the presence of greenspaces have a postive influence on air quality of environments.
These studies, such as [Maas 2006](https://jech.bmj.com/content/60/7/587) state that greenspaces such as parks and dense tree canopy can benefit human health and the surrounding environment. The air quality of an environment is measured using the Air Quality Index (AQI) and determines how safe the air is for human health and is quantified on the scale below .

![AQI](AQI.png)

*AQI scale from https://scijinks.gov/air-quality/*

The map for this study focuses on the AQI based upon the ground-level ozone pollutants in Jefferson County, Kentucky. Ground-level ozone was chosen as the focal pollutant since the AQI is separated by pollutant, and ground-level ozone poses the greatest risk to human health out of the five major pollutants measured. The AQI for the ozone is then compared against the amount of greenspaces present nearby. The AQI measured in this study is an eight-hour average for the monitoring stations selected in the study for the date 11/28/2022. Point data for AQI is only available for individual days from any data source, so one day was chosen for a smaller scope of study for this project. 

Since there are many factors that can impact the AQI of a region, one more factor is considered in the scope of this study. Nonpoint source pollution through transportation is the largest contributor to raising AQI values to unhealthy conditions. Due to this, major roads and railroads are mapped and compared against the regions of mapped AQI to compare with the amount of greenspace within the monitoring areas.

## Methods

Currently shown on the map are the air quality monitoring stations, with a 4 km buffer zone generated around each station. This 4 km buffer zone shows the region for which each monitoring station reports AQI data. All greenspaces have been combined into one layer and clipped to the buffer zone,
and additionally railroads and major roadways have been combined into one layer and clipped to these zones. 
		
To complete this map, there is still remaining work to finish the full analysis. To complete this, the percentage of greenspace within each buffer zone will be calculated for
comparison between each monitoring station to analyze for a trend between greenspace and AQI values. The number of miles of major roadways and railways will summed for each buffer
zone as well and used for comparison and analysis for these stations. Once this is completed, a full conclusion can be delivered on the effects of greenspace on air quality, and the 
transportation results can help address any discrepancies or add to the discussion.  

## Results



## Conclusions


Limitations for this study include the scope of AQI measured in this study are indicative for only one day of measurement. Other factors such as weather, holidays influencing transportation, and industries nearby such as factories on the western half of Louisville may cause this value to change daily. Future studies would include a larger library of temporal data included to also monitor the impact of aforementioned environmental factors. 

## Data Used and Data Sources

Air Quality Data - Environmental Protection Agency website https://aqs.epa.gov/aqsweb/airdata/download_files.html#Annual

Greenspaces Data - Louisville/Jefferson County Information Consortium via hub.arcgis.com 

    Recreation areas - https://hub.arcgis.com/datasets/LOJIC::jefferson-county-ky-recreation-areas-2019-1/about

    Louisville Metro Parks - https://hub.arcgis.com/datasets/LOJIC::louisville-ky-metro-parks-2/about

    Tree canopy - https://hub.arcgis.com/datasets/LOJIC::jefferson-county-ky-tree-canopy-areas-2019-1/about

    Natural areas - https://hub.arcgis.com/datasets/LOJIC::jefferson-county-ky-natural-areas-2/about

Transportation Data - Louisville/Jefferson County Information Consortium via hub.arcgis.com

    Railroads - https://hub.arcgis.com/datasets/LOJIC::jefferson-county-ky-railroads-2022/about

    Major roads - https://hub.arcgis.com/datasets/LOJIC::louisville-metro-area-ky-major-roads/about