

# Slot: No slot (predicate) name specified (sockg_isCarbonDioxideInterpolated)


_No slot (predicate) description specified_






This slot occurs 107354 times.


URI: [sockg:isCarbonDioxideInterpolated](https://idir.uta.edu/sockg-ontology/docs/isCarbonDioxideInterpolated)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasSample](../classes/SockgGasSample.md) | GasSample represents a collection of measurements related to greenhouse gas e... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[Int32](../types/Int32.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GasSample | integer | sockg:individuals/100000 | 1 | 107354 |




## LinkML Source

<details>

```yaml
name: sockg_isCarbonDioxideInterpolated
annotations:
  count:
    tag: count
    value: 107354
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '1'
    example_object_type: integer
    example_predicate: sockg:isCarbonDioxideInterpolated
    example_subject: sockg:individuals/100000
    example_subject_type: sockg_GasSample
from_schema: soc-kg
rank: 1000
domain: sockg_GasSample
slot_uri: sockg:isCarbonDioxideInterpolated
alias: sockg_isCarbonDioxideInterpolated
domain_of:
- sockg_GasSample
range: Any
any_of:
- range: integer
- range: int32

```
</details>