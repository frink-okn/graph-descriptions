

# Slot: rdf_object


_No slot (predicate) description specified_






This slot occurs 5205 times.


URI: [rdf:object](http://www.w3.org/1999/02/22-rdf-syntax-ns#object)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfStatement](../classes/RdfStatement.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpsWildlife.proto-okn.netKgSchemaLocation](../classes/HttpsWildlife.proto-okn.netKgSchemaLocation.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| rdf_Statement | https___wildlife.proto-okn.net_kg_schema_Location | https://wildlife.proto-okn.net/kg/relationship/14856 | https://wildlife.proto-okn.net/kg/node/2426 | 5205 |




## LinkML Source

<details>

```yaml
name: rdf_object
annotations:
  count:
    tag: count
    value: 5205
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://wildlife.proto-okn.net/kg/node/2426
    example_object_type: https___wildlife.proto-okn.net_kg_schema_Location
    example_predicate: rdf:object
    example_subject: https://wildlife.proto-okn.net/kg/relationship/14856
    example_subject_type: rdf_Statement
from_schema: wildlife-kg
rank: 1000
slot_uri: rdf:object
alias: rdf_object
domain_of:
- rdf_Statement
range: https___wildlife.proto-okn.net_kg_schema_Location

```
</details>