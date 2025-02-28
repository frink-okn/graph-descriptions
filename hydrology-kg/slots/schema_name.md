

# Slot: name (schema_name)


_The name of the item._






This slot occurs 33928 times.


URI: [schema:name](https://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [HyfHYFlowPath](../classes/HyfHYFlowPath.md) | No class (type) description specified |  yes  |
| [HyfHYWaterbody](../classes/HyfHYWaterbody.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hyf__HY_Waterbody | string | https://geoconnex.us/nhdplusv2/comid/1001 | Battle Brook | 33928 |
| schema_Place | string | https://geoconnex.us/nhdplusv2/comid/1001 | Battle Brook | 33928 |
| owl_Thing | string | https://geoconnex.us/nhdplusv2/comid/1001 | Battle Brook | 33928 |
| hyf__HY_FlowPath | string | https://geoconnex.us/nhdplusv2/comid/1001 | Battle Brook | 33928 |




## LinkML Source

<details>

```yaml
name: schema_name
annotations:
  count:
    tag: count
    value: 33928
description: The name of the item.
title: name
examples:
- object:
    example_object: Battle Brook
    example_object_type: string
    example_predicate: schema:name
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_Waterbody
- object:
    example_object: Battle Brook
    example_object_type: string
    example_predicate: schema:name
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: schema_Place
- object:
    example_object: Battle Brook
    example_object_type: string
    example_predicate: schema:name
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: owl_Thing
- object:
    example_object: Battle Brook
    example_object_type: string
    example_predicate: schema:name
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_FlowPath
from_schema: hydrology-kg
rank: 1000
slot_uri: schema:name
alias: schema_name
domain_of:
- hyf__HY_FlowPath
- hyf__HY_Waterbody
- owl_Thing
- schema_Place
range: string

```
</details>