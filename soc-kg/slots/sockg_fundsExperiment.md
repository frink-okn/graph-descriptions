

# Slot: No slot (predicate) name specified (sockg_fundsExperiment)


_No slot (predicate) description specified_






This slot occurs 3 times.


URI: [sockg:fundsExperiment](https://idir.uta.edu/sockg-ontology/docs/fundsExperiment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgOrganization](../classes/SockgOrganization.md) | An Organization is a structured group of individuals working together to achi... |  yes  |







## Properties

* Range: [SockgExperiment](../classes/SockgExperiment.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Organization | sockg_Experiment | sockg:individuals/203523 | sockg:individuals/51906 | 3 |




## LinkML Source

<details>

```yaml
name: sockg_fundsExperiment
annotations:
  count:
    tag: count
    value: 3
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/51906
    example_object_type: sockg_Experiment
    example_predicate: sockg:fundsExperiment
    example_subject: sockg:individuals/203523
    example_subject_type: sockg_Organization
from_schema: soc-kg
rank: 1000
domain: sockg_Organization
slot_uri: sockg:fundsExperiment
alias: sockg_fundsExperiment
domain_of:
- sockg_Organization
range: sockg_Experiment

```
</details>