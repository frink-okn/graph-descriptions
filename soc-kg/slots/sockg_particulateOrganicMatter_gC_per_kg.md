

# Slot: No slot (predicate) name specified (sockg_particulateOrganicMatter_gC_per_kg)


_No slot (predicate) description specified_






This slot occurs 18222 times.


URI: [sockg:particulateOrganicMatter_gC_per_kg](https://idir.uta.edu/sockg-ontology/docs/particulateOrganicMatter_gC_per_kg)



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
| sockg_SoilBiologicalSample | double | sockg:individuals/235229 | 3.966132 | 18222 |


## See Also

* [https://lod.nal.usda.gov/nalt/263001](https://lod.nal.usda.gov/nalt/263001)



## LinkML Source

<details>

```yaml
name: sockg_particulateOrganicMatter_gC_per_kg
annotations:
  count:
    tag: count
    value: 18222
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '3.966132'
    example_object_type: double
    example_predicate: sockg:particulateOrganicMatter_gC_per_kg
    example_subject: sockg:individuals/235229
    example_subject_type: sockg_SoilBiologicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/263001
rank: 1000
domain: sockg_SoilBiologicalSample
slot_uri: sockg:particulateOrganicMatter_gC_per_kg
alias: sockg_particulateOrganicMatter_gC_per_kg
domain_of:
- sockg_SoilBiologicalSample
range: Any
any_of:
- range: float
- range: double

```
</details>