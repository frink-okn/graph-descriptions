

# Slot: No slot (predicate) name specified (owl_onProperty)


_No slot (predicate) description specified_






This slot occurs 16 times.


URI: [owl:onProperty](http://www.w3.org/2002/07/owl#onProperty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlObjectProperty](../classes/OwlObjectProperty.md)&nbsp;or&nbsp;<br />[RdfProperty](../classes/RdfProperty.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | rdf_Property | _:B010019df0d645bc4b640e83c5a648a6d | http://w3id.org/fio/v1/epa-frs#fromSystem | 16 |
| owl_Restriction | owl_Thing | _:B010019df0d645bc4b640e83c5a648a6d | http://w3id.org/fio/v1/epa-frs#fromSystem | 16 |
| owl_Restriction | owl_ObjectProperty | _:B2eae44cdbebb2dc00571e0a34d8dba01 | http://w3id.org/fio/v1/epa-frs#ofInterestType | 10 |




## LinkML Source

<details>

```yaml
name: owl_onProperty
annotations:
  count:
    tag: count
    value: 16
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: http://w3id.org/fio/v1/epa-frs#fromSystem
    example_object_type: rdf_Property
    example_predicate: owl:onProperty
    example_subject: _:B010019df0d645bc4b640e83c5a648a6d
    example_subject_type: owl_Restriction
- object:
    example_object: http://w3id.org/fio/v1/epa-frs#fromSystem
    example_object_type: owl_Thing
    example_predicate: owl:onProperty
    example_subject: _:B010019df0d645bc4b640e83c5a648a6d
    example_subject_type: owl_Restriction
- object:
    example_object: http://w3id.org/fio/v1/epa-frs#ofInterestType
    example_object_type: owl_ObjectProperty
    example_predicate: owl:onProperty
    example_subject: _:B2eae44cdbebb2dc00571e0a34d8dba01
    example_subject_type: owl_Restriction
from_schema: fio-kg
rank: 1000
slot_uri: owl:onProperty
alias: owl_onProperty
domain_of:
- owl_Restriction
union_of:
- '{''domain'': ''owl_Restriction''}'
- '{''domain'': ''owl_Class''}'
- '{''domain'': ''rdfs_Class''}'
range: Any
any_of:
- range: owl_ObjectProperty
- range: rdf_Property
- range: owl_Thing

```
</details>