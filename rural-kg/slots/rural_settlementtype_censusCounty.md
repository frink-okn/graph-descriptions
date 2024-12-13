

# Slot: rural_settlementtype_censusCounty


_No slot description provided_





URI: [rural:settlementtype/censusCounty](http://sail.ua.edu/ruralkg/settlementtype/censusCounty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSettlementtypeCountyStatus](../classes/RuralSettlementtypeCountyStatus.md) | Status of a county in terms of rural or urban classification |  no  |







## Properties

* Range: [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None |  |  |  |


## Comments

* 3234 occurrences with subject type rural_settlementtype_CountyStatus and object type rural_administrativearea_County.

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
| self | rural:settlementtype/censusCounty |
| native | rural-kg/:rural_settlementtype_censusCounty |




## LinkML Source

<details>
```yaml
name: rural_settlementtype_censusCounty
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 3234 occurrences with subject type rural_settlementtype_CountyStatus and object
  type rural_administrativearea_County.
examples:
- value: rural:settlementtype/CountyStatus_28135_2013 rural:settlementtype/censusCounty
    rural:administrativearea/County_28135
from_schema: rural-kg
rank: 1000
slot_uri: rural:settlementtype/censusCounty
alias: rural_settlementtype_censusCounty
domain_of:
- rural_settlementtype_CountyStatus
range: rural_administrativearea_County

```
</details>