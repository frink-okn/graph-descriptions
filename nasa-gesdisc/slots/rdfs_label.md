

# Slot: rdfs_label


_No slot (predicate) description specified_






This slot occurs 10326 times.


URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform.md) | No class (type) description specified |  yes  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument.md) | No class (type) description specified |  yes  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter.md) | No class (type) description specified |  yes  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaProject](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaProject.md) | No class (type) description specified |  yes  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md) | No class (type) description specified |  yes  |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset | string | https://nasa-gesdisc.proto-okn.net/kg/node/0 | ERS-1_BYU_L3_OW_SIGMA0_ENHANCED | 6821 |
| https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword | string | https://nasa-gesdisc.proto-okn.net/kg/node/34483 | DATA ANALYSIS AND VISUALIZATION | 1609 |
| https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter | string | https://nasa-gesdisc.proto-okn.net/kg/node/6821 | BYU/SCP | 197 |
| https___nasa-gesdisc.proto-okn.net_kg_schema_Project | string | https://nasa-gesdisc.proto-okn.net/kg/node/7018 | SCP | 351 |
| https___nasa-gesdisc.proto-okn.net_kg_schema_Platform | string | https://nasa-gesdisc.proto-okn.net/kg/node/7369 | ERS-1 | 451 |
| https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument | string | https://nasa-gesdisc.proto-okn.net/kg/node/7820 | AMI | 897 |




## LinkML Source

<details>

```yaml
name: rdfs_label
annotations:
  count:
    tag: count
    value: 10326
description: No slot (predicate) description specified
examples:
- object:
    example_object: ERS-1_BYU_L3_OW_SIGMA0_ENHANCED
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/0
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
- object:
    example_object: DATA ANALYSIS AND VISUALIZATION
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/34483
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
- object:
    example_object: BYU/SCP
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/6821
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
- object:
    example_object: SCP
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7018
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Project
- object:
    example_object: ERS-1
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7369
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
- object:
    example_object: AMI
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7820
    example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
from_schema: nasa-gesdisc
rank: 1000
slot_uri: rdfs:label
alias: rdfs_label
domain_of:
- https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
- https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
- https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
- https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
- https___nasa-gesdisc.proto-okn.net_kg_schema_Project
- https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
range: string

```
</details>