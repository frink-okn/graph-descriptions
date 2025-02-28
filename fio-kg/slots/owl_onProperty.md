

# Slot: No slot (predicate) name specified (owl_onProperty)


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [owl:onProperty](http://www.w3.org/2002/07/owl#onProperty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlObjectProperty](../classes/OwlObjectProperty.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[RdfProperty](../classes/RdfProperty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | [owl_onProperty](../slots/owl_onProperty.md) | domain | [owl_onProperty](../slots/owl_onProperty.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | owl_ObjectProperty | _:b0 | fio:ofIndustry | 1 |
| owl_Restriction | rdf_Property | _:b0 | fio:ofIndustry | 1 |




## LinkML Source

<details>

```yaml
name: owl_onProperty
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: fio:ofIndustry
    example_object_type: owl_ObjectProperty
    example_predicate: owl:onProperty
    example_subject: _:b0
    example_subject_type: owl_Restriction
- object:
    example_object: fio:ofIndustry
    example_object_type: rdf_Property
    example_predicate: owl:onProperty
    example_subject: _:b0
    example_subject_type: owl_Restriction
from_schema: fio-kg
rank: 1000
domain: owl_onProperty
slot_uri: owl:onProperty
alias: owl_onProperty
domain_of:
- owl_Restriction
range: Any
any_of:
- range: owl_ObjectProperty
- range: uri
- range: rdf_Property

```
</details>