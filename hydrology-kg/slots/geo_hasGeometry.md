

# Slot: No slot (predicate) name specified -- this slot is noted as a subproperty of another slot in this graph but has not itself been defined. (geo_hasGeometry)


_A spatial representation for a given Feature._






This slot occurs 980710 times.


URI: [geo:hasGeometry](http://www.opengis.net/ont/geosparql#hasGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md) |  |  no  |
| [B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md) |  |  no  |
| [HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md) |  |  no  |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) |  |  no  |
| [UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md) |  |  no  |
| [IlIsgsISGS-Well](../classes/IlIsgsISGS-Well.md) |  |  no  |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |  |  no  |







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
- __B805a9e7d30eaabcb686b8ce670ed1e95
- http___gwml2.org_def_gwml2#GW_Aquifer
- http___gwml2.org_def_gwml2#GW_AquiferSystem
- hyf_HY_ElementaryFlowPath
- il_isgs_ISGS-Well
- me_mgs_MGS-Well
- us_sdwis_PWS-ServiceArea
range: geo_Geometry

```
</details>