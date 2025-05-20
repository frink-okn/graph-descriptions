

# Slot: No slot (predicate) name specified (sockg_hasBioMassEnergyData)


_No slot (predicate) description specified_






This slot occurs 799 times.


URI: [sockg:hasBioMassEnergyData](https://idir.uta.edu/sockg-ontology/docs/hasBioMassEnergyData)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |







## Properties

* Range: [SockgBioMassEnergy](../classes/SockgBioMassEnergy.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ExperimentalUnit | sockg_BioMassEnergy | sockg:individuals/54440 | sockg:individuals/39169 | 799 |




## LinkML Source

<details>

```yaml
name: sockg_hasBioMassEnergyData
annotations:
  count:
    tag: count
    value: 799
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/39169
    example_object_type: sockg_BioMassEnergy
    example_predicate: sockg:hasBioMassEnergyData
    example_subject: sockg:individuals/54440
    example_subject_type: sockg_ExperimentalUnit
from_schema: soc-kg
rank: 1000
domain: sockg_ExperimentalUnit
slot_uri: sockg:hasBioMassEnergyData
alias: sockg_hasBioMassEnergyData
domain_of:
- sockg_ExperimentalUnit
range: sockg_BioMassEnergy

```
</details>