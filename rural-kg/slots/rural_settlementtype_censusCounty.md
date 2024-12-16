

# Slot: rural_settlementtype_censusCounty


_No slot (predicate) description specified_





URI: [rural:settlementtype/censusCounty](http://sail.ua.edu/ruralkg/settlementtype/censusCounty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSettlementtypeCountyStatus](../classes/RuralSettlementtypeCountyStatus.md) | No class (type) description specified |  no  |







## Properties

* Range: [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_settlementtype_CountyStatus → rural_administrativearea_County | rural:settlementtype/CountyStatus_78030_2013 | rural:settlementtype/censusCounty | rural:administrativearea/County_78030 |


## Comments

* 3234 occurrences with subject type rural_settlementtype_CountyStatus and object type rural_administrativearea_County.

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
description: No slot (predicate) description specified
comments:
- 3234 occurrences with subject type rural_settlementtype_CountyStatus and object
  type rural_administrativearea_County.
examples:
- description: rural_settlementtype_CountyStatus → rural_administrativearea_County
  object:
    example_object: rural:administrativearea/County_78030
    example_predicate: rural:settlementtype/censusCounty
    example_subject: rural:settlementtype/CountyStatus_78030_2013
from_schema: rural-kg
rank: 1000
slot_uri: rural:settlementtype/censusCounty
alias: rural_settlementtype_censusCounty
domain_of:
- rural_settlementtype_CountyStatus
range: rural_administrativearea_County

```
</details>