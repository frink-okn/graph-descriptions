

# Slot: example_ontology_id


_No slot (predicate) description specified_





URI: [example:ontology/id](http://example.org/ontology/id)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)&nbsp;or&nbsp;<br />[xsd:integer](xsd:integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None → integer | example:resource/0006e246-4296-448c-9b81-a0831cad7f1c | example:ontology/id | 1648687 |
| None → string | example:resource/00100b67-f930-4f88-84d8-2c271a59d168 | example:ontology/id | None |


## Comments

* 13840 occurrences with untyped subjects and object type integer.
* 2520 occurrences with untyped subjects and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | example:ontology/id |
| native | climatepub4-kg/:example_ontology_id |




## LinkML Source

<details>
```yaml
name: example_ontology_id
description: No slot (predicate) description specified
comments:
- 13840 occurrences with untyped subjects and object type integer.
- 2520 occurrences with untyped subjects and object type string.
examples:
- description: None → integer
  object:
    example_object: '1648687'
    example_object_type: integer
    example_predicate: example:ontology/id
    example_subject: example:resource/0006e246-4296-448c-9b81-a0831cad7f1c
    example_subject_type: None
- description: None → string
  object:
    example_object: None
    example_object_type: string
    example_predicate: example:ontology/id
    example_subject: example:resource/00100b67-f930-4f88-84d8-2c271a59d168
    example_subject_type: None
from_schema: climatepub4-kg
rank: 1000
slot_uri: example:ontology/id
alias: example_ontology_id
range: Any
any_of:
- range: string
- range: integer

```
</details>