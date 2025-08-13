

# Slot: No slot (predicate) name specified -- this slot is noted as a subproperty of another slot in this graph but has not itself been defined. (geo_hasGeometry)


_A spatial representation for a given Feature._






This slot occurs 980710 times.


URI: [geo:hasGeometry](http://www.opengis.net/ont/geosparql#hasGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HyfHYEstuary](../classes/HyfHYEstuary.md) |  |  no  |
| [HyfHYCanal](../classes/HyfHYCanal.md) |  |  no  |
| [HyfHYWaterBody](../classes/HyfHYWaterBody.md) |  |  no  |
| [HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md) |  |  no  |
| [UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md) |  |  no  |
| [HyfHYLagoon](../classes/HyfHYLagoon.md) |  |  no  |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) |  |  no  |
| [HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md) |  |  no  |
| [IlIsgsISGS-Well](../classes/IlIsgsISGS-Well.md) |  |  no  |
| [HyfHYRiver](../classes/HyfHYRiver.md) |  |  no  |
| [HyfHYImpoundment](../classes/HyfHYImpoundment.md) |  |  no  |
| [HyfHYLake](../classes/HyfHYLake.md) |  |  no  |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |  |  no  |







## Properties

* Range: [GeoGeometry](../classes/GeoGeometry.md)





## Comments

* source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties
* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties
* source: http://www.opengis.net/ont/geosparql#
* source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties
* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties
* description: A spatial representation for a given Feature.
* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: geo_hasGeometry
description: A spatial representation for a given Feature.
title: No slot (predicate) name specified -- this slot is noted as a subproperty of
  another slot in this graph but has not itself been defined.
comments:
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties'
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
- 'source: http://www.opengis.net/ont/geosparql#'
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/feature-properties'
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/feature-properties'
- 'description: A spatial representation for a given Feature.'
- No occurrences of this slot in the graph.
from_schema: okns:geo
source: http://www.opengis.net/ont/geosparql#
domain: geo_Feature
slot_uri: geo:hasGeometry
domain_of:
- http___gwml2.org_def_gwml2#GW_Aquifer
- http___gwml2.org_def_gwml2#GW_AquiferSystem
- hyf__HY_ElementaryFlowPath
- hyf__HY_Lake
- hyf__HY_WaterBody
- il_isgs_ISGS-Well
- me_mgs_MGS-Well
- us_sdwis_PWS-ServiceArea
range: geo_Geometry

```
</details>