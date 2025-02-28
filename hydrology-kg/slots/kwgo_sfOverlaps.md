

# Slot: No slot (predicate) name specified (kwgo_sfOverlaps)


_No slot (predicate) description specified_






This slot occurs 55755 times.


URI: [kwgo:sfOverlaps](http://stko-kwg.geog.ucsb.edu/lod/ontology/sfOverlaps)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Gwml22GWAquifer](../classes/Gwml22GWAquifer.md) | No class (type) description specified |  yes  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HyfHYWaterBody](../classes/HyfHYWaterBody.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[Gwml22GWAquifer](../classes/Gwml22GWAquifer.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| gwml22_GW_Aquifer | kwgo_S2Cell_Level13 | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | kwgr:s2.level13.9935671970391654400 | 14211 |
| gwml22_GW_Aquifer | owl_Thing | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | kwgr:s2.level13.9935671970391654400 | 14223 |
| owl_Thing | kwgo_S2Cell_Level13 | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | kwgr:s2.level13.9935671970391654400 | 14211 |
| owl_Thing | owl_Thing | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | kwgr:s2.level13.9935671970391654400 | 55755 |
| kwgo_S2Cell_Level13 | gwml22_GW_Aquifer | kwgr:s2.level13.5522341904064184320 | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.1176 | 14211 |
| kwgo_S2Cell_Level13 | owl_Thing | kwgr:s2.level13.5522341904064184320 | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.1176 | 41520 |
| owl_Thing | gwml22_GW_Aquifer | kwgr:s2.level13.5522341904064184320 | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.1176 | 14223 |
| kwgo_S2Cell_Level13 | hyf__HY_WaterBody | kwgr:s2.level13.5522342316381044736 | https://geoconnex.us/nhdplusv2/comid/802769 | 27309 |
| owl_Thing | hyf__HY_WaterBody | kwgr:s2.level13.5522342316381044736 | https://geoconnex.us/nhdplusv2/comid/802769 | 27309 |




## LinkML Source

<details>

```yaml
name: kwgo_sfOverlaps
annotations:
  count:
    tag: count
    value: 55755
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: kwgr:s2.level13.9935671970391654400
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfOverlaps
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: gwml22_GW_Aquifer
- object:
    example_object: kwgr:s2.level13.9935671970391654400
    example_object_type: owl_Thing
    example_predicate: kwgo:sfOverlaps
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: gwml22_GW_Aquifer
- object:
    example_object: kwgr:s2.level13.9935671970391654400
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfOverlaps
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:s2.level13.9935671970391654400
    example_object_type: owl_Thing
    example_predicate: kwgo:sfOverlaps
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: owl_Thing
- object:
    example_object: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.1176
    example_object_type: gwml22_GW_Aquifer
    example_predicate: kwgo:sfOverlaps
    example_subject: kwgr:s2.level13.5522341904064184320
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.1176
    example_object_type: owl_Thing
    example_predicate: kwgo:sfOverlaps
    example_subject: kwgr:s2.level13.5522341904064184320
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.1176
    example_object_type: gwml22_GW_Aquifer
    example_predicate: kwgo:sfOverlaps
    example_subject: kwgr:s2.level13.5522341904064184320
    example_subject_type: owl_Thing
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/802769
    example_object_type: hyf__HY_WaterBody
    example_predicate: kwgo:sfOverlaps
    example_subject: kwgr:s2.level13.5522342316381044736
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/802769
    example_object_type: hyf__HY_WaterBody
    example_predicate: kwgo:sfOverlaps
    example_subject: kwgr:s2.level13.5522342316381044736
    example_subject_type: owl_Thing
from_schema: hydrology-kg
rank: 1000
slot_uri: kwgo:sfOverlaps
alias: kwgo_sfOverlaps
domain_of:
- gwml22_GW_Aquifer
- kwgo_S2Cell_Level13
- owl_Thing
range: Any
any_of:
- range: hyf__HY_WaterBody
- range: kwgo_S2Cell_Level13
- range: owl_Thing
- range: gwml22_GW_Aquifer

```
</details>