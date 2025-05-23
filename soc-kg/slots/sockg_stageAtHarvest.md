

# Slot: No slot (predicate) name specified (sockg_stageAtHarvest)


_No slot (predicate) description specified_






This slot occurs 1650 times.


URI: [sockg:stageAtHarvest](https://idir.uta.edu/sockg-ontology/docs/stageAtHarvest)



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
| sockg_ResidueManagementEvent | string | sockg:individuals/227674 | Maturity | 1650 |


## See Also

* [https://lod.nal.usda.gov/nalt/1790](https://lod.nal.usda.gov/nalt/1790)



## LinkML Source

<details>

```yaml
name: sockg_stageAtHarvest
annotations:
  count:
    tag: count
    value: 1650
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Maturity
    example_object_type: string
    example_predicate: sockg:stageAtHarvest
    example_subject: sockg:individuals/227674
    example_subject_type: sockg_ResidueManagementEvent
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/1790
rank: 1000
domain: sockg_ResidueManagementEvent
slot_uri: sockg:stageAtHarvest
alias: sockg_stageAtHarvest
domain_of:
- sockg_ResidueManagementEvent
range: string

```
</details>