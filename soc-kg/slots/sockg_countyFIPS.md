

# Slot: sockg_countyFIPS


_No slot (predicate) description specified_






This slot occurs 31 times.


URI: [sockg:countyFIPS](https://idir.uta.edu/sockg-ontology/docs/countyFIPS)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgCounty](../classes/SockgCounty.md) | A County represents a specific geographical area within a state, often encomp... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_County | string | sockg:individuals/46904 | administrativeRegion.USA.1087 | 31 |




## LinkML Source

<details>

```yaml
name: sockg_countyFIPS
annotations:
  count:
    tag: count
    value: 31
description: No slot (predicate) description specified
examples:
- object:
    example_object: administrativeRegion.USA.1087
    example_object_type: string
    example_predicate: sockg:countyFIPS
    example_subject: sockg:individuals/46904
    example_subject_type: sockg_County
from_schema: soc-kg
rank: 1000
slot_uri: sockg:countyFIPS
alias: sockg_countyFIPS
domain_of:
- sockg_County
range: string

```
</details>