

# Slot: owl_members


_No slot (predicate) description specified_






This slot occurs 14 times.


URI: [owl:members](http://www.w3.org/2002/07/owl#members)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlAllDisjointClasses](../classes/OwlAllDisjointClasses.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_AllDisjointClasses | uri | _:b0 | _:b1 | 14 |




## LinkML Source

<details>

```yaml
name: owl_members
annotations:
  count:
    tag: count
    value: 14
description: No slot (predicate) description specified
examples:
- object:
    example_object: _:b1
    example_object_type: uri
    example_predicate: owl:members
    example_subject: _:b0
    example_subject_type: owl_AllDisjointClasses
from_schema: sudokn-kg
rank: 1000
slot_uri: owl:members
alias: owl_members
domain_of:
- owl_AllDisjointClasses
range: uri

```
</details>