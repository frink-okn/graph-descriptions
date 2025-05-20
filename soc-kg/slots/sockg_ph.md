

# Slot: No slot (predicate) name specified (sockg_ph)


_No slot (predicate) description specified_






This slot occurs 18189 times.


URI: [sockg:ph](https://idir.uta.edu/sockg-ontology/docs/ph)



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
| sockg_SoilChemicalSample | double | sockg:individuals/253453 | 8.06 | 18189 |


## See Also

* [https://lod.nal.usda.gov/nalt/2736](https://lod.nal.usda.gov/nalt/2736)



## LinkML Source

<details>

```yaml
name: sockg_ph
annotations:
  count:
    tag: count
    value: 18189
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '8.06'
    example_object_type: double
    example_predicate: sockg:ph
    example_subject: sockg:individuals/253453
    example_subject_type: sockg_SoilChemicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/2736
rank: 1000
slot_uri: sockg:ph
alias: sockg_ph
domain_of:
- sockg_SoilChemicalSample
union_of:
- '{''domain'': ''sockg_WaterQualityArea''}'
- '{''domain'': ''sockg_SoilChemicalSample''}'
- '{''domain'': ''sockg_WaterQualityConc''}'
- '{''domain'': ''sockg_WindErosionArea''}'
range: Any
any_of:
- range: double
- range: float

```
</details>