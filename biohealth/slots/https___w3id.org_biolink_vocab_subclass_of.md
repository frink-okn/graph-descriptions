

# Slot: https___w3id.org_biolink_vocab_subclass_of


_No slot (predicate) description specified_






This slot occurs 301438 times.


URI: [https://w3id.org/biolink/vocab/subclass_of](https://w3id.org/biolink/vocab/subclass_of)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsW3id.orgBiolinkVocabEntity](../classes/HttpsW3id.orgBiolinkVocabEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpsW3id.orgBiolinkVocabEntity](../classes/HttpsW3id.orgBiolinkVocabEntity.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| https___w3id.org_biolink_vocab_Entity | https___w3id.org_biolink_vocab_Entity | http://linkedlifedata.com/resource/umls/id/C0000039 | http://linkedlifedata.com/resource/umls/id/C0008405 | 301438 |




## LinkML Source

<details>

```yaml
name: https___w3id.org_biolink_vocab_subclass_of
annotations:
  count:
    tag: count
    value: 301438
description: No slot (predicate) description specified
examples:
- object:
    example_object: http://linkedlifedata.com/resource/umls/id/C0008405
    example_object_type: https___w3id.org_biolink_vocab_Entity
    example_predicate: https://w3id.org/biolink/vocab/subclass_of
    example_subject: http://linkedlifedata.com/resource/umls/id/C0000039
    example_subject_type: https___w3id.org_biolink_vocab_Entity
from_schema: biohealth
rank: 1000
slot_uri: https://w3id.org/biolink/vocab/subclass_of
alias: https___w3id.org_biolink_vocab_subclass_of
domain_of:
- https___w3id.org_biolink_vocab_Entity
range: https___w3id.org_biolink_vocab_Entity

```
</details>