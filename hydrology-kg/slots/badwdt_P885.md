

# Slot: No slot (predicate) name specified (badwdt_P885)


_No slot (predicate) description specified_






This slot occurs 68837 times.


URI: [badwdt:P885](https://www.wikidata.org/wiki/Property:P885)



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

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hyf__HY_Waterbody | geo_Feature | https://geoconnex.us/nhdplusv2/comid/1001 | https://geoconnex.us/nhdplusv2/comid/1001.head | 68837 |
| hyf__HY_Waterbody | owl_Thing | https://geoconnex.us/nhdplusv2/comid/1001 | https://geoconnex.us/nhdplusv2/comid/1001.head | 68837 |
| schema_Place | geo_Feature | https://geoconnex.us/nhdplusv2/comid/1001 | https://geoconnex.us/nhdplusv2/comid/1001.head | 68837 |
| schema_Place | owl_Thing | https://geoconnex.us/nhdplusv2/comid/1001 | https://geoconnex.us/nhdplusv2/comid/1001.head | 68837 |
| owl_Thing | geo_Feature | https://geoconnex.us/nhdplusv2/comid/1001 | https://geoconnex.us/nhdplusv2/comid/1001.head | 68837 |
| owl_Thing | owl_Thing | https://geoconnex.us/nhdplusv2/comid/1001 | https://geoconnex.us/nhdplusv2/comid/1001.head | 68837 |
| hyf__HY_FlowPath | geo_Feature | https://geoconnex.us/nhdplusv2/comid/1001 | https://geoconnex.us/nhdplusv2/comid/1001.head | 68837 |
| hyf__HY_FlowPath | owl_Thing | https://geoconnex.us/nhdplusv2/comid/1001 | https://geoconnex.us/nhdplusv2/comid/1001.head | 68837 |




## LinkML Source

<details>

```yaml
name: badwdt_P885
annotations:
  count:
    tag: count
    value: 68837
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/1001.head
    example_object_type: geo_Feature
    example_predicate: badwdt:P885
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_Waterbody
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/1001.head
    example_object_type: owl_Thing
    example_predicate: badwdt:P885
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_Waterbody
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/1001.head
    example_object_type: geo_Feature
    example_predicate: badwdt:P885
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: schema_Place
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/1001.head
    example_object_type: owl_Thing
    example_predicate: badwdt:P885
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: schema_Place
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/1001.head
    example_object_type: geo_Feature
    example_predicate: badwdt:P885
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: owl_Thing
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/1001.head
    example_object_type: owl_Thing
    example_predicate: badwdt:P885
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: owl_Thing
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/1001.head
    example_object_type: geo_Feature
    example_predicate: badwdt:P885
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_FlowPath
- object:
    example_object: https://geoconnex.us/nhdplusv2/comid/1001.head
    example_object_type: owl_Thing
    example_predicate: badwdt:P885
    example_subject: https://geoconnex.us/nhdplusv2/comid/1001
    example_subject_type: hyf__HY_FlowPath
from_schema: hydrology-kg
rank: 1000
slot_uri: badwdt:P885
alias: badwdt_P885
domain_of:
- hyf__HY_FlowPath
- hyf__HY_Waterbody
- owl_Thing
- schema_Place
range: Any
any_of:
- range: geo_Feature
- range: owl_Thing

```
</details>