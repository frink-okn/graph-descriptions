

# Slot: No slot (predicate) name specified (rdfs_comment)


_No slot (predicate) description specified_






This slot occurs 51629 times.


URI: [rdfs:comment](http://www.w3.org/2000/01/rdf-schema#comment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Gwml22GWAquifer](../classes/Gwml22GWAquifer.md) | No class (type) description specified |  yes  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [HyfHYWaterBody](../classes/HyfHYWaterBody.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| gwml22_GW_Aquifer | string | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | Original MGS IDs: 9110 9363 9524 | 1256 |
| owl_Thing | string | http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001 | Original MGS IDs: 9110 9363 9524 | 51629 |
| hyf__HY_WaterBody | string | https://geoconnex.us/nhdplusv2/comid/10101972 | COMID: 10101972 | 50373 |




## LinkML Source

<details>

```yaml
name: rdfs_comment
annotations:
  count:
    tag: count
    value: 51629
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: 'Original MGS IDs: 9110 9363 9524'
    example_object_type: string
    example_predicate: rdfs:comment
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: gwml22_GW_Aquifer
- object:
    example_object: 'Original MGS IDs: 9110 9363 9524'
    example_object_type: string
    example_predicate: rdfs:comment
    example_subject: http://sawgraph.spatialai.org/v1/me_mgs_data#d.MGS-Aquifer.0001
    example_subject_type: owl_Thing
- object:
    example_object: 'COMID: 10101972'
    example_object_type: string
    example_predicate: rdfs:comment
    example_subject: https://geoconnex.us/nhdplusv2/comid/10101972
    example_subject_type: hyf__HY_WaterBody
from_schema: hydrology-kg
rank: 1000
slot_uri: rdfs:comment
alias: rdfs_comment
domain_of:
- gwml22_GW_Aquifer
- hyf__HY_WaterBody
- owl_Thing
range: Any
any_of:
- range: uri
- range: string

```
</details>