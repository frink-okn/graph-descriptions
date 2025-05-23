

# Slot: No slot (predicate) name specified (sockg_sandPercent)


_No slot (predicate) description specified_






This slot occurs 27110 times.


URI: [sockg:sandPercent](https://idir.uta.edu/sockg-ontology/docs/sandPercent)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilPhysicalSample](../classes/SockgSoilPhysicalSample.md) | SoilPhysicalSample represents a comprehensive analysis of soil characteristic... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilPhysicalSample | double | sockg:individuals/308319 | 0.0 | 27110 |


## See Also

* [https://lod.nal.usda.gov/nalt/62338](https://lod.nal.usda.gov/nalt/62338)



## LinkML Source

<details>

```yaml
name: sockg_sandPercent
annotations:
  count:
    tag: count
    value: 27110
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.0'
    example_object_type: double
    example_predicate: sockg:sandPercent
    example_subject: sockg:individuals/308319
    example_subject_type: sockg_SoilPhysicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/62338
rank: 1000
domain: sockg_SoilPhysicalSample
slot_uri: sockg:sandPercent
alias: sockg_sandPercent
domain_of:
- sockg_SoilPhysicalSample
range: Any
any_of:
- range: float
- range: double

```
</details>