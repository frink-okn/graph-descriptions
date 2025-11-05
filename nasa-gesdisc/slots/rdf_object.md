

# Slot: rdf_object


_No slot (predicate) description specified_






This slot occurs 406515 times.


URI: [rdf:object](http://www.w3.org/1999/02/22-rdf-syntax-ns#object)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfStatement](../classes/RdfStatement.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaInstrument.md)&nbsp;or&nbsp;<br />[HttpsNasa-gesdisc.proto-okn.netKgSchemaProject](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaProject.md)&nbsp;or&nbsp;<br />[HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform.md)&nbsp;or&nbsp;<br />[HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword.md)&nbsp;or&nbsp;<br />[HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md)&nbsp;or&nbsp;<br />[HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| rdf_Statement | https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset | https://nasa-gesdisc.proto-okn.net/kg/relationship/0 | https://nasa-gesdisc.proto-okn.net/kg/node/0 | 35695 |
| rdf_Statement | https___nasa-gesdisc.proto-okn.net_kg_schema_Project | https://nasa-gesdisc.proto-okn.net/kg/relationship/10000 | https://nasa-gesdisc.proto-okn.net/kg/node/7024 | 6378 |
| rdf_Statement | https___nasa-gesdisc.proto-okn.net_kg_schema_Publication | https://nasa-gesdisc.proto-okn.net/kg/relationship/100000 | https://nasa-gesdisc.proto-okn.net/kg/node/17877 | 208429 |
| rdf_Statement | https___nasa-gesdisc.proto-okn.net_kg_schema_Platform | https://nasa-gesdisc.proto-okn.net/kg/relationship/16212 | https://nasa-gesdisc.proto-okn.net/kg/node/7369 | 10398 |
| rdf_Statement | https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument | https://nasa-gesdisc.proto-okn.net/kg/relationship/26610 | https://nasa-gesdisc.proto-okn.net/kg/node/7820 | 2526 |
| rdf_Statement | https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword | https://nasa-gesdisc.proto-okn.net/kg/relationship/286820 | https://nasa-gesdisc.proto-okn.net/kg/node/34554 | 143089 |




## LinkML Source

<details>

```yaml
name: rdf_object
annotations:
  count:
    tag: count
    value: 406515
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/node/0
    example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    example_predicate: rdf:object
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/0
    example_subject_type: rdf_Statement
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/node/7024
    example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    example_predicate: rdf:object
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/10000
    example_subject_type: rdf_Statement
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/node/17877
    example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    example_predicate: rdf:object
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/100000
    example_subject_type: rdf_Statement
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/node/7369
    example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    example_predicate: rdf:object
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/16212
    example_subject_type: rdf_Statement
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/node/7820
    example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    example_predicate: rdf:object
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/26610
    example_subject_type: rdf_Statement
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/node/34554
    example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
    example_predicate: rdf:object
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/286820
    example_subject_type: rdf_Statement
from_schema: nasa-gesdisc
rank: 1000
slot_uri: rdf:object
alias: rdf_object
domain_of:
- rdf_Statement
range: Any
any_of:
- range: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
- range: https___nasa-gesdisc.proto-okn.net_kg_schema_Project
- range: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
- range: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
- range: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
- range: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication

```
</details>