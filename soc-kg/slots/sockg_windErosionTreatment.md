

# Slot: No slot (predicate) name specified (sockg_windErosionTreatment)


_No slot (predicate) description specified_






This slot occurs 15 times.


URI: [sockg:windErosionTreatment](https://idir.uta.edu/sockg-ontology/docs/windErosionTreatment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detail... |  yes  |







## Properties

* Range: [SockgTreatment](../classes/SockgTreatment.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WindErosionArea | sockg_Treatment | sockg:individuals/624572 | sockg:individuals/364217 | 15 |




## LinkML Source

<details>

```yaml
name: sockg_windErosionTreatment
annotations:
  count:
    tag: count
    value: 15
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/364217
    example_object_type: sockg_Treatment
    example_predicate: sockg:windErosionTreatment
    example_subject: sockg:individuals/624572
    example_subject_type: sockg_WindErosionArea
from_schema: soc-kg
rank: 1000
domain: sockg_WindErosionArea
slot_uri: sockg:windErosionTreatment
alias: sockg_windErosionTreatment
domain_of:
- sockg_WindErosionArea
range: sockg_Treatment

```
</details>