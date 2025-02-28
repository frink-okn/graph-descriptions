

# Slot: No slot (predicate) name specified (memgs2_SAWidAquifer)


_No slot (predicate) description specified_






This slot occurs 1256 times.


URI: [memgs2:SAWidAquifer](http://sawgraph.spatialai.org/v1/me_mgs#SAWidAquifer)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Gwml22GWAquifer](../classes/Gwml22GWAquifer.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| gwml22_GW_Aquifer | string | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | 1 | 1256 |
| owl_Thing | string | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | 1 | 1256 |




## LinkML Source

<details>

```yaml
name: memgs2_SAWidAquifer
annotations:
  count:
    tag: count
    value: 1256
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '1'
    example_object_type: string
    example_predicate: memgs2:SAWidAquifer
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: gwml22_GW_Aquifer
- object:
    example_object: '1'
    example_object_type: string
    example_predicate: memgs2:SAWidAquifer
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: owl_Thing
from_schema: hydrology-kg
rank: 1000
slot_uri: memgs2:SAWidAquifer
alias: memgs2_SAWidAquifer
domain_of:
- gwml22_GW_Aquifer
- owl_Thing
range: string

```
</details>