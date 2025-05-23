

# Slot: No slot (predicate) name specified (sockg_totalSoilNitrogenSd_gN_per_kg)


_No slot (predicate) description specified_






This slot occurs 720 times.


URI: [sockg:totalSoilNitrogenSd_gN_per_kg](https://idir.uta.edu/sockg-ontology/docs/totalSoilNitrogenSd_gN_per_kg)



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
| sockg_SoilChemicalSample | double | sockg:individuals/270000 | 2.77348 | 720 |


## See Also

* [https://lod.nal.usda.gov/nalt/281219](https://lod.nal.usda.gov/nalt/281219)



## LinkML Source

<details>

```yaml
name: sockg_totalSoilNitrogenSd_gN_per_kg
annotations:
  count:
    tag: count
    value: 720
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '2.77348'
    example_object_type: double
    example_predicate: sockg:totalSoilNitrogenSd_gN_per_kg
    example_subject: sockg:individuals/270000
    example_subject_type: sockg_SoilChemicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/281219
rank: 1000
domain: sockg_SoilChemicalSample
slot_uri: sockg:totalSoilNitrogenSd_gN_per_kg
alias: sockg_totalSoilNitrogenSd_gN_per_kg
domain_of:
- sockg_SoilChemicalSample
range: Any
any_of:
- range: float
- range: double

```
</details>