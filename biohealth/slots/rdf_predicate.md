

# Slot: rdf_predicate


_No slot (predicate) description specified_






This slot occurs 18352179 times.


URI: [rdf:predicate](http://www.w3.org/1999/02/22-rdf-syntax-ns#predicate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfStatement](../classes/RdfStatement.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| rdf_Statement | uri | https://biohealthkg.proto-okn.net/kg/relationship/0 | https://w3id.org/biolink/vocab/subclass_of | 18352179 |




## LinkML Source

<details>

```yaml
name: rdf_predicate
annotations:
  count:
    tag: count
    value: 18352179
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://w3id.org/biolink/vocab/subclass_of
    example_object_type: uri
    example_predicate: rdf:predicate
    example_subject: https://biohealthkg.proto-okn.net/kg/relationship/0
    example_subject_type: rdf_Statement
from_schema: biohealth
rank: 1000
slot_uri: rdf:predicate
alias: rdf_predicate
domain_of:
- rdf_Statement
range: uri

```
</details>