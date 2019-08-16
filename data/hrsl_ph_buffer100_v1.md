# HRSL Philippine

This data is a GeoJSON derived from Facebook's [High Resolution Settlement Layer](https://ai.facebook.com/blog/mapping-the-world-to-help-aid-workers-with-weakly-semi-supervised-learning/) for the Philippines.

Using QGIS, the HRSL raster layer was was converted to vector.  Using the QGIS processing tool, we created a buffer of 100 meter for each polygon and then intersected with HDX's [Philippine administrative data](https://data.humdata.org/dataset/philippines-administrative-levels-0-to-3).


### Changelog

* 2019-08-16 - V1


### Source
* Facebook Connectivity Lab and Center for International Earth Science Information Network - CIESIN - Columbia University. 2016. High Resolution Settlement Layer (HRSL). Source imagery for HRSL © 2016 DigitalGlobe. Accessed 01 June 2019.
* National Mapping and Resource Information Authority (NAMRIA), Philippines Statistics Authority (PSA). 2018. Philippines administrative level 3 (municipality) boundary polygon shapefile. Humanitarian Data Exchange (https://data.humdata.org/). Accessed 12 August 2019.
