

# Slot: No slot (predicate) name specified (sockg_lowerDepth_cm)


_No slot (predicate) description specified_






This slot occurs 100137 times.


URI: [sockg:lowerDepth_cm](https://idir.uta.edu/sockg-ontology/docs/lowerDepth_cm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilChemicalSample](../classes/SockgSoilChemicalSample.md) | The SoilChemicalSample class represents a comprehensive analysis of soil chem... |  yes  |
| [SockgSoilBiologicalSample](../classes/SockgSoilBiologicalSample.md) | SoilBiologicalSample represents a collection of measurements related to micro... |  yes  |
| [SockgSoilPhysicalSample](../classes/SockgSoilPhysicalSample.md) | SoilPhysicalSample represents a comprehensive analysis of soil characteristic... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilBiologicalSample | integer | sockg:individuals/235229 | 2 | 18222 |
| sockg_SoilChemicalSample | double | sockg:individuals/253451 | 15.0 | 53833 |
| sockg_SoilPhysicalSample | double | sockg:individuals/308318 | 30.0 | 28082 |


## See Also

* [https://lod.nal.usda.gov/nalt/63373](https://lod.nal.usda.gov/nalt/63373)



## LinkML Source

<details>

```yaml
name: sockg_lowerDepth_cm
annotations:
  count:
    tag: count
    value: 100137
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '2'
    example_object_type: integer
    example_predicate: sockg:lowerDepth_cm
    example_subject: sockg:individuals/235229
    example_subject_type: sockg_SoilBiologicalSample
- object:
    example_object: '15.0'
    example_object_type: double
    example_predicate: sockg:lowerDepth_cm
    example_subject: sockg:individuals/253451
    example_subject_type: sockg_SoilChemicalSample
- object:
    example_object: '30.0'
    example_object_type: double
    example_predicate: sockg:lowerDepth_cm
    example_subject: sockg:individuals/308318
    example_subject_type: sockg_SoilPhysicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/63373
rank: 1000
slot_uri: sockg:lowerDepth_cm
alias: sockg_lowerDepth_cm
domain_of:
- sockg_SoilBiologicalSample
- sockg_SoilChemicalSample
- sockg_SoilPhysicalSample
union_of:
- '{''domain'': ''sockg_SoilChemicalSample''}'
- '{''domain'': ''sockg_SoilBiologicalSample''}'
- '{''domain'': ''sockg_SoilPhysicalSample''}'
range: Any
any_of:
- range: integer
- range: double

```
</details>