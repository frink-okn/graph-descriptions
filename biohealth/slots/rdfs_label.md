

# Slot: rdfs_label


_No slot (predicate) description specified_






This slot occurs 250976 times.


URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsW3id.orgBiolinkVocabEntity](../classes/HttpsW3id.orgBiolinkVocabEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| https___w3id.org_biolink_vocab_Entity | string | http://linkedlifedata.com/resource/umls/id/C0000039 | 1,2-Dipalmitoylphosphatidylcholine | 250976 |




## LinkML Source

<details>

```yaml
name: rdfs_label
annotations:
  count:
    tag: count
    value: 250976
description: No slot (predicate) description specified
examples:
- object:
    example_object: 1,2-Dipalmitoylphosphatidylcholine
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: http://linkedlifedata.com/resource/umls/id/C0000039
    example_subject_type: https___w3id.org_biolink_vocab_Entity
from_schema: biohealth
rank: 1000
slot_uri: rdfs:label
alias: rdfs_label
domain_of:
- https___w3id.org_biolink_vocab_Entity
range: string

```
</details>