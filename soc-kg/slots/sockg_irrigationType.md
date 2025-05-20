

# Slot: No slot (predicate) name specified (sockg_irrigationType)


_No slot (predicate) description specified_






This slot occurs 4220 times.


URI: [sockg:irrigationType](https://idir.uta.edu/sockg-ontology/docs/irrigationType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgAmendment](../classes/SockgAmendment.md) | An Amendment represents a specific alteration or addition made to agricultura... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Amendment | string | sockg:individuals/10095 | Linear Move Sprinkler | 4220 |


## See Also

* [https://lod.nal.usda.gov/nalt/16017](https://lod.nal.usda.gov/nalt/16017)



## LinkML Source

<details>

```yaml
name: sockg_irrigationType
annotations:
  count:
    tag: count
    value: 4220
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Linear Move Sprinkler
    example_object_type: string
    example_predicate: sockg:irrigationType
    example_subject: sockg:individuals/10095
    example_subject_type: sockg_Amendment
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/16017
rank: 1000
domain: sockg_Amendment
slot_uri: sockg:irrigationType
alias: sockg_irrigationType
domain_of:
- sockg_Amendment
range: Any
any_of:
- range: string
- range: float

```
</details>