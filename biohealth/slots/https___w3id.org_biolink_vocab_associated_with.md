

# Slot: https___w3id.org_biolink_vocab_associated_with


_No slot (predicate) description specified_






This slot occurs 668853 times.


URI: [https://w3id.org/biolink/vocab/associated_with](https://w3id.org/biolink/vocab/associated_with)



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
| https___w3id.org_biolink_vocab_Entity | https___w3id.org_biolink_vocab_Entity | http://linkedlifedata.com/resource/umls/id/C0000039 | http://linkedlifedata.com/resource/umls/id/C0015230 | 668853 |




## LinkML Source

<details>

```yaml
name: https___w3id.org_biolink_vocab_associated_with
annotations:
  count:
    tag: count
    value: 668853
description: No slot (predicate) description specified
examples:
- object:
    example_object: http://linkedlifedata.com/resource/umls/id/C0015230
    example_object_type: https___w3id.org_biolink_vocab_Entity
    example_predicate: https://w3id.org/biolink/vocab/associated_with
    example_subject: http://linkedlifedata.com/resource/umls/id/C0000039
    example_subject_type: https___w3id.org_biolink_vocab_Entity
from_schema: biohealth
rank: 1000
slot_uri: https://w3id.org/biolink/vocab/associated_with
alias: https___w3id.org_biolink_vocab_associated_with
domain_of:
- https___w3id.org_biolink_vocab_Entity
range: https___w3id.org_biolink_vocab_Entity

```
</details>