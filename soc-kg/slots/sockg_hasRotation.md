

# Slot: No slot (predicate) name specified (sockg_hasRotation)


_No slot (predicate) description specified_






This slot occurs 761 times.


URI: [sockg:hasRotation](https://idir.uta.edu/sockg-ontology/docs/hasRotation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgTreatment](../classes/SockgTreatment.md) | The Treatment class encompasses various agricultural practices and management... |  yes  |







## Properties

* Range: [SockgRotation](../classes/SockgRotation.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Treatment | sockg_Rotation | sockg:individuals/363556 | sockg:individuals/230982 | 761 |




## LinkML Source

<details>

```yaml
name: sockg_hasRotation
annotations:
  count:
    tag: count
    value: 761
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/230982
    example_object_type: sockg_Rotation
    example_predicate: sockg:hasRotation
    example_subject: sockg:individuals/363556
    example_subject_type: sockg_Treatment
from_schema: soc-kg
rank: 1000
domain: sockg_Treatment
slot_uri: sockg:hasRotation
alias: sockg_hasRotation
domain_of:
- sockg_Treatment
range: sockg_Rotation

```
</details>