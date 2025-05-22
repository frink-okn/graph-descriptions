

# Slot: owl_minCardinality


_No slot (predicate) description specified_






This slot occurs 11 times.


URI: [owl:minCardinality](http://www.w3.org/2002/07/owl#minCardinality)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Unsignedinteger](../types/Unsignedinteger.md)&nbsp;or&nbsp;<br />[Int32](../types/Int32.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | unsignedinteger | _:B2d99c95457974d6f9fb58deb3a118f49 | 0 | 9 |
| owl_Restriction | int32 | _:Be739d8ba5c2b46b3967f46b720ce1114 | 0 | 2 |




## LinkML Source

<details>

```yaml
name: owl_minCardinality
annotations:
  count:
    tag: count
    value: 11
description: No slot (predicate) description specified
examples:
- object:
    example_object: '0'
    example_object_type: unsignedinteger
    example_predicate: owl:minCardinality
    example_subject: _:B2d99c95457974d6f9fb58deb3a118f49
    example_subject_type: owl_Restriction
- object:
    example_object: '0'
    example_object_type: int32
    example_predicate: owl:minCardinality
    example_subject: _:Be739d8ba5c2b46b3967f46b720ce1114
    example_subject_type: owl_Restriction
from_schema: sawgraph-kg
rank: 1000
slot_uri: owl:minCardinality
alias: owl_minCardinality
domain_of:
- owl_Restriction
range: Any
any_of:
- range: unsignedinteger
- range: int32

```
</details>