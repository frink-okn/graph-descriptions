

# Slot: rdfs_subClassOf


_No slot (predicate) description specified_






This slot occurs 3 times.


URI: [rdfs:subClassOf](http://www.w3.org/2000/01/rdf-schema#subClassOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtAspectClass](../classes/QudtAspectClass.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlRestriction](../classes/OwlRestriction.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | owl_Restriction | qudt:EnumeratedQuantity | _:B73911bb5851b4fbc2403970a309b1a1b | 2 |
| None | uri | qudt:EnumeratedQuantity | qudt:Concept | 1 |




## LinkML Source

<details>

```yaml
name: rdfs_subClassOf
annotations:
  count:
    tag: count
    value: 3
  owl_Restriction:
    tag: owl_Restriction
    value: 2
  uri:
    tag: uri
    value: 1
description: No slot (predicate) description specified
examples:
- object:
    example_object: _:B73911bb5851b4fbc2403970a309b1a1b
    example_object_type: owl_Restriction
    example_predicate: rdfs:subClassOf
    example_subject: qudt:EnumeratedQuantity
    example_subject_type: None
- object:
    example_object: qudt:Concept
    example_object_type: uri
    example_predicate: rdfs:subClassOf
    example_subject: qudt:EnumeratedQuantity
    example_subject_type: None
from_schema: sawgraph-kg
rank: 1000
slot_uri: rdfs:subClassOf
alias: rdfs_subClassOf
domain_of:
- qudt_AspectClass
range: Any
any_of:
- range: owl_Restriction
- range: uri

```
</details>