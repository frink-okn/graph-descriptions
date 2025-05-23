

# Slot: No slot (predicate) name specified (sockg_hasBioSample)


_No slot (predicate) description specified_






This slot occurs 18222 times.


URI: [sockg:hasBioSample](https://idir.uta.edu/sockg-ontology/docs/hasBioSample)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |







## Properties

* Range: [SockgSoilBiologicalSample](../classes/SockgSoilBiologicalSample.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ExperimentalUnit | sockg_SoilBiologicalSample | sockg:individuals/51968 | sockg:individuals/246851 | 18222 |




## LinkML Source

<details>

```yaml
name: sockg_hasBioSample
annotations:
  count:
    tag: count
    value: 18222
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/246851
    example_object_type: sockg_SoilBiologicalSample
    example_predicate: sockg:hasBioSample
    example_subject: sockg:individuals/51968
    example_subject_type: sockg_ExperimentalUnit
from_schema: soc-kg
rank: 1000
domain: sockg_ExperimentalUnit
slot_uri: sockg:hasBioSample
alias: sockg_hasBioSample
domain_of:
- sockg_ExperimentalUnit
range: sockg_SoilBiologicalSample

```
</details>