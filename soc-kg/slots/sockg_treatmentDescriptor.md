

# Slot: No slot (predicate) name specified (sockg_treatmentDescriptor)


_No slot (predicate) description specified_






This slot occurs 769 times.


URI: [sockg:treatmentDescriptor](https://idir.uta.edu/sockg-ontology/docs/treatmentDescriptor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgTreatment](../classes/SockgTreatment.md) | The Treatment class encompasses various agricultural practices and management... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Treatment | string | sockg:individuals/363556 | Control | 769 |




## LinkML Source

<details>

```yaml
name: sockg_treatmentDescriptor
annotations:
  count:
    tag: count
    value: 769
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Control
    example_object_type: string
    example_predicate: sockg:treatmentDescriptor
    example_subject: sockg:individuals/363556
    example_subject_type: sockg_Treatment
from_schema: soc-kg
rank: 1000
domain: sockg_Treatment
slot_uri: sockg:treatmentDescriptor
alias: sockg_treatmentDescriptor
domain_of:
- sockg_Treatment
range: string

```
</details>