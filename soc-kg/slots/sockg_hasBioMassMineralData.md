

# Slot: No slot (predicate) name specified (sockg_hasBioMassMineralData)


_No slot (predicate) description specified_






This slot occurs 6723 times.


URI: [sockg:hasBioMassMineralData](https://idir.uta.edu/sockg-ontology/docs/hasBioMassMineralData)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |







## Properties

* Range: [SockgBioMassMineral](../classes/SockgBioMassMineral.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ExperimentalUnit | sockg_BioMassMineral | sockg:individuals/51968 | sockg:individuals/40481 | 6723 |




## LinkML Source

<details>

```yaml
name: sockg_hasBioMassMineralData
annotations:
  count:
    tag: count
    value: 6723
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/40481
    example_object_type: sockg_BioMassMineral
    example_predicate: sockg:hasBioMassMineralData
    example_subject: sockg:individuals/51968
    example_subject_type: sockg_ExperimentalUnit
from_schema: soc-kg
rank: 1000
domain: sockg_ExperimentalUnit
slot_uri: sockg:hasBioMassMineralData
alias: sockg_hasBioMassMineralData
domain_of:
- sockg_ExperimentalUnit
range: sockg_BioMassMineral

```
</details>