

# Class: TODO -- what's a good name for this class (type)? (ilisgs_WellDepthInFt)


_No type description provided_





URI: [ilisgs:WellDepthInFt](http://sawgraph.spatialai.org/v1/il-isgs#WellDepthInFt)






```mermaid
 classDiagram
    class IlisgsWellDepthInFt
    click IlisgsWellDepthInFt href "../IlisgsWellDepthInFt"
      HttpSawgraph.spatialai.orgV1Stad#SingleData <|-- IlisgsWellDepthInFt
        click HttpSawgraph.spatialai.orgV1Stad#SingleData href "../HttpSawgraph.spatialai.orgV1Stad#SingleData"
      
      IlisgsWellDepthInFt : https___qudt.org_schema_qudt_numericValue
        
          
    
    
    IlisgsWellDepthInFt --> "0..1" Float : https___qudt.org_schema_qudt_numericValue
    click Float href "../Float"

        
      IlisgsWellDepthInFt : https___qudt.org_schema_qudt_unit
        
          
    
    
    IlisgsWellDepthInFt --> "0..1" Uri : https___qudt.org_schema_qudt_unit
    click Uri href "../Uri"

        
      
```





## Inheritance
* [HttpSawgraph.spatialai.orgV1Stad#Quantity](../classes/HttpSawgraph.spatialai.orgV1Stad#Quantity.md)
    * [HttpSawgraph.spatialai.orgV1Stad#SingleData](../classes/HttpSawgraph.spatialai.orgV1Stad#SingleData.md)
        * **IlisgsWellDepthInFt**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [https___qudt.org_schema_qudt_numericValue](../slots/https___qudt.org_schema_qudt_numericValue.md) | 0..1 <br/> [xsd:float](http://www.w3.org/2001/XMLSchema#float) | No slot description provided | direct |
| [https___qudt.org_schema_qudt_unit](../slots/https___qudt.org_schema_qudt_unit.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot description provided | [HttpSawgraph.spatialai.orgV1Stad#Quantity](../classes/HttpSawgraph.spatialai.orgV1Stad#Quantity.md) |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ContaminosoFeature](../classes/ContaminosoFeature.md) | [ilisgs_wellDepth](../slots/ilisgs_wellDepth.md) | range | [IlisgsWellDepthInFt](../classes/IlisgsWellDepthInFt.md) |






## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sawgraph-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | ilisgs:WellDepthInFt |
| native | sawgraph-kg/:IlisgsWellDepthInFt |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: ilisgs_WellDepthInFt
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 376687 occurences.
from_schema: sawgraph-kg
rank: 1000
is_a: http___sawgraph.spatialai.org_v1_stad#SingleData
slots:
- https___qudt.org_schema_qudt_numericValue
class_uri: ilisgs:WellDepthInFt

```
</details>

### Induced

<details>
```yaml
name: ilisgs_WellDepthInFt
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 376687 occurences.
from_schema: sawgraph-kg
rank: 1000
is_a: http___sawgraph.spatialai.org_v1_stad#SingleData
attributes:
  https___qudt.org_schema_qudt_numericValue:
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
    owner: ilisgs_WellDepthInFt
    domain_of:
    - http___sawgraph.spatialai.org_v1_stad#Quantity
    - ilisgs_WellDepthInFt
    - ilisgs_WellYield
    - ussdwis_Amount
    range: float
  https___qudt.org_schema_qudt_unit:
    name: https___qudt.org_schema_qudt_unit
    description: No slot description provided
    title: No slot description provided
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
    owner: ilisgs_WellDepthInFt
    domain_of:
    - http___sawgraph.spatialai.org_v1_stad#Quantity
    - ilisgs_WellYield
    - ussdwis_Amount
    range: uri
class_uri: ilisgs:WellDepthInFt

```
</details>