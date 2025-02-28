

# Slot: No slot (predicate) name specified (kwgo_sfCrosses)


_No slot (predicate) description specified_






This slot occurs 395346 times.


URI: [kwgo:sfCrosses](http://stko-kwg.geog.ucsb.edu/lod/ontology/sfCrosses)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [HyfHYFlowPath](../classes/HyfHYFlowPath.md) | No class (type) description specified |  yes  |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | No class (type) description specified |  yes  |
| [HyfHYWaterbody](../classes/HyfHYWaterbody.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HyfHYWaterbody](../classes/HyfHYWaterbody.md)&nbsp;or&nbsp;<br />[HyfHYFlowPath](../classes/HyfHYFlowPath.md)&nbsp;or&nbsp;<br />[SchemaPlace](../classes/SchemaPlace.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Thing | hyf__HY_Waterbody | kwgr:s2.level13.5522339705040928768 | https://geoconnex.us/nhdplusv2/comid/166195770 | 197673 |
| owl_Thing | schema_Place | kwgr:s2.level13.5522339705040928768 | https://geoconnex.us/nhdplusv2/comid/166195770 | 197673 |
| owl_Thing | owl_Thing | kwgr:s2.level13.5522339705040928768 | https://geoconnex.us/nhdplusv2/comid/166195770 | 395346 |
| owl_Thing | hyf__HY_FlowPath | kwgr:s2.level13.5522339705040928768 | https://geoconnex.us/nhdplusv2/comid/166195770 | 197673 |
| kwgo_S2Cell_Level13 | hyf__HY_Waterbody | kwgr:s2.level13.5522341904064184320 | https://geoconnex.us/nhdplusv2/comid/803107 | 94779 |
| kwgo_S2Cell_Level13 | schema_Place | kwgr:s2.level13.5522341904064184320 | https://geoconnex.us/nhdplusv2/comid/803107 | 94779 |
| kwgo_S2Cell_Level13 | owl_Thing | kwgr:s2.level13.5522341904064184320 | https://geoconnex.us/nhdplusv2/comid/803107 | 94779 |
| kwgo_S2Cell_Level13 | hyf__HY_FlowPath | kwgr:s2.level13.5522341904064184320 | https://geoconnex.us/nhdplusv2/comid/803107 | 94779 |
| hyf__HY_Waterbody | kwgo_S2Cell_Level13 | https://geoconnex.us/nhdplusv2/comid/1001 | kwgr:s2.level13.5522769236130267136 | 94779 |
| hyf__HY_Waterbody | owl_Thing | https://geoconnex.us/nhdplusv2/comid/1001 | kwgr:s2.level13.5522769236130267136 | 197673 |
| schema_Place | kwgo_S2Cell_Level13 | https://geoconnex.us/nhdplusv2/comid/1001 | kwgr:s2.level13.5522769236130267136 | 94779 |
| schema_Place | owl_Thing | https://geoconnex.us/nhdplusv2/comid/1001 | kwgr:s2.level13.5522769236130267136 | 197673 |
| owl_Thing | kwgo_S2Cell_Level13 | https://geoconnex.us/nhdplusv2/comid/1001 | kwgr:s2.level13.5522769236130267136 | 94779 |
| hyf__HY_FlowPath | kwgo_S2Cell_Level13 | https://geoconnex.us/nhdplusv2/comid/1001 | kwgr:s2.level13.5522769236130267136 | 94779 |
| hyf__HY_FlowPath | owl_Thing | https://geoconnex.us/nhdplusv2/comid/1001 | kwgr:s2.level13.5522769236130267136 | 197673 |




## LinkML Source

<details>

```yaml
name: kwgo_sfCrosses
annotations:
  count:
    tag: count
    value: 395346
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/166195770
    example_object_type: hyf__HY_Waterbody
    example_predicate: kwgo:sfCrosses
    example_subject: kwgr:s2.level13.5522339705040928768
    example_subject_type: owl_Thing
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/166195770
    example_object_type: schema_Place
    example_predicate: kwgo:sfCrosses
    example_subject: kwgr:s2.level13.5522339705040928768
    example_subject_type: owl_Thing
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/166195770
    example_object_type: owl_Thing
    example_predicate: kwgo:sfCrosses
    example_subject: kwgr:s2.level13.5522339705040928768
    example_subject_type: owl_Thing
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/166195770
    example_object_type: hyf__HY_FlowPath
    example_predicate: kwgo:sfCrosses
    example_subject: kwgr:s2.level13.5522339705040928768
    example_subject_type: owl_Thing
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/803107
    example_object_type: hyf__HY_Waterbody
    example_predicate: kwgo:sfCrosses
    example_subject: kwgr:s2.level13.5522341904064184320
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/803107
    example_object_type: schema_Place
    example_predicate: kwgo:sfCrosses
    example_subject: kwgr:s2.level13.5522341904064184320
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/803107
    example_object_type: owl_Thing
    example_predicate: kwgo:sfCrosses
    example_subject: kwgr:s2.level13.5522341904064184320
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/803107
    example_object_type: hyf__HY_FlowPath
    example_predicate: kwgo:sfCrosses
    example_subject: kwgr:s2.level13.5522341904064184320
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: kwgr:s2.level13.5522769236130267136
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfCrosses
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_Waterbody
- object:
    example_object: kwgr:s2.level13.5522769236130267136
    example_object_type: owl_Thing
    example_predicate: kwgo:sfCrosses
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_Waterbody
- object:
    example_object: kwgr:s2.level13.5522769236130267136
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfCrosses
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: schema_Place
- object:
    example_object: kwgr:s2.level13.5522769236130267136
    example_object_type: owl_Thing
    example_predicate: kwgo:sfCrosses
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: schema_Place
- object:
    example_object: kwgr:s2.level13.5522769236130267136
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfCrosses
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:s2.level13.5522769236130267136
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfCrosses
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_FlowPath
- object:
    example_object: kwgr:s2.level13.5522769236130267136
    example_object_type: owl_Thing
    example_predicate: kwgo:sfCrosses
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_FlowPath
from_schema: hydrology-kg
rank: 1000
slot_uri: kwgo:sfCrosses
alias: kwgo_sfCrosses
domain_of:
- hyf__HY_FlowPath
- hyf__HY_Waterbody
- kwgo_S2Cell_Level13
- owl_Thing
- schema_Place
range: Any
any_of:
- range: kwgo_S2Cell_Level13
- range: owl_Thing
- range: hyf__HY_Waterbody
- range: hyf__HY_FlowPath
- range: schema_Place

```
</details>