

# Slot: rdfs_label


_No slot (predicate) description specified_






This slot occurs 1057 times.


URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsWildlife.proto-okn.netKgSchemaLocation](../classes/HttpsWildlife.proto-okn.netKgSchemaLocation.md) | No class (type) description specified |  yes  |
| [HttpsWildlife.proto-okn.netKgSchemaBirdName](../classes/HttpsWildlife.proto-okn.netKgSchemaBirdName.md) | No class (type) description specified |  yes  |
| [HttpsWildlife.proto-okn.netKgSchemaAmphibianName](../classes/HttpsWildlife.proto-okn.netKgSchemaAmphibianName.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| https___wildlife.proto-okn.net_kg_schema_Location | string | https://wildlife.proto-okn.net/kg/node/2216 | Saint Petersburg | 657 |
| https___wildlife.proto-okn.net_kg_schema_Bird_name | string | https://wildlife.proto-okn.net/kg/node/2217 | Ardea alba Linnaeus, 1758 | 303 |
| https___wildlife.proto-okn.net_kg_schema_Amphibian_name | string | https://wildlife.proto-okn.net/kg/node/2861 | Lithobates sphenocephalus | 97 |




## LinkML Source

<details>

```yaml
name: rdfs_label
annotations:
  count:
    tag: count
    value: 1057
description: No slot (predicate) description specified
examples:
- object:
    example_object: Saint Petersburg
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://wildlife.proto-okn.net/kg/node/2216
    example_subject_type: https___wildlife.proto-okn.net_kg_schema_Location
- object:
    example_object: Ardea alba Linnaeus, 1758
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://wildlife.proto-okn.net/kg/node/2217
    example_subject_type: https___wildlife.proto-okn.net_kg_schema_Bird_name
- object:
    example_object: Lithobates sphenocephalus
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://wildlife.proto-okn.net/kg/node/2861
    example_subject_type: https___wildlife.proto-okn.net_kg_schema_Amphibian_name
from_schema: wildlife-kg
rank: 1000
slot_uri: rdfs:label
alias: rdfs_label
domain_of:
- https___wildlife.proto-okn.net_kg_schema_Amphibian_name
- https___wildlife.proto-okn.net_kg_schema_Bird_name
- https___wildlife.proto-okn.net_kg_schema_Location
range: string

```
</details>