

# Slot: No slot (predicate) name specified (sockg_measSoilChem_UID)


_No slot (predicate) description specified_






This slot occurs 53833 times.


URI: [sockg:measSoilChem_UID](https://idir.uta.edu/sockg-ontology/docs/measSoilChem_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilChemicalSample](../classes/SockgSoilChemicalSample.md) | The SoilChemicalSample class represents a comprehensive analysis of soil chem... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilChemicalSample | string | sockg:individuals/253451 | AgCros_MNMOFS_52_2007-10-29_10.0_15.0 | 53833 |




## LinkML Source

<details>

```yaml
name: sockg_measSoilChem_UID
annotations:
  count:
    tag: count
    value: 53833
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_MNMOFS_52_2007-10-29_10.0_15.0
    example_object_type: string
    example_predicate: sockg:measSoilChem_UID
    example_subject: sockg:individuals/253451
    example_subject_type: sockg_SoilChemicalSample
from_schema: soc-kg
rank: 1000
domain: sockg_SoilChemicalSample
slot_uri: sockg:measSoilChem_UID
alias: sockg_measSoilChem_UID
domain_of:
- sockg_SoilChemicalSample
range: string

```
</details>