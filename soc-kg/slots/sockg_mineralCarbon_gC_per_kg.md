

# Slot: No slot (predicate) name specified (sockg_mineralCarbon_gC_per_kg)


_No slot (predicate) description specified_






This slot occurs 3343 times.


URI: [sockg:mineralCarbon_gC_per_kg](https://idir.uta.edu/sockg-ontology/docs/mineralCarbon_gC_per_kg)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilChemicalSample](../classes/SockgSoilChemicalSample.md) | The SoilChemicalSample class represents a comprehensive analysis of soil chem... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilChemicalSample | double | sockg:individuals/267681 | 6.427706 | 3343 |




## LinkML Source

<details>

```yaml
name: sockg_mineralCarbon_gC_per_kg
annotations:
  count:
    tag: count
    value: 3343
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '6.427706'
    example_object_type: double
    example_predicate: sockg:mineralCarbon_gC_per_kg
    example_subject: sockg:individuals/267681
    example_subject_type: sockg_SoilChemicalSample
from_schema: soc-kg
rank: 1000
domain: sockg_SoilChemicalSample
slot_uri: sockg:mineralCarbon_gC_per_kg
alias: sockg_mineralCarbon_gC_per_kg
domain_of:
- sockg_SoilChemicalSample
range: Any
any_of:
- range: double
- range: float

```
</details>