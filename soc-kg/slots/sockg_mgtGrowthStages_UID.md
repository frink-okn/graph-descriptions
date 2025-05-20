

# Slot: No slot (predicate) name specified (sockg_mgtGrowthStages_UID)


_No slot (predicate) description specified_






This slot occurs 4896 times.


URI: [sockg:mgtGrowthStages_UID](https://idir.uta.edu/sockg-ontology/docs/mgtGrowthStages_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgCropGrowthStage](../classes/SockgCropGrowthStage.md) | The CropGrowthStage class represents the various phases of development that a... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_CropGrowthStage | string | sockg:individuals/46937 | AgCros_INWLREAP_R-202_2011-08-31_Zea_mays_Corn_ | 4896 |




## LinkML Source

<details>

```yaml
name: sockg_mgtGrowthStages_UID
annotations:
  count:
    tag: count
    value: 4896
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_INWLREAP_R-202_2011-08-31_Zea_mays_Corn_
    example_object_type: string
    example_predicate: sockg:mgtGrowthStages_UID
    example_subject: sockg:individuals/46937
    example_subject_type: sockg_CropGrowthStage
from_schema: soc-kg
rank: 1000
domain: sockg_CropGrowthStage
slot_uri: sockg:mgtGrowthStages_UID
alias: sockg_mgtGrowthStages_UID
domain_of:
- sockg_CropGrowthStage
range: string

```
</details>