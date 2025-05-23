

# Slot: No slot (predicate) name specified (sockg_ironConcentration_mg_per_kg)


_No slot (predicate) description specified_






This slot occurs 6723 times.


URI: [sockg:ironConcentration_mg_per_kg](https://idir.uta.edu/sockg-ontology/docs/ironConcentration_mg_per_kg)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgBioMassMineral](../classes/SockgBioMassMineral.md) | BioMassMiner is a class that represents the analysis of biomass in terms of i... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_BioMassMineral | double | sockg:individuals/39962 | 56.0 | 6723 |




## LinkML Source

<details>

```yaml
name: sockg_ironConcentration_mg_per_kg
annotations:
  count:
    tag: count
    value: 6723
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '56.0'
    example_object_type: double
    example_predicate: sockg:ironConcentration_mg_per_kg
    example_subject: sockg:individuals/39962
    example_subject_type: sockg_BioMassMineral
from_schema: soc-kg
rank: 1000
domain: sockg_BioMassMineral
slot_uri: sockg:ironConcentration_mg_per_kg
alias: sockg_ironConcentration_mg_per_kg
domain_of:
- sockg_BioMassMineral
range: Any
any_of:
- range: float
- range: double

```
</details>