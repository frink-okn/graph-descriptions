

# Slot: sockg_stateFIPS


_No slot (predicate) description specified_






This slot occurs 18 times.


URI: [sockg:stateFIPS](https://idir.uta.edu/sockg-ontology/docs/stateFIPS)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgState](../classes/SockgState.md) | A State represents a regional jurisdiction within a country, often defined by... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_State | string | sockg:individuals/336400 | administrativeRegion.USA.1 | 18 |




## LinkML Source

<details>

```yaml
name: sockg_stateFIPS
annotations:
  count:
    tag: count
    value: 18
description: No slot (predicate) description specified
examples:
- object:
    example_object: administrativeRegion.USA.1
    example_object_type: string
    example_predicate: sockg:stateFIPS
    example_subject: sockg:individuals/336400
    example_subject_type: sockg_State
from_schema: soc-kg
rank: 1000
slot_uri: sockg:stateFIPS
alias: sockg_stateFIPS
domain_of:
- sockg_State
range: string

```
</details>