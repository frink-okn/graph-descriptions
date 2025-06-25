

# Slot: No slot (predicate) name specified (sockg_hasChemSample)


_No slot (predicate) description specified_






This slot occurs 53833 times.


URI: [sockg:hasChemSample](https://idir.uta.edu/sockg-ontology/docs/hasChemSample)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |







## Properties

* Range: [SockgSoilChemicalSample](../classes/SockgSoilChemicalSample.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ExperimentalUnit | sockg_SoilChemicalSample | sockg:individuals/51937 | sockg:individuals/281187 | 53833 |




## LinkML Source

<details>

```yaml
name: sockg_hasChemSample
annotations:
  count:
    tag: count
    value: 53833
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/281187
    example_object_type: sockg_SoilChemicalSample
    example_predicate: sockg:hasChemSample
    example_subject: sockg:individuals/51937
    example_subject_type: sockg_ExperimentalUnit
from_schema: soc-kg
rank: 1000
domain: sockg_ExperimentalUnit
slot_uri: sockg:hasChemSample
alias: sockg_hasChemSample
domain_of:
- sockg_ExperimentalUnit
range: sockg_SoilChemicalSample

```
</details>