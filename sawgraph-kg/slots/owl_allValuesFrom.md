

# Slot: owl_allValuesFrom


_No slot (predicate) description specified_






This slot occurs 20 times.


URI: [owl:allValuesFrom](http://www.w3.org/2002/07/owl#allValuesFrom)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[OwlClass](../classes/OwlClass.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | owl_Class | _:B1b94d9e751ffada9b24c828d0fa88371 | qudt:Datatype | 13 |
| owl_Restriction | uri | _:B54b5f5e01e0d6114012a8c907ebde248 | qudt:OrderedType | 7 |




## LinkML Source

<details>

```yaml
name: owl_allValuesFrom
annotations:
  count:
    tag: count
    value: 20
description: No slot (predicate) description specified
examples:
- object:
    example_object: qudt:Datatype
    example_object_type: owl_Class
    example_predicate: owl:allValuesFrom
    example_subject: _:B1b94d9e751ffada9b24c828d0fa88371
    example_subject_type: owl_Restriction
- object:
    example_object: qudt:OrderedType
    example_object_type: uri
    example_predicate: owl:allValuesFrom
    example_subject: _:B54b5f5e01e0d6114012a8c907ebde248
    example_subject_type: owl_Restriction
from_schema: sawgraph-kg
rank: 1000
slot_uri: owl:allValuesFrom
alias: owl_allValuesFrom
domain_of:
- owl_Restriction
range: Any
any_of:
- range: uri
- range: owl_Class

```
</details>