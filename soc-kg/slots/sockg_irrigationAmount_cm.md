

# Slot: No slot (predicate) name specified (sockg_irrigationAmount_cm)


_No slot (predicate) description specified_






This slot occurs 4382 times.


URI: [sockg:irrigationAmount_cm](https://idir.uta.edu/sockg-ontology/docs/irrigationAmount_cm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgAmendment](../classes/SockgAmendment.md) | An Amendment represents a specific alteration or addition made to agricultura... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Amendment | double | sockg:individuals/1000 | 3.65 | 4382 |


## See Also

* [https://lod.nal.usda.gov/nalt/47771](https://lod.nal.usda.gov/nalt/47771)



## LinkML Source

<details>

```yaml
name: sockg_irrigationAmount_cm
annotations:
  count:
    tag: count
    value: 4382
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '3.65'
    example_object_type: double
    example_predicate: sockg:irrigationAmount_cm
    example_subject: sockg:individuals/1000
    example_subject_type: sockg_Amendment
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/47771
rank: 1000
domain: sockg_Amendment
slot_uri: sockg:irrigationAmount_cm
alias: sockg_irrigationAmount_cm
domain_of:
- sockg_Amendment
range: Any
any_of:
- range: float
- range: double

```
</details>