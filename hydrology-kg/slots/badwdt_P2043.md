

# Slot: No slot (predicate) name specified (badwdt_P2043)


_No slot (predicate) description specified_






This slot occurs 68837 times.


URI: [badwdt:P2043](https://www.wikidata.org/wiki/Property:P2043)



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

* Range: [xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hyf__HY_Waterbody | float | https://geoconnex.us/nhdplusv2/comid/1001 | 4.252 | 68837 |
| schema_Place | float | https://geoconnex.us/nhdplusv2/comid/1001 | 4.252 | 68837 |
| owl_Thing | float | https://geoconnex.us/nhdplusv2/comid/1001 | 4.252 | 68837 |
| hyf__HY_FlowPath | float | https://geoconnex.us/nhdplusv2/comid/1001 | 4.252 | 68837 |




## LinkML Source

<details>

```yaml
name: badwdt_P2043
annotations:
  count:
    tag: count
    value: 68837
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '4.252'
    example_object_type: float
    example_predicate: badwdt:P2043
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_Waterbody
- object:
    example_object: '4.252'
    example_object_type: float
    example_predicate: badwdt:P2043
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: schema_Place
- object:
    example_object: '4.252'
    example_object_type: float
    example_predicate: badwdt:P2043
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: owl_Thing
- object:
    example_object: '4.252'
    example_object_type: float
    example_predicate: badwdt:P2043
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_FlowPath
from_schema: hydrology-kg
rank: 1000
slot_uri: badwdt:P2043
alias: badwdt_P2043
domain_of:
- hyf__HY_FlowPath
- hyf__HY_Waterbody
- owl_Thing
- schema_Place
range: float

```
</details>