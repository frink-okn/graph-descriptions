

# Slot: owl_onProperty


_No slot (predicate) description specified_






This slot occurs 62 times.


URI: [owl:onProperty](http://www.w3.org/2002/07/owl#onProperty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlRestriction](../classes/OwlRestriction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlAnnotationProperty](../classes/OwlAnnotationProperty.md)&nbsp;or&nbsp;<br />[OwlObjectProperty](../classes/OwlObjectProperty.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[OwlDatatypeProperty](../classes/OwlDatatypeProperty.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Restriction | owl_DatatypeProperty | _:B1483a74553e695096917e036e115647b | qudt:abbreviation | 2 |
| owl_Restriction | uri | _:B1b94d9e751ffada9b24c828d0fa88371 | qudt:basis | 51 |
| owl_Restriction | owl_ObjectProperty | _:B6913f0a64a969f89379ad1e1a3c4555b | coso:observedProperty | 8 |
| owl_Restriction | owl_AnnotationProperty | _:Bd98fe8bdc6e04c95195453fbd99b19cd | dct:description | 1 |




## LinkML Source

<details>

```yaml
name: owl_onProperty
annotations:
  count:
    tag: count
    value: 62
description: No slot (predicate) description specified
examples:
- object:
    example_object: qudt:abbreviation
    example_object_type: owl_DatatypeProperty
    example_predicate: owl:onProperty
    example_subject: _:B1483a74553e695096917e036e115647b
    example_subject_type: owl_Restriction
- object:
    example_object: qudt:basis
    example_object_type: uri
    example_predicate: owl:onProperty
    example_subject: _:B1b94d9e751ffada9b24c828d0fa88371
    example_subject_type: owl_Restriction
- object:
    example_object: coso:observedProperty
    example_object_type: owl_ObjectProperty
    example_predicate: owl:onProperty
    example_subject: _:B6913f0a64a969f89379ad1e1a3c4555b
    example_subject_type: owl_Restriction
- object:
    example_object: dct:description
    example_object_type: owl_AnnotationProperty
    example_predicate: owl:onProperty
    example_subject: _:Bd98fe8bdc6e04c95195453fbd99b19cd
    example_subject_type: owl_Restriction
from_schema: sawgraph-kg
rank: 1000
slot_uri: owl:onProperty
alias: owl_onProperty
domain_of:
- owl_Restriction
range: Any
any_of:
- range: owl_AnnotationProperty
- range: owl_ObjectProperty
- range: uri
- range: owl_DatatypeProperty

```
</details>