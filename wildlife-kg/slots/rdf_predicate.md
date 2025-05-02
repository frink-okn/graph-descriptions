

# Slot: rdf_predicate


_No slot (predicate) description specified_






This slot occurs 5205 times.


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
| rdf_Statement | uri | https://wildlife.proto-okn.net/kg/relationship/14856 | https://wildlife.proto-okn.net/kg/schema/OBSERVED_AT | 5205 |




## LinkML Source

<details>

```yaml
name: rdf_predicate
annotations:
  count:
    tag: count
    value: 5205
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://wildlife.proto-okn.net/kg/schema/OBSERVED_AT
    example_object_type: uri
    example_predicate: rdf:predicate
    example_subject: https://wildlife.proto-okn.net/kg/relationship/14856
    example_subject_type: rdf_Statement
from_schema: wildlife-kg
rank: 1000
slot_uri: rdf:predicate
alias: rdf_predicate
domain_of:
- rdf_Statement
range: uri

```
</details>