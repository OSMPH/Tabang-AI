# HRSL Philippines derived vectors

This data was derived from Facebook's [High Resolution Settlement Layer](https://ai.facebook.com/blog/mapping-the-world-to-help-aid-workers-with-weakly-semi-supervised-learning/) for the Philippines.

Data included are the following:

* `hrsl_ph_buffer100m_v1.geojson.zip` - HRSL vector with a buffer of 100 meters, joined with administrative [Pcodes](https://www.humanitarianresponse.info/en/help/cod-pcodes-use-hrinfo).
* `hrsl_ph_500m_grid_v1.geojson.zip` - 500m grid based intersected with `hrsl_ph_buffer100m_v1.geojson`.
* `ph_admin_code.csv` - Administrative names and Pcodes up to admin level 3 (municipality) which can be joined to the above GeoJSON.
 
### Changelog

* 2019-09-06 - version 1
  * Known issue - Bacolod City is not included due to geometry issue of the polygon from administrative boundaries.

### Sources
* Facebook Connectivity Lab and Center for International Earth Science Information Network - CIESIN - Columbia University. 2016. [High Resolution Settlement Layer (HRSL)](https://www.ciesin.columbia.edu/data/hrsl/). Source imagery for HRSL © 2016 DigitalGlobe. Accessed 01 June 2019.
* National Mapping and Resource Information Authority (NAMRIA), Philippines Statistics Authority (PSA). 2016. Indicative Municipal/City boundaries of the Philippines (Second quarter 2016).  Accessed 12 August 2019.
