

# Slot: rural_settlementtype_description


_No slot description provided_





URI: [rural:settlementtype/description](http://sail.ua.edu/ruralkg/settlementtype/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSettlementtypeRUCC](../classes/RuralSettlementtypeRUCC.md) | Rural-Urban Continuum Code classification |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| rural:settlementtype/RUCC_2013_9 rural:settlementtype/description Nonmetro - Completely rural or less than 2,500 urban population, not adjacent to a metro area |

## Comments

* 10 occurrences with subject type rural_settlementtype_RUCC and object type string.

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
| self | rural:settlementtype/description |
| native | rural-kg/:rural_settlementtype_description |




## LinkML Source

<details>
```yaml
name: rural_settlementtype_description
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 10 occurrences with subject type rural_settlementtype_RUCC and object type string.
examples:
- value: rural:settlementtype/RUCC_2013_9 rural:settlementtype/description Nonmetro
    - Completely rural or less than 2,500 urban population, not adjacent to a metro
    area
from_schema: rural-kg
rank: 1000
slot_uri: rural:settlementtype/description
alias: rural_settlementtype_description
domain_of:
- rural_settlementtype_RUCC
range: string

```
</details>