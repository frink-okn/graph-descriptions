

# Slot: No slot (predicate) name specified (kwgo_sfTouches)


_No slot (predicate) description specified_






This slot occurs 2007528 times.


URI: [kwgo:sfTouches](http://stko-kwg.geog.ucsb.edu/lod/ontology/sfTouches)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Thing | kwgo_S2Cell_Level13 | kwgr:s2.level13.5522340254796742656 | kwgr:s2.level13.5529493127691239424 | 1996072 |
| owl_Thing | owl_Thing | kwgr:s2.level13.5522340254796742656 | kwgr:s2.level13.5529493127691239424 | 2007528 |
| kwgo_S2Cell_Level13 | owl_Thing | kwgr:s2.level13.5522341869704445952 | kwgr:s2.level13.5522340392235696128 | 1996072 |
| kwgo_S2Cell_Level13 | kwgo_S2Cell_Level13 | kwgr:s2.level13.5522341869704445952 | kwgr:s2.level13.5522341904064184320 | 1984616 |




## LinkML Source

<details>

```yaml
name: kwgo_sfTouches
annotations:
  count:
    tag: count
    value: 2007528
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: kwgr:s2.level13.5529493127691239424
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfTouches
    example_subject: kwgr:s2.level13.5522340254796742656
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:s2.level13.5529493127691239424
    example_object_type: owl_Thing
    example_predicate: kwgo:sfTouches
    example_subject: kwgr:s2.level13.5522340254796742656
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:s2.level13.5522340392235696128
    example_object_type: owl_Thing
    example_predicate: kwgo:sfTouches
    example_subject: kwgr:s2.level13.5522341869704445952
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: kwgr:s2.level13.5522341904064184320
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfTouches
    example_subject: kwgr:s2.level13.5522341869704445952
    example_subject_type: kwgo_S2Cell_Level13
from_schema: spatial-kg
rank: 1000
slot_uri: kwgo:sfTouches
alias: kwgo_sfTouches
domain_of:
- kwgo_S2Cell_Level13
- owl_Thing
range: Any
any_of:
- range: owl_Thing
- range: kwgo_S2Cell_Level13

```
</details>