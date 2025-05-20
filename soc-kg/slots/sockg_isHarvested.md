

# Slot: No slot (predicate) name specified (sockg_isHarvested)


_No slot (predicate) description specified_






This slot occurs 18356 times.


URI: [sockg:isHarvested](https://idir.uta.edu/sockg-ontology/docs/isHarvested)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |







## Properties

* Range: [SockgHarvest](../classes/SockgHarvest.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ExperimentalUnit | sockg_Harvest | sockg:individuals/51937 | sockg:individuals/174016 | 18356 |




## LinkML Source

<details>

```yaml
name: sockg_isHarvested
annotations:
  count:
    tag: count
    value: 18356
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/174016
    example_object_type: sockg_Harvest
    example_predicate: sockg:isHarvested
    example_subject: sockg:individuals/51937
    example_subject_type: sockg_ExperimentalUnit
from_schema: soc-kg
rank: 1000
domain: sockg_ExperimentalUnit
slot_uri: sockg:isHarvested
alias: sockg_isHarvested
domain_of:
- sockg_ExperimentalUnit
range: sockg_Harvest

```
</details>