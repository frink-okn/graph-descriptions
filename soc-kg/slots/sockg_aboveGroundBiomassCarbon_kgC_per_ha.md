

# Slot: No slot (predicate) name specified (sockg_aboveGroundBiomassCarbon_kgC_per_ha)


_No slot (predicate) description specified_






This slot occurs 2149 times.


URI: [sockg:aboveGroundBiomassCarbon_kgC_per_ha](https://idir.uta.edu/sockg-ontology/docs/aboveGroundBiomassCarbon_kgC_per_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGrazing](../classes/SockgGrazing.md) | The Grazing class represents the assessment of various productivity metrics a... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Grazing | double | sockg:individuals/164143 | 2391.471 | 2149 |




## LinkML Source

<details>

```yaml
name: sockg_aboveGroundBiomassCarbon_kgC_per_ha
annotations:
  count:
    tag: count
    value: 2149
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '2391.471'
    example_object_type: double
    example_predicate: sockg:aboveGroundBiomassCarbon_kgC_per_ha
    example_subject: sockg:individuals/164143
    example_subject_type: sockg_Grazing
from_schema: soc-kg
rank: 1000
domain: sockg_Grazing
slot_uri: sockg:aboveGroundBiomassCarbon_kgC_per_ha
alias: sockg_aboveGroundBiomassCarbon_kgC_per_ha
domain_of:
- sockg_Grazing
range: Any
any_of:
- range: double
- range: float

```
</details>