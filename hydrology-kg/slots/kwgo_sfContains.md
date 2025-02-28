

# Slot: No slot (predicate) name specified (kwgo_sfContains)


_No slot (predicate) description specified_






This slot occurs 395 times.


URI: [kwgo:sfContains](http://stko-kwg.geog.ucsb.edu/lod/ontology/sfContains)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Gwml22GWAquifer](../classes/Gwml22GWAquifer.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| gwml22_GW_Aquifer | kwgo_S2Cell_Level13 | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | kwgr:s2.level13.9935675406365491200 | 395 |
| gwml22_GW_Aquifer | owl_Thing | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | kwgr:s2.level13.9935675406365491200 | 395 |
| owl_Thing | kwgo_S2Cell_Level13 | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | kwgr:s2.level13.9935675406365491200 | 395 |
| owl_Thing | owl_Thing | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | kwgr:s2.level13.9935675406365491200 | 395 |




## LinkML Source

<details>

```yaml
name: kwgo_sfContains
annotations:
  count:
    tag: count
    value: 395
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: kwgr:s2.level13.9935675406365491200
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfContains
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: gwml22_GW_Aquifer
- object:
    example_object: kwgr:s2.level13.9935675406365491200
    example_object_type: owl_Thing
    example_predicate: kwgo:sfContains
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: gwml22_GW_Aquifer
- object:
    example_object: kwgr:s2.level13.9935675406365491200
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfContains
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:s2.level13.9935675406365491200
    example_object_type: owl_Thing
    example_predicate: kwgo:sfContains
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: owl_Thing
from_schema: hydrology-kg
rank: 1000
slot_uri: kwgo:sfContains
alias: kwgo_sfContains
domain_of:
- gwml22_GW_Aquifer
- owl_Thing
range: Any
any_of:
- range: kwgo_S2Cell_Level13
- range: owl_Thing

```
</details>