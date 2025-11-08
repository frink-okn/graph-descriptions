

# Slot: No slot (predicate) name specified -- this slot is noted as a subproperty of another slot in this graph but has not itself been defined. (geo_hasGeometry)


_A spatial representation for a given Feature._






This slot occurs 13107 times.


URI: [geo:hasGeometry](http://www.opengis.net/ont/geosparql#hasGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site.md) |  |  no  |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Us-wqp#Site](../classes/HttpW3id.orgSawgraphV1Us-wqp#Site.md) |  |  no  |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) |  |  no  |







## Properties

* Range: [GeoGeometry](../classes/GeoGeometry.md)





## Comments

* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties
* source: http://www.opengis.net/ont/geosparql#
* source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties
* description: A spatial representation for a given Feature.



## LinkML Source

<details>

```yaml
name: geo_hasGeometry
description: A spatial representation for a given Feature.
title: No slot (predicate) name specified -- this slot is noted as a subproperty of
  another slot in this graph but has not itself been defined.
notes:
- No occurrences of this slot in the graph.
comments:
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
- 'source: http://www.opengis.net/ont/geosparql#'
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties'
- 'description: A spatial representation for a given Feature.'
from_schema: okns:geo
source: http://www.opengis.net/ont/geosparql#
domain: geo_Feature
slot_uri: geo:hasGeometry
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Site
- http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
- http___w3id.org_sawgraph_v1_us-wqp#Site
- me_egad_EGAD-PFAS-Site
- me_egad_EGAD-SamplePoint
range: geo_Geometry

```
</details>