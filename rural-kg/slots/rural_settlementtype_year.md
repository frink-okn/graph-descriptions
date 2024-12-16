

# Slot: rural_settlementtype_year


_No slot (predicate) description specified_





URI: [rural:settlementtype/year](http://sail.ua.edu/ruralkg/settlementtype/year)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSettlementtypeRUCC](../classes/RuralSettlementtypeRUCC.md) | No class (type) description specified |  no  |
| [RuralSettlementtypeCountyStatus](../classes/RuralSettlementtypeCountyStatus.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:integer](xsd:integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_settlementtype_RUCC → integer | rural:settlementtype/RUCC_2013_0 | rural:settlementtype/year | 2013 |
| rural_settlementtype_CountyStatus → integer | rural:settlementtype/CountyStatus_01001_2013 | rural:settlementtype/year | 2013 |


## Comments

* 10 occurrences with subject type rural_settlementtype_RUCC and object type integer.
* 3234 occurrences with subject type rural_settlementtype_CountyStatus and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:settlementtype/year |
| native | rural-kg/:rural_settlementtype_year |




## LinkML Source

<details>
```yaml
name: rural_settlementtype_year
description: No slot (predicate) description specified
comments:
- 10 occurrences with subject type rural_settlementtype_RUCC and object type integer.
- 3234 occurrences with subject type rural_settlementtype_CountyStatus and object
  type integer.
examples:
- description: rural_settlementtype_RUCC → integer
  object:
    example_object: '2013'
    example_predicate: rural:settlementtype/year
    example_subject: rural:settlementtype/RUCC_2013_0
- description: rural_settlementtype_CountyStatus → integer
  object:
    example_object: '2013'
    example_predicate: rural:settlementtype/year
    example_subject: rural:settlementtype/CountyStatus_01001_2013
from_schema: rural-kg
rank: 1000
slot_uri: rural:settlementtype/year
alias: rural_settlementtype_year
domain_of:
- rural_settlementtype_CountyStatus
- rural_settlementtype_RUCC
range: integer

```
</details>