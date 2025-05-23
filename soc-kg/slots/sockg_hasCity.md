

# Slot: No slot (predicate) name specified (sockg_hasCity)


_No slot (predicate) description specified_






This slot occurs 33 times.


URI: [sockg:hasCity](https://idir.uta.edu/sockg-ontology/docs/hasCity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgCounty](../classes/SockgCounty.md) | A County represents a specific geographical area within a state, often encomp... |  yes  |







## Properties

* Range: [SockgCity](../classes/SockgCity.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_County | sockg_City | sockg:individuals/46904 | sockg:individuals/46864 | 33 |




## LinkML Source

<details>

```yaml
name: sockg_hasCity
annotations:
  count:
    tag: count
    value: 33
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/46864
    example_object_type: sockg_City
    example_predicate: sockg:hasCity
    example_subject: sockg:individuals/46904
    example_subject_type: sockg_County
from_schema: soc-kg
rank: 1000
domain: sockg_County
slot_uri: sockg:hasCity
alias: sockg_hasCity
domain_of:
- sockg_County
range: sockg_City

```
</details>