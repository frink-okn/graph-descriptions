

# Slot: No slot (predicate) name specified (geo_hasMetricArea)


_No slot (predicate) description specified_






This slot occurs 249509 times.


URI: [geo:hasMetricArea](http://www.opengis.net/ont/geosparql#hasMetricArea)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| kwgo_S2Cell_Level13 | float | kwgr:s2.level13.5522341869704445952 | 1138180.867994085 | 249509 |
| owl_Thing | float | kwgr:s2.level13.5522341869704445952 | 1138180.867994085 | 249509 |




## LinkML Source

<details>

```yaml
name: geo_hasMetricArea
annotations:
  count:
    tag: count
    value: 249509
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '1138180.867994085'
    example_object_type: float
    example_predicate: geo:hasMetricArea
    example_subject: kwgr:s2.level13.5522341869704445952
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: '1138180.867994085'
    example_object_type: float
    example_predicate: geo:hasMetricArea
    example_subject: kwgr:s2.level13.5522341869704445952
    example_subject_type: owl_Thing
from_schema: spatial-kg
rank: 1000
slot_uri: geo:hasMetricArea
alias: geo_hasMetricArea
domain_of:
- kwgo_S2Cell_Level13
- owl_Thing
range: float

```
</details>