

# Slot: No slot (predicate) name specified (sockg_totalPhosphorusAmount_kgP_per_ha)


_No slot (predicate) description specified_






This slot occurs 8440 times.


URI: [sockg:totalPhosphorusAmount_kgP_per_ha](https://idir.uta.edu/sockg-ontology/docs/totalPhosphorusAmount_kgP_per_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgAmendment](../classes/SockgAmendment.md) | An Amendment represents a specific alteration or addition made to agricultura... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Amendment | double | sockg:individuals/10 | 19.6 | 8440 |


## See Also

* [https://lod.nal.usda.gov/nalt/325170](https://lod.nal.usda.gov/nalt/325170)



## LinkML Source

<details>

```yaml
name: sockg_totalPhosphorusAmount_kgP_per_ha
annotations:
  count:
    tag: count
    value: 8440
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '19.6'
    example_object_type: double
    example_predicate: sockg:totalPhosphorusAmount_kgP_per_ha
    example_subject: sockg:individuals/10
    example_subject_type: sockg_Amendment
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/325170
rank: 1000
domain: sockg_Amendment
slot_uri: sockg:totalPhosphorusAmount_kgP_per_ha
alias: sockg_totalPhosphorusAmount_kgP_per_ha
domain_of:
- sockg_Amendment
range: Any
any_of:
- range: double
- range: float

```
</details>