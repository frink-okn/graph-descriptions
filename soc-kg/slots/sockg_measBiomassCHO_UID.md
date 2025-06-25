

# Slot: No slot (predicate) name specified (sockg_measBiomassCHO_UID)


_No slot (predicate) description specified_






This slot occurs 1367 times.


URI: [sockg:measBiomassCHO_UID](https://idir.uta.edu/sockg-ontology/docs/measBiomassCHO_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgBioMassCarbohydrate](../classes/SockgBioMassCarbohydrate.md) | BioMassCarbohydrate represents the carbohydrate content in biomass derived fr... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_BioMassCarbohydrate | string | sockg:individuals/37796 | AgCros_MNSPReap_101LA_2009-10-01_Zea_mays_Corn_Above_earshank | 1367 |




## LinkML Source

<details>

```yaml
name: sockg_measBiomassCHO_UID
annotations:
  count:
    tag: count
    value: 1367
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_MNSPReap_101LA_2009-10-01_Zea_mays_Corn_Above_earshank
    example_object_type: string
    example_predicate: sockg:measBiomassCHO_UID
    example_subject: sockg:individuals/37796
    example_subject_type: sockg_BioMassCarbohydrate
from_schema: soc-kg
rank: 1000
domain: sockg_BioMassCarbohydrate
slot_uri: sockg:measBiomassCHO_UID
alias: sockg_measBiomassCHO_UID
domain_of:
- sockg_BioMassCarbohydrate
range: string

```
</details>