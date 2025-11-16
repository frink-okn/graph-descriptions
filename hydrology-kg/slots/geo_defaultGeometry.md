

# Slot: geo_defaultGeometry


_The default Geometry to be used in spatial calculations. It is usually the most detailed Geometry._






This slot occurs 517868 times.


URI: [geo:defaultGeometry](http://www.opengis.net/ont/geosparql#defaultGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md) |  |  no  |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |  |  no  |
| [B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md) |  |  no  |
| [HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md) |  |  no  |







## Properties

* Range: [GeoGeometry](../classes/GeoGeometry.md)





## Comments

* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties
* source: http://www.opengis.net/ont/geosparql#
* description: The default Geometry to be used in spatial calculations. It is usually the most detailed Geometry.



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
- No occurrences of this slot in the graph.
comments:
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
- 'source: http://www.opengis.net/ont/geosparql#'
- 'description: The default Geometry to be used in spatial calculations. It is usually
  the most detailed Geometry.'
from_schema: okns:geo
source: http://www.opengis.net/ont/geosparql#
exact_mappings:
- http://www.opengis.net/ont/geosparql#hasDefaultGeometry
domain: geo_Feature
slot_uri: geo:defaultGeometry
domain_of:
- __B805a9e7d30eaabcb686b8ce670ed1e95
- http___gwml2.org_def_gwml2#GW_Aquifer
- http___gwml2.org_def_gwml2#GW_AquiferSystem
- hyf_HY_ElementaryFlowPath
subproperty_of: geo_hasGeometry
range: geo_Geometry

```
</details>