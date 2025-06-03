

# Slot: No slot (predicate) name specified (owl_minCardinality)


_No slot (predicate) description specified_






This slot occurs 11 times.


URI: [owl:minCardinality](http://www.w3.org/2002/07/owl#minCardinality)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Unsignedinteger](../types/Unsignedinteger.md)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[Int32](../types/Int32.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | int32 | _:B034dc74789599b0e98c60b3a0f255193 | 0 | 2 |
| owl_Restriction | unsignedinteger | _:B07369d6468d5ba92651edaaff1cab22e | 0 | 9 |




## LinkML Source

<details>

```yaml
name: owl_minCardinality
annotations:
  count:
    tag: count
    value: 11
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0'
    example_object_type: int32
    example_predicate: owl:minCardinality
    example_subject: _:B034dc74789599b0e98c60b3a0f255193
    example_subject_type: owl_Restriction
- object:
    example_object: '0'
    example_object_type: unsignedinteger
    example_predicate: owl:minCardinality
    example_subject: _:B07369d6468d5ba92651edaaff1cab22e
    example_subject_type: owl_Restriction
from_schema: sawgraph-kg
rank: 1000
slot_uri: owl:minCardinality
alias: owl_minCardinality
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
- range: int32

```
</details>