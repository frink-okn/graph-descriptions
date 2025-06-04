

# Slot: No slot (predicate) name specified (owl_allValuesFrom)


_No slot (predicate) description specified_






This slot occurs 20 times.


URI: [owl:allValuesFrom](http://www.w3.org/2002/07/owl#allValuesFrom)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlClass](../classes/OwlClass.md)&nbsp;or&nbsp;<br />[RdfsDatatype](../classes/RdfsDatatype.md)&nbsp;or&nbsp;<br />[RdfsClass](../classes/RdfsClass.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | owl_Thing | _:B028f2531b3b2d380ecbddd6893801342 | qudt:EnumeratedValue | 20 |
| owl_Restriction | owl_Class | _:B028f2531b3b2d380ecbddd6893801342 | qudt:EnumeratedValue | 13 |
| owl_Restriction | rdfs_Class | _:B028f2531b3b2d380ecbddd6893801342 | qudt:EnumeratedValue | 20 |
| owl_Restriction | rdfs_Datatype | _:Bc72f0a6928d26f5f09981dbdf8032c33 | xsd:string | 2 |




## LinkML Source

<details>

```yaml
name: owl_allValuesFrom
annotations:
  count:
    tag: count
    value: 20
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: qudt:EnumeratedValue
    example_object_type: owl_Thing
    example_predicate: owl:allValuesFrom
    example_subject: _:B028f2531b3b2d380ecbddd6893801342
    example_subject_type: owl_Restriction
- object:
    example_object: qudt:EnumeratedValue
    example_object_type: owl_Class
    example_predicate: owl:allValuesFrom
    example_subject: _:B028f2531b3b2d380ecbddd6893801342
    example_subject_type: owl_Restriction
- object:
    example_object: qudt:EnumeratedValue
    example_object_type: rdfs_Class
    example_predicate: owl:allValuesFrom
    example_subject: _:B028f2531b3b2d380ecbddd6893801342
    example_subject_type: owl_Restriction
- object:
    example_object: xsd:string
    example_object_type: rdfs_Datatype
    example_predicate: owl:allValuesFrom
    example_subject: _:Bc72f0a6928d26f5f09981dbdf8032c33
    example_subject_type: owl_Restriction
from_schema: sawgraph-kg
rank: 1000
slot_uri: owl:allValuesFrom
alias: owl_allValuesFrom
domain_of:
- owl_Restriction
union_of:
- '{''domain'': ''owl_Class''}'
- '{''domain'': ''owl_Restriction''}'
- '{''domain'': ''rdfs_Class''}'
range: Any
any_of:
- range: owl_Thing
- range: owl_Class
- range: rdfs_Datatype
- range: rdfs_Class

```
</details>