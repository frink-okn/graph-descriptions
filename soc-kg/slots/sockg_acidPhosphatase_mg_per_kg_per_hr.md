

# Slot: No slot (predicate) name specified (sockg_acidPhosphatase_mg_per_kg_per_hr)


_No slot (predicate) description specified_






This slot occurs 213 times.


URI: [sockg:acidPhosphatase_mg_per_kg_per_hr](https://idir.uta.edu/sockg-ontology/docs/acidPhosphatase_mg_per_kg_per_hr)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilBiologicalSample](../classes/SockgSoilBiologicalSample.md) | SoilBiologicalSample represents a collection of measurements related to micro... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilBiologicalSample | double | sockg:individuals/251798 | 23.14453 | 213 |


## See Also

* [https://lod.nal.usda.gov/nalt/2726](https://lod.nal.usda.gov/nalt/2726)



## LinkML Source

<details>

```yaml
name: sockg_acidPhosphatase_mg_per_kg_per_hr
annotations:
  count:
    tag: count
    value: 213
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '23.14453'
    example_object_type: double
    example_predicate: sockg:acidPhosphatase_mg_per_kg_per_hr
    example_subject: sockg:individuals/251798
    example_subject_type: sockg_SoilBiologicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/2726
rank: 1000
domain: sockg_SoilBiologicalSample
slot_uri: sockg:acidPhosphatase_mg_per_kg_per_hr
alias: sockg_acidPhosphatase_mg_per_kg_per_hr
domain_of:
- sockg_SoilBiologicalSample
range: Any
any_of:
- range: float
- range: double

```
</details>