

# Slot: No slot (predicate) name specified (sockg_alkPhosphatase_mg_per_kg_per_hr)


_No slot (predicate) description specified_






This slot occurs 465 times.


URI: [sockg:alkPhosphatase_mg_per_kg_per_hr](https://idir.uta.edu/sockg-ontology/docs/alkPhosphatase_mg_per_kg_per_hr)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilBiologicalSample](../classes/SockgSoilBiologicalSample.md) | SoilBiologicalSample represents a collection of measurements related to micro... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilBiologicalSample | double | sockg:individuals/251567 | 135.1641 | 465 |


## See Also

* [https://lod.nal.usda.gov/nalt/6425](https://lod.nal.usda.gov/nalt/6425)



## LinkML Source

<details>

```yaml
name: sockg_alkPhosphatase_mg_per_kg_per_hr
annotations:
  count:
    tag: count
    value: 465
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '135.1641'
    example_object_type: double
    example_predicate: sockg:alkPhosphatase_mg_per_kg_per_hr
    example_subject: sockg:individuals/251567
    example_subject_type: sockg_SoilBiologicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/6425
rank: 1000
domain: sockg_SoilBiologicalSample
slot_uri: sockg:alkPhosphatase_mg_per_kg_per_hr
alias: sockg_alkPhosphatase_mg_per_kg_per_hr
domain_of:
- sockg_SoilBiologicalSample
range: Any
any_of:
- range: double
- range: float

```
</details>