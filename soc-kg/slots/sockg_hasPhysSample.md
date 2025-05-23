

# Slot: No slot (predicate) name specified (sockg_hasPhysSample)


_No slot (predicate) description specified_






This slot occurs 28082 times.


URI: [sockg:hasPhysSample](https://idir.uta.edu/sockg-ontology/docs/hasPhysSample)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |







## Properties

* Range: [SockgSoilPhysicalSample](../classes/SockgSoilPhysicalSample.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ExperimentalUnit | sockg_SoilPhysicalSample | sockg:individuals/51937 | sockg:individuals/326976 | 28082 |




## LinkML Source

<details>

```yaml
name: sockg_hasPhysSample
annotations:
  count:
    tag: count
    value: 28082
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/326976
    example_object_type: sockg_SoilPhysicalSample
    example_predicate: sockg:hasPhysSample
    example_subject: sockg:individuals/51937
    example_subject_type: sockg_ExperimentalUnit
from_schema: soc-kg
rank: 1000
domain: sockg_ExperimentalUnit
slot_uri: sockg:hasPhysSample
alias: sockg_hasPhysSample
domain_of:
- sockg_ExperimentalUnit
range: sockg_SoilPhysicalSample

```
</details>