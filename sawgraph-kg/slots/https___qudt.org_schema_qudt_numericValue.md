

# Slot: No slot description provided (https___qudt.org_schema_qudt_numericValue)


_No slot description provided_





URI: [https://qudt.org/schema/qudt/numericValue](https://qudt.org/schema/qudt/numericValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpSawgraph.spatialai.orgV1Us-epa-ghg#Amount](../classes/HttpSawgraph.spatialai.orgV1Us-epa-ghg#Amount.md) | No type description provided |  no  |
| [HttpSawgraph.spatialai.orgV1Stad#StatisticalAggregateData](../classes/HttpSawgraph.spatialai.orgV1Stad#StatisticalAggregateData.md) | No type description provided |  no  |
| [MemgsWellDepthInFt](../classes/MemgsWellDepthInFt.md) | No type description provided |  no  |
| [HttpSawgraph.spatialai.orgV1Stad#SingleData](../classes/HttpSawgraph.spatialai.orgV1Stad#SingleData.md) | No type description provided |  no  |
| [UssdwisAmount](../classes/UssdwisAmount.md) | No type description provided |  no  |
| [IlisgsWellYield](../classes/IlisgsWellYield.md) | No type description provided |  no  |
| [HttpSawgraph.spatialai.orgV1Stad#Quantity](../classes/HttpSawgraph.spatialai.orgV1Stad#Quantity.md) | No type description provided |  no  |
| [IlisgsWellDepthInFt](../classes/IlisgsWellDepthInFt.md) | No type description provided |  no  |
| [MemgsWellOverburdenThicknessInFt](../classes/MemgsWellOverburdenThicknessInFt.md) | No type description provided |  no  |







## Properties

* Range: [xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.Depth.120010000300 https://qudt.org/schema/qudt/numericValue 20.0 |
| http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.Yield.120010000300 https://qudt.org/schema/qudt/numericValue 0.0 |
| http://sawgraph.spatialai.org/v1/us-epa-ghg#d.Amount.GHGFacility-1006665.Year-2011.Chemical-2_2_3_3_4-PENTAFLUORO-4-_TRIFLUOROMETHYL_-OXETANE.Chemical-2_2_3_3_4-PENTAFLUORO-4-_TRIFLUOROMETHYL_-OXETANE https://qudt.org/schema/qudt/numericValue 0.311139058 |
| http://sawgraph.spatialai.org/v1/us-sdwis-data#d.Amount.ME0000185.Sample-04262022.Chemical-PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA https://qudt.org/schema/qudt/numericValue 49.14 |

## Comments

* 376687 occurrences with subject type ilisgs_WellDepthInFt and object type float.
* 265368 occurrences with subject type ilisgs_WellYield and object type float.
* 733 occurrences with subject type http___sawgraph.spatialai.org_v1_stad#Quantity and object type float.
* 22 occurrences with subject type ussdwis_Amount and object type float.

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
| self | https://qudt.org/schema/qudt/numericValue |
| native | sawgraph-kg/:https___qudt.org_schema_qudt_numericValue |




## LinkML Source

<details>
```yaml
name: https___qudt.org_schema_qudt_numericValue
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 376687 occurrences with subject type ilisgs_WellDepthInFt and object type float.
- 265368 occurrences with subject type ilisgs_WellYield and object type float.
- 733 occurrences with subject type http___sawgraph.spatialai.org_v1_stad#Quantity
  and object type float.
- 22 occurrences with subject type ussdwis_Amount and object type float.
examples:
- value: http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.Depth.120010000300
    https://qudt.org/schema/qudt/numericValue 20.0
- value: http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.Yield.120010000300
    https://qudt.org/schema/qudt/numericValue 0.0
- value: http://sawgraph.spatialai.org/v1/us-epa-ghg#d.Amount.GHGFacility-1006665.Year-2011.Chemical-2_2_3_3_4-PENTAFLUORO-4-_TRIFLUOROMETHYL_-OXETANE.Chemical-2_2_3_3_4-PENTAFLUORO-4-_TRIFLUOROMETHYL_-OXETANE
    https://qudt.org/schema/qudt/numericValue 0.311139058
- value: http://sawgraph.spatialai.org/v1/us-sdwis-data#d.Amount.ME0000185.Sample-04262022.Chemical-PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
    https://qudt.org/schema/qudt/numericValue 49.14
from_schema: sawgraph-kg
rank: 1000
slot_uri: https://qudt.org/schema/qudt/numericValue
alias: https___qudt.org_schema_qudt_numericValue
domain_of:
- http___sawgraph.spatialai.org_v1_stad#Quantity
- ilisgs_WellDepthInFt
- ilisgs_WellYield
- ussdwis_Amount
range: float

```
</details>