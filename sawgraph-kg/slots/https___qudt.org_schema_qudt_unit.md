

# Slot: TODO -- tell the world what this slot (predicate) describes. (https___qudt.org_schema_qudt_unit)


_TODO -- tell the world what this slot (predicate) describes._





URI: [https://qudt.org/schema/qudt/unit](https://qudt.org/schema/qudt/unit)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpSawgraph.spatialai.orgV1Stad#StatisticalAggregateData](../classes/HttpSawgraph.spatialai.orgV1Stad#StatisticalAggregateData.md) | TODO -- tell the world what this class (type) describes |  no  |
| [HttpSawgraph.spatialai.orgV1Us-epa-ghg#Amount](../classes/HttpSawgraph.spatialai.orgV1Us-epa-ghg#Amount.md) | TODO -- tell the world what this class (type) describes |  no  |
| [HttpSawgraph.spatialai.orgV1Stad#Quantity](../classes/HttpSawgraph.spatialai.orgV1Stad#Quantity.md) | TODO -- tell the world what this class (type) describes |  no  |
| [IlisgsWellYield](../classes/IlisgsWellYield.md) | TODO -- tell the world what this class (type) describes |  no  |
| [IlisgsWellDepthInFt](../classes/IlisgsWellDepthInFt.md) | TODO -- tell the world what this class (type) describes |  no  |
| [MemgsWellOverburdenThicknessInFt](../classes/MemgsWellOverburdenThicknessInFt.md) | TODO -- tell the world what this class (type) describes |  no  |
| [UssdwisAmount](../classes/UssdwisAmount.md) | TODO -- tell the world what this class (type) describes |  no  |
| [MemgsWellDepthInFt](../classes/MemgsWellDepthInFt.md) | TODO -- tell the world what this class (type) describes |  no  |
| [HttpSawgraph.spatialai.orgV1Stad#SingleData](../classes/HttpSawgraph.spatialai.orgV1Stad#SingleData.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.Yield.120010000300 https://qudt.org/schema/qudt/unit https://qudt.org/vocab/unit/GAL_US-PER-MIN |
| http://sawgraph.spatialai.org/v1/us-epa-ghg#d.Amount.GHGFacility-1006665.Year-2011.Chemical-2_2_3_3_4-PENTAFLUORO-4-_TRIFLUOROMETHYL_-OXETANE.Chemical-2_2_3_3_4-PENTAFLUORO-4-_TRIFLUOROMETHYL_-OXETANE https://qudt.org/schema/qudt/unit https://qudt.org/schema/qudt/TON_Metric |
| http://sawgraph.spatialai.org/v1/us-sdwis-data#d.Amount.ME0000185.Sample-04262022.Chemical-PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA https://qudt.org/schema/qudt/unit https://qudt.org/schema/qudt/NanoGM-PER-L |

## Comments

* 265368 occurrences with subject type ilisgs_WellYield and object type uri.
* 733 occurrences with subject type http___sawgraph.spatialai.org_v1_stad#Quantity and object type uri.
* 21 occurrences with subject type ussdwis_Amount and object type uri.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sawgraph-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | https://qudt.org/schema/qudt/unit |
| native | sawgraph-kg/:https___qudt.org_schema_qudt_unit |




## LinkML Source

<details>
```yaml
name: https___qudt.org_schema_qudt_unit
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 265368 occurrences with subject type ilisgs_WellYield and object type uri.
- 733 occurrences with subject type http___sawgraph.spatialai.org_v1_stad#Quantity
  and object type uri.
- 21 occurrences with subject type ussdwis_Amount and object type uri.
examples:
- value: http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.Yield.120010000300
    https://qudt.org/schema/qudt/unit https://qudt.org/vocab/unit/GAL_US-PER-MIN
- value: http://sawgraph.spatialai.org/v1/us-epa-ghg#d.Amount.GHGFacility-1006665.Year-2011.Chemical-2_2_3_3_4-PENTAFLUORO-4-_TRIFLUOROMETHYL_-OXETANE.Chemical-2_2_3_3_4-PENTAFLUORO-4-_TRIFLUOROMETHYL_-OXETANE
    https://qudt.org/schema/qudt/unit https://qudt.org/schema/qudt/TON_Metric
- value: http://sawgraph.spatialai.org/v1/us-sdwis-data#d.Amount.ME0000185.Sample-04262022.Chemical-PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
    https://qudt.org/schema/qudt/unit https://qudt.org/schema/qudt/NanoGM-PER-L
from_schema: sawgraph-kg
rank: 1000
slot_uri: https://qudt.org/schema/qudt/unit
alias: https___qudt.org_schema_qudt_unit
domain_of:
- http___sawgraph.spatialai.org_v1_stad#Quantity
- ilisgs_WellYield
- ussdwis_Amount
range: uri

```
</details>