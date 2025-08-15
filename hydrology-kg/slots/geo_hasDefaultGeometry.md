

# Slot: geo_hasDefaultGeometry


_The default Geometry to be used in spatial calculations. It is usually the most detailed Geometry._






This slot occurs 83346 times.


URI: [geo:hasDefaultGeometry](http://www.opengis.net/ont/geosparql#hasDefaultGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) |  |  no  |
| [UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md) |  |  no  |







## Properties

* Range: [GeoGeometry](../classes/GeoGeometry.md)





## Comments

* source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties
* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties
* source: http://www.opengis.net/ont/geosparql#
* source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties
* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties
* description: The default Geometry to be used in spatial calculations. It is usually the most detailed Geometry.
* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: geo_hasDefaultGeometry
description: The default Geometry to be used in spatial calculations. It is usually
  the most detailed Geometry.
notes:
- Duplicate properties defaultGeometry and hasDefaultGeometry exist because of an
  inconsistency between ontology and documentation in GeoSPARQL 1.0. Only hasDefaultGeometry
  is described in the documention.
comments:
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties'
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
- 'source: http://www.opengis.net/ont/geosparql#'
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties'
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
- 'description: The default Geometry to be used in spatial calculations. It is usually
  the most detailed Geometry.'
- No occurrences of this slot in the graph.
from_schema: okns:geo
source: http://www.opengis.net/ont/geosparql#
exact_mappings:
- http://www.opengis.net/ont/geosparql#defaultGeometry
domain: geo_Feature
slot_uri: geo:hasDefaultGeometry
domain_of:
- me_mgs_MGS-Well
- us_sdwis_PWS-ServiceArea
subproperty_of: geo_hasGeometry
range: geo_Geometry

```
</details>