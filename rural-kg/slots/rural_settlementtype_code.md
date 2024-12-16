

# Slot: rural_settlementtype_code


_No slot (predicate) description specified_





URI: [rural:settlementtype/code](http://sail.ua.edu/ruralkg/settlementtype/code)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSettlementtypeRUCC](../classes/RuralSettlementtypeRUCC.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_settlementtype_RUCC → string | rural:settlementtype/RUCC_2013_0 | rural:settlementtype/code | 0 |


## Comments

* 10 occurrences with subject type rural_settlementtype_RUCC and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:settlementtype/code |
| native | rural-kg/:rural_settlementtype_code |




## LinkML Source

<details>
```yaml
name: rural_settlementtype_code
description: No slot (predicate) description specified
comments:
- 10 occurrences with subject type rural_settlementtype_RUCC and object type string.
examples:
- description: rural_settlementtype_RUCC → string
  object:
    example_object: '0'
    example_predicate: rural:settlementtype/code
    example_subject: rural:settlementtype/RUCC_2013_0
from_schema: rural-kg
rank: 1000
slot_uri: rural:settlementtype/code
alias: rural_settlementtype_code
domain_of:
- rural_settlementtype_RUCC
range: string

```
</details>