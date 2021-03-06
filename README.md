﻿# AddDemographicLayers-widget-js (OEI)

## Updates
Februay 12, 2019 Updated to work with 2012-2016 ACS that's available in the latest EJSCREEN 2018.

July 25, 2018 Updated to work with EPA EnviroAtlas.

August 29, 2017 Updated to work with 2011-2015 ACS that’s available in the latest EJSCREEN 2017.

April 4, 2016 Updated widget for HTTPS compatibility and latest WAB version

## Description
This is a widget developed for Esri’s Web AppBuilder (WAB) to map the Census demographic layers. It allows mapping a Census demographic layer as thematic map or graduated symbol map, which is in the same way as used in EPA’s [EJSCREEN](http://www2.epa.gov/ejscreen) application. 
Layers for multiple demographic variables can be added from one of 3 Census data sets: 
- 2012-2016 ACS
- 2010 Census
- 2000 Census

For more information about each of the Census datasets, please refer to [Census.gov](http://www.census.gov)!

Note: Due to the limitation of the LayerList widget on dynamic map services, some functionality of the LayerList widget may not be available. Specifically, the layer visibility checkboxes in the LayerList widget do not synchronize with the map once a layer has been added, and all checkboxes for an added layer will remain unchecked by default even though some layers may be visible.
The LayerList widget can however still be used to toggle the layer visibility and to show the pop-ups for each layer. To show pop-ups, after a demographic layer is added to the map, open the LayerList tool, expand the layer, and click the menu for the sub-layer that is currently displayed at the appropriate scale in the map, then select Enable Popups. 

For *EnviroAtlas*, rename the file of "LayerListView_4_EnviroAtlas_Only" to LayerListView.js and then use it to replace the same file under the LayerList widget folder.



