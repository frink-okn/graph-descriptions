

# Slot: geo_hasDefaultGeometry


_The default Geometry to be used in spatial calculations. It is usually the most detailed Geometry._






This slot occurs 12719 times.


URI: [geo:hasDefaultGeometry](http://www.opengis.net/ont/geosparql#hasDefaultGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site.md) |  |  no  |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) |  |  no  |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) |  |  no  |







## Properties

* Range: [GeoGeometry](../classes/GeoGeometry.md)





## Comments

* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties
* source: http://www.opengis.net/ont/geosparql#
* source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties
* description: The default Geometry to be used in spatial calculations. It is usually the most detailed Geometry.



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
- No occurrences of this slot in the graph.
comments:
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
- 'source: http://www.opengis.net/ont/geosparql#'
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties'
- 'description: The default Geometry to be used in spatial calculations. It is usually
  the most detailed Geometry.'
from_schema: okns:geo
source: http://www.opengis.net/ont/geosparql#
exact_mappings:
- http://www.opengis.net/ont/geosparql#defaultGeometry
domain: geo_Feature
slot_uri: geo:hasDefaultGeometry
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Site
- http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
- me_egad_EGAD-PFAS-Site
- me_egad_EGAD-SamplePoint
subproperty_of: geo_hasGeometry
range: geo_Geometry

```
</details>