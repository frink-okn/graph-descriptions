

# Slot: example_ontology_id


_No slot (predicate) description specified_






This slot occurs 16360 times.


URI: [example:ontology/id](http://example.org/ontology/id)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | integer | example:resource/0006e246-4296-448c-9b81-a0831cad7f1c | 1648687 | 13840 |
| None | string | example:resource/00100b67-f930-4f88-84d8-2c271a59d168 | None | 2520 |




## LinkML Source

<details>

```yaml
name: example_ontology_id
annotations:
  count:
    tag: count
    value: 16360
  integer:
    tag: integer
    value: 13840
  string:
    tag: string
    value: 2520
description: No slot (predicate) description specified
examples:
- object:
    example_object: '1648687'
    example_object_type: integer
    example_predicate: example:ontology/id
    example_subject: example:resource/0006e246-4296-448c-9b81-a0831cad7f1c
    example_subject_type: None
- object:
    example_object: None
    example_object_type: string
    example_predicate: example:ontology/id
    example_subject: example:resource/00100b67-f930-4f88-84d8-2c271a59d168
    example_subject_type: None
from_schema: dream-kg
rank: 1000
slot_uri: example:ontology/id
alias: example_ontology_id
range: Any
any_of:
- range: integer
- range: string

```
</details>