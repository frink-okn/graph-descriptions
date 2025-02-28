

# Slot: No slot (predicate) name specified (kwgo_sfContains)


_No slot (predicate) description specified_






This slot occurs 923206 times.


URI: [kwgo:sfContains](http://stko-kwg.geog.ucsb.edu/lod/ontology/sfContains)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [KwgoAdministrativeRegion1](../classes/KwgoAdministrativeRegion1.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [KwgoAdministrativeRegion3](../classes/KwgoAdministrativeRegion3.md) | No class (type) description specified |  yes  |
| [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| kwgo_AdministrativeRegion_1 | kwgo_S2Cell_Level13 | kwgr:administrativeRegion.USA.17 | kwgr:s2.level13.9788714544757997568 | 244704 |
| kwgo_AdministrativeRegion_1 | owl_Thing | kwgr:administrativeRegion.USA.17 | kwgr:s2.level13.9788714544757997568 | 244704 |
| owl_Thing | kwgo_S2Cell_Level13 | kwgr:administrativeRegion.USA.17 | kwgr:s2.level13.9788714544757997568 | 923206 |
| owl_Thing | owl_Thing | kwgr:administrativeRegion.USA.17 | kwgr:s2.level13.9788714544757997568 | 923206 |
| kwgo_AdministrativeRegion_2 | kwgo_S2Cell_Level13 | kwgr:administrativeRegion.USA.17001 | kwgr:s2.level13.9790230015378456576 | 233310 |
| kwgo_AdministrativeRegion_2 | owl_Thing | kwgr:administrativeRegion.USA.17001 | kwgr:s2.level13.9790230015378456576 | 233310 |
| kwgo_AdministrativeRegion_3 | kwgo_S2Cell_Level13 | https://datacommons.org/browser/geoId/1700105742 | kwgr:s2.level13.9790280627273072640 | 195683 |
| kwgo_AdministrativeRegion_3 | owl_Thing | https://datacommons.org/browser/geoId/1700105742 | kwgr:s2.level13.9790280627273072640 | 195683 |




## LinkML Source

<details>

```yaml
name: kwgo_sfContains
annotations:
  count:
    tag: count
    value: 923206
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: kwgr:s2.level13.9788714544757997568
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfContains
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: kwgo_AdministrativeRegion_1
- object:
    example_object: kwgr:s2.level13.9788714544757997568
    example_object_type: owl_Thing
    example_predicate: kwgo:sfContains
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: kwgo_AdministrativeRegion_1
- object:
    example_object: kwgr:s2.level13.9788714544757997568
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfContains
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:s2.level13.9788714544757997568
    example_object_type: owl_Thing
    example_predicate: kwgo:sfContains
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:s2.level13.9790230015378456576
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfContains
    example_subject: kwgr:administrativeRegion.USA.17001
    example_subject_type: kwgo_AdministrativeRegion_2
- object:
    example_object: kwgr:s2.level13.9790230015378456576
    example_object_type: owl_Thing
    example_predicate: kwgo:sfContains
    example_subject: kwgr:administrativeRegion.USA.17001
    example_subject_type: kwgo_AdministrativeRegion_2
- object:
    example_object: kwgr:s2.level13.9790280627273072640
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfContains
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: kwgo_AdministrativeRegion_3
- object:
    example_object: kwgr:s2.level13.9790280627273072640
    example_object_type: owl_Thing
    example_predicate: kwgo:sfContains
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: kwgo_AdministrativeRegion_3
from_schema: spatial-kg
rank: 1000
slot_uri: kwgo:sfContains
alias: kwgo_sfContains
domain_of:
- kwgo_AdministrativeRegion_1
- kwgo_AdministrativeRegion_2
- kwgo_AdministrativeRegion_3
- owl_Thing
range: Any
any_of:
- range: owl_Thing
- range: kwgo_S2Cell_Level13

```
</details>