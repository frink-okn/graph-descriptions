

# Slot: rural_settlementtype_population


_TODO -- tell the world what this slot (predicate) describes._





URI: [rural:settlementtype/population](http://sail.ua.edu/ruralkg/settlementtype/population)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSettlementtypeCountyStatus](../classes/RuralSettlementtypeCountyStatus.md) | Status of a county in terms of rural or urban classification |  no  |







## Properties

* Range: [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Value |
| --- |
| rural:settlementtype/CountyStatus_36089_2013 rural:settlementtype/population 111944 |

## Comments

* 3234 occurrences with subject type rural_settlementtype_CountyStatus and object type integer.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

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
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 3234 occurrences with subject type rural_settlementtype_CountyStatus and object
  type integer.
examples:
- value: rural:settlementtype/CountyStatus_36089_2013 rural:settlementtype/population
    111944
from_schema: rural-kg
rank: 1000
slot_uri: rural:settlementtype/population
alias: rural_settlementtype_population
domain_of:
- rural_settlementtype_CountyStatus
range: integer

```
</details>