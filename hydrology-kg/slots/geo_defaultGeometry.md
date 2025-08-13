

# Slot: geo_defaultGeometry


_The default Geometry to be used in spatial calculations. It is usually the most detailed Geometry._






This slot occurs 517868 times.


URI: [geo:defaultGeometry](http://www.opengis.net/ont/geosparql#defaultGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HyfHYEstuary](../classes/HyfHYEstuary.md) |  |  no  |
| [HyfHYCanal](../classes/HyfHYCanal.md) |  |  no  |
| [HyfHYWaterBody](../classes/HyfHYWaterBody.md) |  |  no  |
| [HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md) |  |  no  |
| [HyfHYLagoon](../classes/HyfHYLagoon.md) |  |  no  |
| [HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md) |  |  no  |
| [HyfHYRiver](../classes/HyfHYRiver.md) |  |  no  |
| [HyfHYImpoundment](../classes/HyfHYImpoundment.md) |  |  no  |
| [HyfHYLake](../classes/HyfHYLake.md) |  |  no  |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |  |  no  |







## Properties

* Range: [GeoGeometry](../classes/GeoGeometry.md)





## Comments

* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties
* source: http://www.opengis.net/ont/geosparql#
* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties
* description: The default Geometry to be used in spatial calculations. It is usually the most detailed Geometry.
* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: geo_defaultGeometry
description: The default Geometry to be used in spatial calculations. It is usually
  the most detailed Geometry.
notes:
- Duplicate properties defaultGeometry and hasDefaultGeometry exist because of an
  inconsistency between ontology and documentation in GeoSPARQL 1.0. Only hasDefaultGeometry
  is described in the documention.
comments:
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
- 'source: http://www.opengis.net/ont/geosparql#'
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
- 'description: The default Geometry to be used in spatial calculations. It is usually
  the most detailed Geometry.'
- No occurrences of this slot in the graph.
from_schema: okns:geo
source: http://www.opengis.net/ont/geosparql#
exact_mappings:
- http://www.opengis.net/ont/geosparql#hasDefaultGeometry
domain: geo_Feature
slot_uri: geo:defaultGeometry
domain_of:
- http___gwml2.org_def_gwml2#GW_Aquifer
- http___gwml2.org_def_gwml2#GW_AquiferSystem
- hyf__HY_ElementaryFlowPath
- hyf__HY_Lake
- hyf__HY_WaterBody
subproperty_of: geo_hasGeometry
range: geo_Geometry

```
</details>