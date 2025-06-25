

# Slot: No slot (predicate) name specified (sockg_measResidueMgnt_UID)


_No slot (predicate) description specified_






This slot occurs 18356 times.


URI: [sockg:measResidueMgnt_UID](https://idir.uta.edu/sockg-ontology/docs/measResidueMgnt_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgHarvest](../classes/SockgHarvest.md) | Harvest represents the process of collecting mature crops from the fields, wi... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Harvest | string | sockg:individuals/172906 | AgCros_PAHAW_211_2007-11-14_Glycine_max_Soybean_ | 18356 |




## LinkML Source

<details>

```yaml
name: sockg_measResidueMgnt_UID
annotations:
  count:
    tag: count
    value: 18356
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_PAHAW_211_2007-11-14_Glycine_max_Soybean_
    example_object_type: string
    example_predicate: sockg:measResidueMgnt_UID
    example_subject: sockg:individuals/172906
    example_subject_type: sockg_Harvest
from_schema: soc-kg
rank: 1000
domain: sockg_Harvest
slot_uri: sockg:measResidueMgnt_UID
alias: sockg_measResidueMgnt_UID
domain_of:
- sockg_Harvest
range: string

```
</details>