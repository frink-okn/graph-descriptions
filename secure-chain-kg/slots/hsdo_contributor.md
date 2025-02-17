

# Slot: contributor (hsdo_contributor)


_A secondary contributor to the CreativeWork or Event._






This slot occurs 36716 times.


URI: [hsdo:contributor](http://schema.org/contributor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HsdoPerson](../classes/HsdoPerson.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | hsdo_Person | securechain:Software/zapcc | schema:Person/yrnkrn | 3668 |
| securechain_Software | hsdo_Person | securechain:Software/3D-Graphics-Rendering-Cookbook | schema:Person/JosephA-packt | 33048 |




## LinkML Source

<details>

```yaml
name: hsdo_contributor
annotations:
  count:
    tag: count
    value: 36716
  hsdo_Person:
    tag: hsdo_Person
    value: 3668
description: A secondary contributor to the CreativeWork or Event.
title: contributor
examples:
- object:
    example_object: schema:Person/yrnkrn
    example_object_type: hsdo_Person
    example_predicate: hsdo:contributor
    example_subject: securechain:Software/zapcc
    example_subject_type: None
- object:
    example_object: schema:Person/JosephA-packt
    example_object_type: hsdo_Person
    example_predicate: hsdo:contributor
    example_subject: securechain:Software/3D-Graphics-Rendering-Cookbook
    example_subject_type: securechain_Software
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:contributor
alias: hsdo_contributor
domain_of:
- securechain_Software
range: hsdo_Person

```
</details>