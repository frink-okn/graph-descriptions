

# Slot: No slot (predicate) name specified (rdfs_label)


_No slot (predicate) description specified_






This slot occurs 16791 times.


URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [HyfHYWaterBody](../classes/HyfHYWaterBody.md) | No class (type) description specified |  yes  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hyf__HY_WaterBody | string | https://geoconnex.us/nhdplusv2/comid/10101972 | GNIS_NAME: Moses Pond | 16791 |
| owl_Thing | string | https://geoconnex.us/nhdplusv2/comid/10101972 | GNIS_NAME: Moses Pond | 16791 |




## LinkML Source

<details>

```yaml
name: rdfs_label
annotations:
  count:
    tag: count
    value: 16791
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: 'GNIS_NAME: Moses Pond'
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://geoconnex.us/nhdplusv2/comid/10101972
    example_subject_type: hyf__HY_WaterBody
- object:
    example_object: 'GNIS_NAME: Moses Pond'
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://geoconnex.us/nhdplusv2/comid/10101972
    example_subject_type: owl_Thing
from_schema: hydrology-kg
rank: 1000
slot_uri: rdfs:label
alias: rdfs_label
domain_of:
- hyf__HY_WaterBody
- owl_Thing
range: Any
any_of:
- range: uri
- range: string

```
</details>