# OpenFields
This is an ArcMap (10.1 - 10.6) Addon for Farmland Assessment in Illinois.

--__This project is owned by Cloudpoint Geographics Inc.__---

It takes your Existing Three layers: Land Use, Parcels and Soils and performs a geoprocessing Union based on Parcel Number. The outputs are Shapefile plus CSV to TXT for importing the results into a County CAMA system.  Options for Flood debasement or deeded acreage are available. The tool has well documented help and was build using Python. Just installing the addon should be straightforward OR you can modify the Python for your own customization. 

Please note: THIS TOOL DOES NO FARMLAND VALUATION. It simply performs the spatial analysis needed for Farmland assessment, all value calculations are done in your county CAMA system. 


Most Users can simply download the "OpenFields.esriaddin" and install it. Everything is packaged there. Those interested in the source code can see that as well. BUT you will have to re-compile your changes in order to make the ArcToolbox an add-on again. 


It is important that you run the settings the first time you use the tool and after each upgrade. There are new options being added, including a Summary .csv. It was a requested bonus that Kendall was able to put in before he left us. 

Kendall Knapp (Cloudpoint's Genius Intern) created this December 2016. We are available for customization and will support those customizations, however the base script is available AS IS. Cloudpoint Geographics, Kendall or Micah Williamson (account owner) are NOT liable for any miscalculations of your data, use at your own risk.
