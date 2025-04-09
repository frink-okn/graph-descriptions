

# Slot: dct_subject


_No slot (predicate) description specified_






This slot occurs 8521 times.


URI: [dct:subject](http://purl.org/dc/terms/subject)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform.md) | No class (type) description specified |  yes  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument.md) | No class (type) description specified |  yes  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter.md) | No class (type) description specified |  yes  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaProject](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaProject.md) | No class (type) description specified |  yes  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset | string | https://nasa-gesdisc.proto-okn.net/kg/node/0 | ERS-1 Gridded Level 3 Enhanced Resolution Sigma-0 from BYU | 6821 |
| https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter | string | https://nasa-gesdisc.proto-okn.net/kg/node/6821 | N/A | 197 |
| https___nasa-gesdisc.proto-okn.net_kg_schema_Project | string | https://nasa-gesdisc.proto-okn.net/kg/node/7018 | Scatterometry Climate Record Pathfinder | 342 |
| https___nasa-gesdisc.proto-okn.net_kg_schema_Platform | string | https://nasa-gesdisc.proto-okn.net/kg/node/7369 | European Remote Sensing Satellite-1 | 378 |
| https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument | string | https://nasa-gesdisc.proto-okn.net/kg/node/7820 | Active Microwave Instrument | 783 |




## LinkML Source

<details>

```yaml
name: dct_subject
annotations:
  count:
    tag: count
    value: 8521
description: No slot (predicate) description specified
examples:
- object:
    example_object: ERS-1 Gridded Level 3 Enhanced Resolution Sigma-0 from BYU
    example_object_type: string
    example_predicate: dct:subject
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/0
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
- object:
    example_object: N/A
    example_object_type: string
    example_predicate: dct:subject
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/6821
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
- object:
    example_object: Scatterometry Climate Record Pathfinder
    example_object_type: string
    example_predicate: dct:subject
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7018
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Project
- object:
    example_object: European Remote Sensing Satellite-1
    example_object_type: string
    example_predicate: dct:subject
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7369
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
- object:
    example_object: Active Microwave Instrument
    example_object_type: string
    example_predicate: dct:subject
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7820
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
from_schema: nasa-gesdisc
rank: 1000
slot_uri: dct:subject
alias: dct_subject
domain_of:
- https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
- https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
- https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
- https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
- https___nasa-gesdisc.proto-okn.net_kg_schema_Project
range: string

```
</details>