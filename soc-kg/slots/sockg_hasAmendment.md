

# Slot: No slot (predicate) name specified (sockg_hasAmendment)


_No slot (predicate) description specified_






This slot occurs 37796 times.


URI: [sockg:hasAmendment](https://idir.uta.edu/sockg-ontology/docs/hasAmendment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |







## Properties

* Range: [SockgAmendment](../classes/SockgAmendment.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ExperimentalUnit | sockg_Amendment | sockg:individuals/51937 | sockg:individuals/15592 | 37796 |




## LinkML Source

<details>

```yaml
name: sockg_hasAmendment
annotations:
  count:
    tag: count
    value: 37796
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/15592
    example_object_type: sockg_Amendment
    example_predicate: sockg:hasAmendment
    example_subject: sockg:individuals/51937
    example_subject_type: sockg_ExperimentalUnit
from_schema: soc-kg
rank: 1000
domain: sockg_ExperimentalUnit
slot_uri: sockg:hasAmendment
alias: sockg_hasAmendment
domain_of:
- sockg_ExperimentalUnit
range: sockg_Amendment

```
</details>