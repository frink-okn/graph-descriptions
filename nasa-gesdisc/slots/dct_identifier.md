

# Slot: dct_identifier


_No slot (predicate) description specified_






This slot occurs 142173 times.


URI: [dct:identifier](http://purl.org/dc/terms/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md) | No class (type) description specified |  yes  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset | string | https://nasa-gesdisc.proto-okn.net/kg/node/0 | 10.5067/ERS1B-SNEN0 | 6821 |
| https___nasa-gesdisc.proto-okn.net_kg_schema_Publication | string | https://nasa-gesdisc.proto-okn.net/kg/node/10000 | 10.1111/COBI.13282 | 135352 |




## LinkML Source

<details>

```yaml
name: dct_identifier
annotations:
  count:
    tag: count
    value: 142173
description: No slot (predicate) description specified
examples:
- object:
    example_object: 10.5067/ERS1B-SNEN0
    example_object_type: string
    example_predicate: dct:identifier
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/0
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
- object:
    example_object: 10.1111/COBI.13282
    example_object_type: string
    example_predicate: dct:identifier
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/10000
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
from_schema: nasa-gesdisc
rank: 1000
slot_uri: dct:identifier
alias: dct_identifier
domain_of:
- https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
- https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
range: string

```
</details>