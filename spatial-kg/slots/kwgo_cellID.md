

# Slot: No slot (predicate) name specified (kwgo_cellID)


_No slot (predicate) description specified_






This slot occurs 249509 times.


URI: [kwgo:cellID](http://stko-kwg.geog.ucsb.edu/lod/ontology/cellID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| kwgo_S2Cell_Level13 | integer | kwgr:s2.level13.5522341869704445952 | 5522341869704445952 | 249509 |
| owl_Thing | integer | kwgr:s2.level13.5522341869704445952 | 5522341869704445952 | 249509 |




## LinkML Source

<details>

```yaml
name: kwgo_cellID
annotations:
  count:
    tag: count
    value: 249509
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '5522341869704445952'
    example_object_type: integer
    example_predicate: kwgo:cellID
    example_subject: kwgr:s2.level13.5522341869704445952
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: '5522341869704445952'
    example_object_type: integer
    example_predicate: kwgo:cellID
    example_subject: kwgr:s2.level13.5522341869704445952
    example_subject_type: owl_Thing
from_schema: spatial-kg
rank: 1000
slot_uri: kwgo:cellID
alias: kwgo_cellID
domain_of:
- kwgo_S2Cell_Level13
- owl_Thing
range: integer

```
</details>