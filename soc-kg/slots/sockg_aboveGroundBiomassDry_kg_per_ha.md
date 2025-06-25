

# Slot: No slot (predicate) name specified (sockg_aboveGroundBiomassDry_kg_per_ha)


_No slot (predicate) description specified_






This slot occurs 6995 times.


URI: [sockg:aboveGroundBiomassDry_kg_per_ha](https://idir.uta.edu/sockg-ontology/docs/aboveGroundBiomassDry_kg_per_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGrazing](../classes/SockgGrazing.md) | The Grazing class represents the assessment of various productivity metrics a... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Grazing | double | sockg:individuals/163960 | 3600.0 | 6995 |




## LinkML Source

<details>

```yaml
name: sockg_aboveGroundBiomassDry_kg_per_ha
annotations:
  count:
    tag: count
    value: 6995
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '3600.0'
    example_object_type: double
    example_predicate: sockg:aboveGroundBiomassDry_kg_per_ha
    example_subject: sockg:individuals/163960
    example_subject_type: sockg_Grazing
from_schema: soc-kg
rank: 1000
domain: sockg_Grazing
slot_uri: sockg:aboveGroundBiomassDry_kg_per_ha
alias: sockg_aboveGroundBiomassDry_kg_per_ha
domain_of:
- sockg_Grazing
range: Any
any_of:
- range: float
- range: double

```
</details>