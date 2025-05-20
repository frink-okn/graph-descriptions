

# Slot: No slot (predicate) name specified (sockg_locatedInField)


_No slot (predicate) description specified_






This slot occurs 3809 times.


URI: [sockg:locatedInField](https://idir.uta.edu/sockg-ontology/docs/locatedInField)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |







## Properties

* Range: [SockgField](../classes/SockgField.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ExperimentalUnit | sockg_Field | sockg:individuals/51937 | sockg:individuals/55816 | 3809 |




## LinkML Source

<details>

```yaml
name: sockg_locatedInField
annotations:
  count:
    tag: count
    value: 3809
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/55816
    example_object_type: sockg_Field
    example_predicate: sockg:locatedInField
    example_subject: sockg:individuals/51937
    example_subject_type: sockg_ExperimentalUnit
from_schema: soc-kg
rank: 1000
domain: sockg_ExperimentalUnit
slot_uri: sockg:locatedInField
alias: sockg_locatedInField
domain_of:
- sockg_ExperimentalUnit
range: sockg_Field

```
</details>