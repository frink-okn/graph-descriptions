

# Slot: No slot (predicate) name specified (sockg_experimentName)


_No slot (predicate) description specified_






This slot occurs 55 times.


URI: [sockg:experimentName](https://idir.uta.edu/sockg-ontology/docs/experimentName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperiment](../classes/SockgExperiment.md) | An Experiment is a structured investigation carried out to observe and analyz... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Experiment | string | sockg:individuals/51906 | GRACEnet | 55 |




## LinkML Source

<details>

```yaml
name: sockg_experimentName
annotations:
  count:
    tag: count
    value: 55
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: GRACEnet
    example_object_type: string
    example_predicate: sockg:experimentName
    example_subject: sockg:individuals/51906
    example_subject_type: sockg_Experiment
from_schema: soc-kg
rank: 1000
domain: sockg_Experiment
slot_uri: sockg:experimentName
alias: sockg_experimentName
domain_of:
- sockg_Experiment
range: string

```
</details>