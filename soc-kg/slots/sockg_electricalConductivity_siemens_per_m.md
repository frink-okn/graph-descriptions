

# Slot: No slot (predicate) name specified (sockg_electricalConductivity_siemens_per_m)


_No slot (predicate) description specified_






This slot occurs 5552 times.


URI: [sockg:electricalConductivity_siemens_per_m](https://idir.uta.edu/sockg-ontology/docs/electricalConductivity_siemens_per_m)



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
| sockg_SoilChemicalSample | double | sockg:individuals/253453 | 0.307 | 5552 |


## See Also

* [https://lod.nal.usda.gov/nalt/316816](https://lod.nal.usda.gov/nalt/316816)



## LinkML Source

<details>

```yaml
name: sockg_electricalConductivity_siemens_per_m
annotations:
  count:
    tag: count
    value: 5552
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.307'
    example_object_type: double
    example_predicate: sockg:electricalConductivity_siemens_per_m
    example_subject: sockg:individuals/253453
    example_subject_type: sockg_SoilChemicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/316816
rank: 1000
domain: sockg_SoilChemicalSample
slot_uri: sockg:electricalConductivity_siemens_per_m
alias: sockg_electricalConductivity_siemens_per_m
domain_of:
- sockg_SoilChemicalSample
range: Any
any_of:
- range: float
- range: double

```
</details>