

# Slot: No slot (predicate) name specified (sockg_rotationDescriptor)


_No slot (predicate) description specified_






This slot occurs 66 times.


URI: [sockg:rotationDescriptor](https://idir.uta.edu/sockg-ontology/docs/rotationDescriptor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgRotation](../classes/SockgRotation.md) | Rotation refers to the practice of systematically changing the types of crops... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Rotation | string | sockg:individuals/230982 | Rangeland | 66 |


## See Also

* [https://lod.nal.usda.gov/nalt/30158](https://lod.nal.usda.gov/nalt/30158)



## LinkML Source

<details>

```yaml
name: sockg_rotationDescriptor
annotations:
  count:
    tag: count
    value: 66
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Rangeland
    example_object_type: string
    example_predicate: sockg:rotationDescriptor
    example_subject: sockg:individuals/230982
    example_subject_type: sockg_Rotation
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/30158
rank: 1000
domain: sockg_Rotation
slot_uri: sockg:rotationDescriptor
alias: sockg_rotationDescriptor
domain_of:
- sockg_Rotation
range: string

```
</details>