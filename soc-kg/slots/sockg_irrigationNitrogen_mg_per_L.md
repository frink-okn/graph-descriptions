

# Slot: No slot (predicate) name specified (sockg_irrigationNitrogen_mg_per_L)


_No slot (predicate) description specified_






This slot occurs 160 times.


URI: [sockg:irrigationNitrogen_mg_per_L](https://idir.uta.edu/sockg-ontology/docs/irrigationNitrogen_mg_per_L)



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
| sockg_Amendment | double | sockg:individuals/22222 | 0.0 | 160 |


## See Also

* [https://lod.nal.usda.gov/nalt/7829](https://lod.nal.usda.gov/nalt/7829)



## LinkML Source

<details>

```yaml
name: sockg_irrigationNitrogen_mg_per_L
annotations:
  count:
    tag: count
    value: 160
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.0'
    example_object_type: double
    example_predicate: sockg:irrigationNitrogen_mg_per_L
    example_subject: sockg:individuals/22222
    example_subject_type: sockg_Amendment
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/7829
rank: 1000
domain: sockg_Amendment
slot_uri: sockg:irrigationNitrogen_mg_per_L
alias: sockg_irrigationNitrogen_mg_per_L
domain_of:
- sockg_Amendment
range: Any
any_of:
- range: double
- range: float

```
</details>