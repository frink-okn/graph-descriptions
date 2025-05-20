

# Slot: No slot (predicate) name specified (sockg_measBiomassMinAn_UID)


_No slot (predicate) description specified_






This slot occurs 6723 times.


URI: [sockg:measBiomassMinAn_UID](https://idir.uta.edu/sockg-ontology/docs/measBiomassMinAn_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgBioMassMineral](../classes/SockgBioMassMineral.md) | BioMassMiner is a class that represents the analysis of biomass in terms of i... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_BioMassMineral | string | sockg:individuals/39962 | AgCros_NECCIRR_423_2018-10-04_Zea_mays_Corn_Stover_all_non-grain_biomass_ | 6723 |




## LinkML Source

<details>

```yaml
name: sockg_measBiomassMinAn_UID
annotations:
  count:
    tag: count
    value: 6723
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_NECCIRR_423_2018-10-04_Zea_mays_Corn_Stover_all_non-grain_biomass_
    example_object_type: string
    example_predicate: sockg:measBiomassMinAn_UID
    example_subject: sockg:individuals/39962
    example_subject_type: sockg_BioMassMineral
from_schema: soc-kg
rank: 1000
domain: sockg_BioMassMineral
slot_uri: sockg:measBiomassMinAn_UID
alias: sockg_measBiomassMinAn_UID
domain_of:
- sockg_BioMassMineral
range: string

```
</details>