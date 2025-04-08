

# Slot: rdf_subject


_No slot (predicate) description specified_






This slot occurs 406515 times.


URI: [rdf:subject](http://www.w3.org/1999/02/22-rdf-syntax-ns#subject)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfStatement](../classes/RdfStatement.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPlatform.md)&nbsp;or&nbsp;<br />[HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword.md)&nbsp;or&nbsp;<br />[HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md)&nbsp;or&nbsp;<br />[HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataCenter.md)&nbsp;or&nbsp;<br />[HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| rdf_Statement | https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter | https://nasa-gesdisc.proto-okn.net/kg/relationship/0 | https://nasa-gesdisc.proto-okn.net/kg/node/6821 | 9834 |
| rdf_Statement | https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset | https://nasa-gesdisc.proto-okn.net/kg/relationship/10000 | https://nasa-gesdisc.proto-okn.net/kg/node/138 | 38347 |
| rdf_Statement | https___nasa-gesdisc.proto-okn.net_kg_schema_Publication | https://nasa-gesdisc.proto-okn.net/kg/relationship/100000 | https://nasa-gesdisc.proto-okn.net/kg/node/53279 | 353985 |
| rdf_Statement | https___nasa-gesdisc.proto-okn.net_kg_schema_Platform | https://nasa-gesdisc.proto-okn.net/kg/relationship/26610 | https://nasa-gesdisc.proto-okn.net/kg/node/7369 | 2526 |
| rdf_Statement | https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword | https://nasa-gesdisc.proto-okn.net/kg/relationship/54997 | https://nasa-gesdisc.proto-okn.net/kg/node/34483 | 1823 |




## LinkML Source

<details>

```yaml
name: rdf_subject
annotations:
  count:
    tag: count
    value: 406515
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/node/6821
    example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    example_predicate: rdf:subject
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/0
    example_subject_type: rdf_Statement
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/node/138
    example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    example_predicate: rdf:subject
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/10000
    example_subject_type: rdf_Statement
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/node/53279
    example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    example_predicate: rdf:subject
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/100000
    example_subject_type: rdf_Statement
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/node/7369
    example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    example_predicate: rdf:subject
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/26610
    example_subject_type: rdf_Statement
- object:
    example_object: https://nasa-gesdisc.proto-okn.net/kg/node/34483
    example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
    example_predicate: rdf:subject
    example_subject: https://nasa-gesdisc.proto-okn.net/kg/relationship/54997
    example_subject_type: rdf_Statement
from_schema: nasa-gesdisc
rank: 1000
slot_uri: rdf:subject
alias: rdf_subject
domain_of:
- rdf_Statement
range: Any
any_of:
- range: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
- range: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
- range: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
- range: https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
- range: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication

```
</details>