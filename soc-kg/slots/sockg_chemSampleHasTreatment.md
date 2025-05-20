

# Slot: No slot (predicate) name specified (sockg_chemSampleHasTreatment)


_No slot (predicate) description specified_






This slot occurs 54015 times.


URI: [sockg:chemSampleHasTreatment](https://idir.uta.edu/sockg-ontology/docs/chemSampleHasTreatment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilChemicalSample](../classes/SockgSoilChemicalSample.md) | The SoilChemicalSample class represents a comprehensive analysis of soil chem... |  yes  |







## Properties

* Range: [SockgTreatment](../classes/SockgTreatment.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilChemicalSample | sockg_Treatment | sockg:individuals/253451 | sockg:individuals/363676 | 54015 |




## LinkML Source

<details>

```yaml
name: sockg_chemSampleHasTreatment
annotations:
  count:
    tag: count
    value: 54015
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/363676
    example_object_type: sockg_Treatment
    example_predicate: sockg:chemSampleHasTreatment
    example_subject: sockg:individuals/253451
    example_subject_type: sockg_SoilChemicalSample
from_schema: soc-kg
rank: 1000
domain: sockg_SoilChemicalSample
slot_uri: sockg:chemSampleHasTreatment
alias: sockg_chemSampleHasTreatment
domain_of:
- sockg_SoilChemicalSample
range: sockg_Treatment

```
</details>