

# Slot: No slot (predicate) name specified (sockg_inorganicCarbon_gC_per_kg)


_No slot (predicate) description specified_






This slot occurs 5391 times.


URI: [sockg:inorganicCarbon_gC_per_kg](https://idir.uta.edu/sockg-ontology/docs/inorganicCarbon_gC_per_kg)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilChemicalSample](../classes/SockgSoilChemicalSample.md) | The SoilChemicalSample class represents a comprehensive analysis of soil chem... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilChemicalSample | double | sockg:individuals/253620 | 0.6600704 | 5391 |


## See Also

* [https://lod.nal.usda.gov/nalt/338945](https://lod.nal.usda.gov/nalt/338945)



## LinkML Source

<details>

```yaml
name: sockg_inorganicCarbon_gC_per_kg
annotations:
  count:
    tag: count
    value: 5391
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.6600704'
    example_object_type: double
    example_predicate: sockg:inorganicCarbon_gC_per_kg
    example_subject: sockg:individuals/253620
    example_subject_type: sockg_SoilChemicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/338945
rank: 1000
domain: sockg_SoilChemicalSample
slot_uri: sockg:inorganicCarbon_gC_per_kg
alias: sockg_inorganicCarbon_gC_per_kg
domain_of:
- sockg_SoilChemicalSample
range: Any
any_of:
- range: float
- range: double

```
</details>