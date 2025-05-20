

# Slot: No slot (predicate) name specified (sockg_projectName)


_No slot (predicate) description specified_






This slot occurs 64 times.


URI: [sockg:projectName](https://idir.uta.edu/sockg-ontology/docs/projectName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperiment](../classes/SockgExperiment.md) | An Experiment is a structured investigation carried out to observe and analyz... |  yes  |
| [SockgProject](../classes/SockgProject.md) | A project in the context of agriculture refers to a planned set of activities... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Experiment | string | sockg:individuals/51906 | GRACEnet | 55 |
| sockg_Project | string | sockg:individuals/227438 | GRACEnet | 9 |


## See Also

* [https://lod.nal.usda.gov/nalt/61097](https://lod.nal.usda.gov/nalt/61097)



## LinkML Source

<details>

```yaml
name: sockg_projectName
annotations:
  count:
    tag: count
    value: 64
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: GRACEnet
    example_object_type: string
    example_predicate: sockg:projectName
    example_subject: sockg:individuals/51906
    example_subject_type: sockg_Experiment
- object:
    example_object: GRACEnet
    example_object_type: string
    example_predicate: sockg:projectName
    example_subject: sockg:individuals/227438
    example_subject_type: sockg_Project
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/61097
rank: 1000
slot_uri: sockg:projectName
alias: sockg_projectName
domain_of:
- sockg_Experiment
- sockg_Project
union_of:
- '{''domain'': ''sockg_Project''}'
- '{''domain'': ''sockg_Experiment''}'
range: string

```
</details>