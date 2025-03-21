

# Slot: https___w3id.org_biolink_vocab_category


_No slot (predicate) description specified_






This slot occurs 250976 times.


URI: [https://w3id.org/biolink/vocab/category](https://w3id.org/biolink/vocab/category)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsW3id.orgBiolinkVocabEntity](../classes/HttpsW3id.orgBiolinkVocabEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| https___w3id.org_biolink_vocab_Entity | uri | http://linkedlifedata.com/resource/umls/id/C0000039 | https://biohealthkg.proto-okn.net/kg/semtype/lipd | 250976 |




## LinkML Source

<details>

```yaml
name: https___w3id.org_biolink_vocab_category
annotations:
  count:
    tag: count
    value: 250976
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://biohealthkg.proto-okn.net/kg/semtype/lipd
    example_object_type: uri
    example_predicate: https://w3id.org/biolink/vocab/category
    example_subject: http://linkedlifedata.com/resource/umls/id/C0000039
    example_subject_type: https___w3id.org_biolink_vocab_Entity
from_schema: biohealth
rank: 1000
slot_uri: https://w3id.org/biolink/vocab/category
alias: https___w3id.org_biolink_vocab_category
domain_of:
- https___w3id.org_biolink_vocab_Entity
range: uri

```
</details>