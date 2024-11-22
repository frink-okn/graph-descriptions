

# Slot: rural_settlementtype_year


_TODO -- tell the world what this slot (predicate) describes._





URI: [rural:settlementtype/year](http://sail.ua.edu/ruralkg/settlementtype/year)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSettlementtypeRUCC](../classes/RuralSettlementtypeRUCC.md) | Rural-Urban Continuum Code classification |  no  |
| [RuralSettlementtypeCountyStatus](../classes/RuralSettlementtypeCountyStatus.md) | Status of a county in terms of rural or urban classification |  no  |







## Properties

* Range: [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Value |
| --- |
| rural:settlementtype/CountyStatus_46019_2013 rural:settlementtype/year 2013 |
| rural:settlementtype/RUCC_2013_5 rural:settlementtype/year 2013 |

## Comments

* 3234 occurrences with subject type rural_settlementtype_CountyStatus and object type integer.
* 10 occurrences with subject type rural_settlementtype_RUCC and object type integer.

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
| self | rural:settlementtype/year |
| native | rural-kg/:rural_settlementtype_year |




## LinkML Source

<details>
```yaml
name: rural_settlementtype_year
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 3234 occurrences with subject type rural_settlementtype_CountyStatus and object
  type integer.
- 10 occurrences with subject type rural_settlementtype_RUCC and object type integer.
examples:
- value: rural:settlementtype/CountyStatus_46019_2013 rural:settlementtype/year 2013
- value: rural:settlementtype/RUCC_2013_5 rural:settlementtype/year 2013
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