

# Slot: No slot (predicate) name specified (rdfs_range)


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [rdfs:range](http://www.w3.org/2000/01/rdf-schema#range)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [RdfObjectProperty](../classes/RdfObjectProperty.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlClass](../classes/OwlClass.md)&nbsp;or&nbsp;<br />[RdfsClass](../classes/RdfsClass.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| rdf_ObjectProperty | owl_Class | owl:topObjectProperty | owl:Thing | 1 |
| rdf_ObjectProperty | owl_Thing | owl:topObjectProperty | owl:Thing | 1 |
| rdf_ObjectProperty | rdfs_Class | owl:topObjectProperty | owl:Thing | 1 |
| owl_Thing | owl_Class | owl:topObjectProperty | owl:Thing | 1 |
| owl_Thing | owl_Thing | owl:topObjectProperty | owl:Thing | 1 |
| owl_Thing | rdfs_Class | owl:topObjectProperty | owl:Thing | 1 |




## LinkML Source

<details>

```yaml
name: rdfs_range
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: owl:Thing
    example_object_type: owl_Class
    example_predicate: rdfs:range
    example_subject: owl:topObjectProperty
    example_subject_type: rdf_ObjectProperty
- object:
    example_object: owl:Thing
    example_object_type: owl_Thing
    example_predicate: rdfs:range
    example_subject: owl:topObjectProperty
    example_subject_type: rdf_ObjectProperty
- object:
    example_object: owl:Thing
    example_object_type: rdfs_Class
    example_predicate: rdfs:range
    example_subject: owl:topObjectProperty
    example_subject_type: rdf_ObjectProperty
- object:
    example_object: owl:Thing
    example_object_type: owl_Class
    example_predicate: rdfs:range
    example_subject: owl:topObjectProperty
    example_subject_type: owl_Thing
- object:
    example_object: owl:Thing
    example_object_type: owl_Thing
    example_predicate: rdfs:range
    example_subject: owl:topObjectProperty
    example_subject_type: owl_Thing
- object:
    example_object: owl:Thing
    example_object_type: rdfs_Class
    example_predicate: rdfs:range
    example_subject: owl:topObjectProperty
    example_subject_type: owl_Thing
from_schema: spatial-kg
rank: 1000
slot_uri: rdfs:range
alias: rdfs_range
domain_of:
- owl_Thing
- rdf_ObjectProperty
range: Any
any_of:
- range: owl_Thing
- range: owl_Class
- range: rdfs_Class
- range: uri

```
</details>