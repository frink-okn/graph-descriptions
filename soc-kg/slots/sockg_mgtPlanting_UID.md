

# Slot: No slot (predicate) name specified (sockg_mgtPlanting_UID)


_No slot (predicate) description specified_






This slot occurs 23450 times.


URI: [sockg:mgtPlanting_UID](https://idir.uta.edu/sockg-ontology/docs/mgtPlanting_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPlantingEvent](../classes/SockgPlantingEvent.md) | An event involving the act of planting, which includes considerations for spa... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_PlantingEvent | string | sockg:individuals/203988 | AgCros_MNMOFS_71_2004-11-04_Secale_cereale_Rye_ | 23450 |




## LinkML Source

<details>

```yaml
name: sockg_mgtPlanting_UID
annotations:
  count:
    tag: count
    value: 23450
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_MNMOFS_71_2004-11-04_Secale_cereale_Rye_
    example_object_type: string
    example_predicate: sockg:mgtPlanting_UID
    example_subject: sockg:individuals/203988
    example_subject_type: sockg_PlantingEvent
from_schema: soc-kg
rank: 1000
domain: sockg_PlantingEvent
slot_uri: sockg:mgtPlanting_UID
alias: sockg_mgtPlanting_UID
domain_of:
- sockg_PlantingEvent
range: string

```
</details>