

# Slot: owl_maxCardinality


_No slot (predicate) description specified_






This slot occurs 31 times.


URI: [owl:maxCardinality](http://www.w3.org/2002/07/owl#maxCardinality)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Unsignedinteger](../types/Unsignedinteger.md)&nbsp;or&nbsp;<br />[Int32](../types/Int32.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | int32 | _:B1483a74553e695096917e036e115647b | 1 | 7 |
| owl_Restriction | integer | _:B1eaf986f62f70bde3920fc763297ba4b | 1 | 20 |
| owl_Restriction | unsignedinteger | _:B2d418fab187385bd606ec62687307b1d | 1 | 4 |




## LinkML Source

<details>

```yaml
name: owl_maxCardinality
annotations:
  count:
    tag: count
    value: 31
description: No slot (predicate) description specified
examples:
- object:
    example_object: '1'
    example_object_type: int32
    example_predicate: owl:maxCardinality
    example_subject: _:B1483a74553e695096917e036e115647b
    example_subject_type: owl_Restriction
- object:
    example_object: '1'
    example_object_type: integer
    example_predicate: owl:maxCardinality
    example_subject: _:B1eaf986f62f70bde3920fc763297ba4b
    example_subject_type: owl_Restriction
- object:
    example_object: '1'
    example_object_type: unsignedinteger
    example_predicate: owl:maxCardinality
    example_subject: _:B2d418fab187385bd606ec62687307b1d
    example_subject_type: owl_Restriction
from_schema: sawgraph-kg
rank: 1000
slot_uri: owl:maxCardinality
alias: owl_maxCardinality
domain_of:
- owl_Restriction
range: Any
any_of:
- range: unsignedinteger
- range: int32
- range: integer

```
</details>