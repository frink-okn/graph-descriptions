

# Slot: No slot (predicate) name specified (prov_hadPrimarySource)


_No slot (predicate) description specified_






This slot occurs 1256 times.


URI: [prov:hadPrimarySource](http://www.w3.org/ns/prov#hadPrimarySource)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Gwml22GWAquifer](../classes/Gwml22GWAquifer.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |







## Properties

* Range: [OwlThing](../classes/OwlThing.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| gwml22_GW_Aquifer | owl_Thing | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | memgs2:MGS | 1256 |
| owl_Thing | owl_Thing | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | memgs2:MGS | 1256 |




## LinkML Source

<details>

```yaml
name: prov_hadPrimarySource
annotations:
  count:
    tag: count
    value: 1256
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: memgs2:MGS
    example_object_type: owl_Thing
    example_predicate: prov:hadPrimarySource
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: gwml22_GW_Aquifer
- object:
    example_object: memgs2:MGS
    example_object_type: owl_Thing
    example_predicate: prov:hadPrimarySource
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: owl_Thing
from_schema: hydrology-kg
rank: 1000
slot_uri: prov:hadPrimarySource
alias: prov_hadPrimarySource
domain_of:
- gwml22_GW_Aquifer
- owl_Thing
range: owl_Thing

```
</details>