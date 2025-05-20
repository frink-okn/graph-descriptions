

# Slot: No slot (predicate) name specified (sockg_totalSoilCarbon_gC_per_kg)


_No slot (predicate) description specified_






This slot occurs 44073 times.


URI: [sockg:totalSoilCarbon_gC_per_kg](https://idir.uta.edu/sockg-ontology/docs/totalSoilCarbon_gC_per_kg)



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
| sockg_SoilChemicalSample | double | sockg:individuals/253451 | 30.7 | 44073 |


## See Also

* [https://lod.nal.usda.gov/nalt/325192](https://lod.nal.usda.gov/nalt/325192)



## LinkML Source

<details>

```yaml
name: sockg_totalSoilCarbon_gC_per_kg
annotations:
  count:
    tag: count
    value: 44073
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '30.7'
    example_object_type: double
    example_predicate: sockg:totalSoilCarbon_gC_per_kg
    example_subject: sockg:individuals/253451
    example_subject_type: sockg_SoilChemicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/325192
rank: 1000
domain: sockg_SoilChemicalSample
slot_uri: sockg:totalSoilCarbon_gC_per_kg
alias: sockg_totalSoilCarbon_gC_per_kg
domain_of:
- sockg_SoilChemicalSample
range: Any
any_of:
- range: double
- range: float

```
</details>