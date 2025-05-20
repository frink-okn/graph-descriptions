

# Slot: No slot (predicate) name specified (sockg_measWindErosionArea_UID)


_No slot (predicate) description specified_






This slot occurs 15 times.


URI: [sockg:measWindErosionArea_UID](https://idir.uta.edu/sockg-ontology/docs/measWindErosionArea_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detail... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WindErosionArea | string | sockg:individuals/624572 | AgCros_TXBSWEWC_COMP2_2001-03-15 | 15 |




## LinkML Source

<details>

```yaml
name: sockg_measWindErosionArea_UID
annotations:
  count:
    tag: count
    value: 15
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_TXBSWEWC_COMP2_2001-03-15
    example_object_type: string
    example_predicate: sockg:measWindErosionArea_UID
    example_subject: sockg:individuals/624572
    example_subject_type: sockg_WindErosionArea
from_schema: soc-kg
rank: 1000
domain: sockg_WindErosionArea
slot_uri: sockg:measWindErosionArea_UID
alias: sockg_measWindErosionArea_UID
domain_of:
- sockg_WindErosionArea
range: string

```
</details>