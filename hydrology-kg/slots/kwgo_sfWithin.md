

# Slot: No slot (predicate) name specified (kwgo_sfWithin)


_No slot (predicate) description specified_






This slot occurs 906 times.


URI: [kwgo:sfWithin](http://stko-kwg.geog.ucsb.edu/lod/ontology/sfWithin)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HyfHYWaterBody](../classes/HyfHYWaterBody.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[Gwml22GWAquifer](../classes/Gwml22GWAquifer.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| kwgo_S2Cell_Level13 | hyf__HY_WaterBody | kwgr:s2.level13.5522837268412235776 | https://geoconnex.us/nhdplusv2/comid/5194604 | 511 |
| kwgo_S2Cell_Level13 | owl_Thing | kwgr:s2.level13.5522837268412235776 | https://geoconnex.us/nhdplusv2/comid/5194604 | 906 |
| owl_Thing | hyf__HY_WaterBody | kwgr:s2.level13.5522837268412235776 | https://geoconnex.us/nhdplusv2/comid/5194604 | 511 |
| owl_Thing | owl_Thing | kwgr:s2.level13.5522837268412235776 | https://geoconnex.us/nhdplusv2/comid/5194604 | 906 |
| kwgo_S2Cell_Level13 | gwml22_GW_Aquifer | kwgr:s2.level13.5523896132469522432 | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.1195 | 395 |
| owl_Thing | gwml22_GW_Aquifer | kwgr:s2.level13.5523896132469522432 | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.1195 | 395 |




## LinkML Source

<details>

```yaml
name: kwgo_sfWithin
annotations:
  count:
    tag: count
    value: 906
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/5194604
    example_object_type: hyf__HY_WaterBody
    example_predicate: kwgo:sfWithin
    example_subject: kwgr:s2.level13.5522837268412235776
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/5194604
    example_object_type: owl_Thing
    example_predicate: kwgo:sfWithin
    example_subject: kwgr:s2.level13.5522837268412235776
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/5194604
    example_object_type: hyf__HY_WaterBody
    example_predicate: kwgo:sfWithin
    example_subject: kwgr:s2.level13.5522837268412235776
    example_subject_type: owl_Thing
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/5194604
    example_object_type: owl_Thing
    example_predicate: kwgo:sfWithin
    example_subject: kwgr:s2.level13.5522837268412235776
    example_subject_type: owl_Thing
- object:
    example_object: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.1195
    example_object_type: gwml22_GW_Aquifer
    example_predicate: kwgo:sfWithin
    example_subject: kwgr:s2.level13.5523896132469522432
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.1195
    example_object_type: gwml22_GW_Aquifer
    example_predicate: kwgo:sfWithin
    example_subject: kwgr:s2.level13.5523896132469522432
    example_subject_type: owl_Thing
from_schema: hydrology-kg
rank: 1000
slot_uri: kwgo:sfWithin
alias: kwgo_sfWithin
domain_of:
- kwgo_S2Cell_Level13
- owl_Thing
range: Any
any_of:
- range: hyf__HY_WaterBody
- range: owl_Thing
- range: gwml22_GW_Aquifer

```
</details>