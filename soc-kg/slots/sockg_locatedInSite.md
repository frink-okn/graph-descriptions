

# Slot: No slot (predicate) name specified (sockg_locatedInSite)


_No slot (predicate) description specified_






This slot occurs 3803 times.


URI: [sockg:locatedInSite](https://idir.uta.edu/sockg-ontology/docs/locatedInSite)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |







## Properties

* Range: [SockgSite](../classes/SockgSite.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ExperimentalUnit | sockg_Site | sockg:individuals/51937 | sockg:individuals/231073 | 3803 |




## LinkML Source

<details>

```yaml
name: sockg_locatedInSite
annotations:
  count:
    tag: count
    value: 3803
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/231073
    example_object_type: sockg_Site
    example_predicate: sockg:locatedInSite
    example_subject: sockg:individuals/51937
    example_subject_type: sockg_ExperimentalUnit
from_schema: soc-kg
rank: 1000
domain: sockg_ExperimentalUnit
slot_uri: sockg:locatedInSite
alias: sockg_locatedInSite
domain_of:
- sockg_ExperimentalUnit
range: sockg_Site

```
</details>