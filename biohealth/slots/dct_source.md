

# Slot: dct_source


_No slot (predicate) description specified_






This slot occurs 18352179 times.


URI: [dct:source](http://purl.org/dc/terms/source)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfStatement](../classes/RdfStatement.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| rdf_Statement | string | https://biohealthkg.proto-okn.net/kg/relationship/0 | MIMIC;PubMed | 18352179 |




## LinkML Source

<details>

```yaml
name: dct_source
annotations:
  count:
    tag: count
    value: 18352179
description: No slot (predicate) description specified
examples:
- object:
    example_object: MIMIC;PubMed
    example_object_type: string
    example_predicate: dct:source
    example_subject: https://biohealthkg.proto-okn.net/kg/relationship/0
    example_subject_type: rdf_Statement
from_schema: biohealth
rank: 1000
slot_uri: dct:source
alias: dct_source
domain_of:
- rdf_Statement
range: string

```
</details>