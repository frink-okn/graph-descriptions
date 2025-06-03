

# Slot: No slot (predicate) name specified (owl_onProperty)


_No slot (predicate) description specified_






This slot occurs 62 times.


URI: [owl:onProperty](http://www.w3.org/2002/07/owl#onProperty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlAnnotationProperty](../classes/OwlAnnotationProperty.md)&nbsp;or&nbsp;<br />[OwlDatatypeProperty](../classes/OwlDatatypeProperty.md)&nbsp;or&nbsp;<br />[RdfProperty](../classes/RdfProperty.md)&nbsp;or&nbsp;<br />[OwlObjectProperty](../classes/OwlObjectProperty.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | owl_Thing | _:B028f2531b3b2d380ecbddd6893801342 | qudt:enumeratedValue | 62 |
| owl_Restriction | rdf_Property | _:B028f2531b3b2d380ecbddd6893801342 | qudt:enumeratedValue | 16 |
| owl_Restriction | owl_ObjectProperty | _:B028f2531b3b2d380ecbddd6893801342 | qudt:enumeratedValue | 8 |
| owl_Restriction | owl_DatatypeProperty | _:B2884e26759d573de491a452ee02cd5be | qudt:abbreviation | 2 |
| owl_Restriction | owl_AnnotationProperty | _:B3132a05d8995a22458a38f94cdb45e45 | dct:description | 1 |




## LinkML Source

<details>

```yaml
name: owl_onProperty
annotations:
  count:
    tag: count
    value: 62
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: qudt:enumeratedValue
    example_object_type: owl_Thing
    example_predicate: owl:onProperty
    example_subject: _:B028f2531b3b2d380ecbddd6893801342
    example_subject_type: owl_Restriction
- object:
    example_object: qudt:enumeratedValue
    example_object_type: rdf_Property
    example_predicate: owl:onProperty
    example_subject: _:B028f2531b3b2d380ecbddd6893801342
    example_subject_type: owl_Restriction
- object:
    example_object: qudt:enumeratedValue
    example_object_type: owl_ObjectProperty
    example_predicate: owl:onProperty
    example_subject: _:B028f2531b3b2d380ecbddd6893801342
    example_subject_type: owl_Restriction
- object:
    example_object: qudt:abbreviation
    example_object_type: owl_DatatypeProperty
    example_predicate: owl:onProperty
    example_subject: _:B2884e26759d573de491a452ee02cd5be
    example_subject_type: owl_Restriction
- object:
    example_object: dct:description
    example_object_type: owl_AnnotationProperty
    example_predicate: owl:onProperty
    example_subject: _:B3132a05d8995a22458a38f94cdb45e45
    example_subject_type: owl_Restriction
from_schema: sawgraph-kg
rank: 1000
slot_uri: owl:onProperty
alias: owl_onProperty
domain_of:
- owl_Restriction
union_of:
- '{''domain'': ''owl_Class''}'
- '{''domain'': ''owl_Restriction''}'
- '{''domain'': ''rdfs_Class''}'
range: Any
any_of:
- range: owl_Thing
- range: owl_AnnotationProperty
- range: owl_DatatypeProperty
- range: rdf_Property
- range: owl_ObjectProperty

```
</details>