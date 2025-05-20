

# Slot: No slot (predicate) name specified (sockg_mgtResidue_UID)


_No slot (predicate) description specified_






This slot occurs 3308 times.


URI: [sockg:mgtResidue_UID](https://idir.uta.edu/sockg-ontology/docs/mgtResidue_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgResidueManagementEvent](../classes/SockgResidueManagementEvent.md) | A ResidueManagementEvent represents a specific instance of managing agricultu... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ResidueManagementEvent | string | sockg:individuals/227674 | AgCros_PAHAW_212_2011-10-05_Zea_mays_Corn_ | 3308 |




## LinkML Source

<details>

```yaml
name: sockg_mgtResidue_UID
annotations:
  count:
    tag: count
    value: 3308
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_PAHAW_212_2011-10-05_Zea_mays_Corn_
    example_object_type: string
    example_predicate: sockg:mgtResidue_UID
    example_subject: sockg:individuals/227674
    example_subject_type: sockg_ResidueManagementEvent
from_schema: soc-kg
rank: 1000
domain: sockg_ResidueManagementEvent
slot_uri: sockg:mgtResidue_UID
alias: sockg_mgtResidue_UID
domain_of:
- sockg_ResidueManagementEvent
range: string

```
</details>