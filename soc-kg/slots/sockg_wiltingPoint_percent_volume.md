

# Slot: No slot (predicate) name specified (sockg_wiltingPoint_percent_volume)


_No slot (predicate) description specified_






This slot occurs 24 times.


URI: [sockg:wiltingPoint_percent_volume](https://idir.uta.edu/sockg-ontology/docs/wiltingPoint_percent_volume)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilPhysicalSample](../classes/SockgSoilPhysicalSample.md) | SoilPhysicalSample represents a comprehensive analysis of soil characteristic... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilPhysicalSample | double | sockg:individuals/334651 | 21.2 | 24 |


## See Also

* [https://lod.nal.usda.gov/nalt/57491](https://lod.nal.usda.gov/nalt/57491)



## LinkML Source

<details>

```yaml
name: sockg_wiltingPoint_percent_volume
annotations:
  count:
    tag: count
    value: 24
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '21.2'
    example_object_type: double
    example_predicate: sockg:wiltingPoint_percent_volume
    example_subject: sockg:individuals/334651
    example_subject_type: sockg_SoilPhysicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/57491
rank: 1000
domain: sockg_SoilPhysicalSample
slot_uri: sockg:wiltingPoint_percent_volume
alias: sockg_wiltingPoint_percent_volume
domain_of:
- sockg_SoilPhysicalSample
range: Any
any_of:
- range: double
- range: float

```
</details>