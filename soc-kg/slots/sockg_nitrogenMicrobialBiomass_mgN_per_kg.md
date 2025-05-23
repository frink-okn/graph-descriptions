

# Slot: No slot (predicate) name specified (sockg_nitrogenMicrobialBiomass_mgN_per_kg)


_No slot (predicate) description specified_






This slot occurs 2080 times.


URI: [sockg:nitrogenMicrobialBiomass_mgN_per_kg](https://idir.uta.edu/sockg-ontology/docs/nitrogenMicrobialBiomass_mgN_per_kg)



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
| sockg_SoilBiologicalSample | double | sockg:individuals/235818 | 0.122 | 2080 |


## See Also

* [https://lod.nal.usda.gov/nalt/324700](https://lod.nal.usda.gov/nalt/324700)



## LinkML Source

<details>

```yaml
name: sockg_nitrogenMicrobialBiomass_mgN_per_kg
annotations:
  count:
    tag: count
    value: 2080
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.122'
    example_object_type: double
    example_predicate: sockg:nitrogenMicrobialBiomass_mgN_per_kg
    example_subject: sockg:individuals/235818
    example_subject_type: sockg_SoilBiologicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/324700
rank: 1000
domain: sockg_SoilBiologicalSample
slot_uri: sockg:nitrogenMicrobialBiomass_mgN_per_kg
alias: sockg_nitrogenMicrobialBiomass_mgN_per_kg
domain_of:
- sockg_SoilBiologicalSample
range: Any
any_of:
- range: float
- range: double

```
</details>