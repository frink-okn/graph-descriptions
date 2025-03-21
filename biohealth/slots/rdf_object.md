

# Slot: rdf_object


_No slot (predicate) description specified_






This slot occurs 18352179 times.


URI: [rdf:object](http://www.w3.org/1999/02/22-rdf-syntax-ns#object)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfStatement](../classes/RdfStatement.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpsW3id.orgBiolinkVocabEntity](../classes/HttpsW3id.orgBiolinkVocabEntity.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| rdf_Statement | https___w3id.org_biolink_vocab_Entity | https://biohealthkg.proto-okn.net/kg/relationship/0 | http://linkedlifedata.com/resource/umls/id/C0250480 | 18352179 |




## LinkML Source

<details>

```yaml
name: rdf_object
annotations:
  count:
    tag: count
    value: 18352179
description: No slot (predicate) description specified
examples:
- object:
    example_object: http://linkedlifedata.com/resource/umls/id/C0250480
    example_object_type: https___w3id.org_biolink_vocab_Entity
    example_predicate: rdf:object
    example_subject: https://biohealthkg.proto-okn.net/kg/relationship/0
    example_subject_type: rdf_Statement
from_schema: biohealth
rank: 1000
slot_uri: rdf:object
alias: rdf_object
domain_of:
- rdf_Statement
range: https___w3id.org_biolink_vocab_Entity

```
</details>