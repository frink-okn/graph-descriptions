

# Slot: rural_settlementtype_hasRUCC


_No slot (predicate) description specified_





URI: [rural:settlementtype/hasRUCC](http://sail.ua.edu/ruralkg/settlementtype/hasRUCC)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSettlementtypeCountyStatus](../classes/RuralSettlementtypeCountyStatus.md) | No class (type) description specified |  no  |







## Properties

* Range: [RuralSettlementtypeRUCC](../classes/RuralSettlementtypeRUCC.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_settlementtype_CountyStatus → rural_settlementtype_RUCC | rural:settlementtype/CountyStatus_78030_2013 | rural:settlementtype/hasRUCC | rural:settlementtype/RUCC_2013_5 |


## Comments

* 3234 occurrences with subject type rural_settlementtype_CountyStatus and object type rural_settlementtype_RUCC.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:settlementtype/hasRUCC |
| native | rural-kg/:rural_settlementtype_hasRUCC |




## LinkML Source

<details>
```yaml
name: rural_settlementtype_hasRUCC
description: No slot (predicate) description specified
comments:
- 3234 occurrences with subject type rural_settlementtype_CountyStatus and object
  type rural_settlementtype_RUCC.
examples:
- description: rural_settlementtype_CountyStatus → rural_settlementtype_RUCC
  object:
    example_object: rural:settlementtype/RUCC_2013_5
    example_predicate: rural:settlementtype/hasRUCC
    example_subject: rural:settlementtype/CountyStatus_78030_2013
from_schema: rural-kg
rank: 1000
slot_uri: rural:settlementtype/hasRUCC
alias: rural_settlementtype_hasRUCC
domain_of:
- rural_settlementtype_CountyStatus
range: rural_settlementtype_RUCC

```
</details>