

# Slot: No slot (predicate) name specified (owl_maxCardinality)


_No slot (predicate) description specified_






This slot occurs 31 times.


URI: [owl:maxCardinality](http://www.w3.org/2002/07/owl#maxCardinality)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Unsignedinteger](../types/Unsignedinteger.md)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[Int32](../types/Int32.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | integer | _:B040a3495e8a7e81253a5a9e35c747f26 | 1 | 20 |
| owl_Restriction | int32 | _:B2884e26759d573de491a452ee02cd5be | 1 | 7 |
| owl_Restriction | unsignedinteger | _:B9fab7a8c48e9f0c2663ef5cda30b2842 | 1 | 4 |




## LinkML Source

<details>

```yaml
name: owl_maxCardinality
annotations:
  count:
    tag: count
    value: 31
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '1'
    example_object_type: integer
    example_predicate: owl:maxCardinality
    example_subject: _:B040a3495e8a7e81253a5a9e35c747f26
    example_subject_type: owl_Restriction
- object:
    example_object: '1'
    example_object_type: int32
    example_predicate: owl:maxCardinality
    example_subject: _:B2884e26759d573de491a452ee02cd5be
    example_subject_type: owl_Restriction
- object:
    example_object: '1'
    example_object_type: unsignedinteger
    example_predicate: owl:maxCardinality
    example_subject: _:B9fab7a8c48e9f0c2663ef5cda30b2842
    example_subject_type: owl_Restriction
from_schema: sawgraph-kg
rank: 1000
slot_uri: owl:maxCardinality
alias: owl_maxCardinality
domain_of:
- owl_Restriction
union_of:
- '{''domain'': ''owl_Class''}'
- '{''domain'': ''owl_Restriction''}'
- '{''domain'': ''rdfs_Class''}'
range: Any
any_of:
- range: unsignedinteger
- range: rdfs_Literal
- range: integer
- range: int32

```
</details>