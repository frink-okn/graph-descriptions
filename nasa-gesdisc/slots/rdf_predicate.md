

# Slot: rdf_predicate


_No slot (predicate) description specified_






This slot occurs 406515 times.


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
| rdf_Statement | uri | https://nasa-gesdisc.proto-okn.net/kg/relationship/0 | https://nasa-gesdisc.proto-okn.net/kg/schema/HAS_DATASET | 406515 |




## LinkML Source

<details>

```yaml
name: rdf_predicate
annotations:
  count:
    tag: count
    value: 406515
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/schema/HAS_DATASET
    example_object_type: uri
    example_predicate: rdf:predicate
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/0
    example_subject_type: rdf_Statement
from_schema: nasa-gesdisc
rank: 1000
slot_uri: rdf:predicate
alias: rdf_predicate
domain_of:
- rdf_Statement
range: uri

```
</details>