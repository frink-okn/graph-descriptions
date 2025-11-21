

# Slot: No slot (predicate) name specified -- this slot is noted as a subproperty of another slot in this graph but has not itself been defined. (geo_hasGeometry)


_A spatial representation for a given Feature._






This slot occurs 762584 times.


URI: [geo:hasGeometry](http://www.opengis.net/ont/geosparql#hasGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |







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
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
range: geo_Geometry

```
</details>