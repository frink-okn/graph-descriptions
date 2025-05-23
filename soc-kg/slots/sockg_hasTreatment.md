

# Slot: No slot (predicate) name specified (sockg_hasTreatment)


_No slot (predicate) description specified_






This slot occurs 741 times.


URI: [sockg:hasTreatment](https://idir.uta.edu/sockg-ontology/docs/hasTreatment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperiment](../classes/SockgExperiment.md) | An Experiment is a structured investigation carried out to observe and analyz... |  yes  |







## Properties

* Range: [SockgTreatment](../classes/SockgTreatment.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Experiment | sockg_Treatment | sockg:individuals/51906 | sockg:individuals/363836 | 741 |




## LinkML Source

<details>

```yaml
name: sockg_hasTreatment
annotations:
  count:
    tag: count
    value: 741
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/363836
    example_object_type: sockg_Treatment
    example_predicate: sockg:hasTreatment
    example_subject: sockg:individuals/51906
    example_subject_type: sockg_Experiment
from_schema: soc-kg
rank: 1000
domain: sockg_Experiment
slot_uri: sockg:hasTreatment
alias: sockg_hasTreatment
domain_of:
- sockg_Experiment
range: sockg_Treatment

```
</details>