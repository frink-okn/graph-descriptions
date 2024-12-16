

# Slot: rural_settlementtype_population


_No slot (predicate) description specified_





URI: [rural:settlementtype/population](http://sail.ua.edu/ruralkg/settlementtype/population)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSettlementtypeCountyStatus](../classes/RuralSettlementtypeCountyStatus.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:integer](xsd:integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_settlementtype_CountyStatus → integer | rural:settlementtype/CountyStatus_01001_2013 | rural:settlementtype/population | 54571 |


## Comments

* 3234 occurrences with subject type rural_settlementtype_CountyStatus and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:settlementtype/population |
| native | rural-kg/:rural_settlementtype_population |




## LinkML Source

<details>
```yaml
name: rural_settlementtype_population
description: No slot (predicate) description specified
comments:
- 3234 occurrences with subject type rural_settlementtype_CountyStatus and object
  type integer.
examples:
- description: rural_settlementtype_CountyStatus → integer
  object:
    example_object: '54571'
    example_predicate: rural:settlementtype/population
    example_subject: rural:settlementtype/CountyStatus_01001_2013
from_schema: rural-kg
rank: 1000
slot_uri: rural:settlementtype/population
alias: rural_settlementtype_population
domain_of:
- rural_settlementtype_CountyStatus
range: integer

```
</details>