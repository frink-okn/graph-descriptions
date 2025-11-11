

# Slot: https___wildlife.proto_okn.net_kg_schema_OBSERVED_AT


_No slot (predicate) description specified_






This slot occurs 5205 times.


URI: [https://wildlife.proto-okn.net/kg/schema/OBSERVED_AT](https://wildlife.proto-okn.net/kg/schema/OBSERVED_AT)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsWildlife.proto-okn.netKgSchemaBirdName](../classes/HttpsWildlife.proto-okn.netKgSchemaBirdName.md) | No class (type) description specified |  yes  |
| [HttpsWildlife.proto-okn.netKgSchemaAmphibianName](../classes/HttpsWildlife.proto-okn.netKgSchemaAmphibianName.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpsWildlife.proto-okn.netKgSchemaLocation](../classes/HttpsWildlife.proto-okn.netKgSchemaLocation.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| https___wildlife.proto-okn.net_kg_schema_Bird_name | https___wildlife.proto-okn.net_kg_schema_Location | https://wildlife.proto-okn.net/kg/node/2217 | https://wildlife.proto-okn.net/kg/node/2216 | 2482 |
| https___wildlife.proto-okn.net_kg_schema_Amphibian_name | https___wildlife.proto-okn.net_kg_schema_Location | https://wildlife.proto-okn.net/kg/node/2861 | https://wildlife.proto-okn.net/kg/node/2216 | 2723 |




## LinkML Source

<details>

```yaml
name: https___wildlife.proto-okn.net_kg_schema_OBSERVED_AT
annotations:
  count:
    tag: count
    value: 5205
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://wildlife.proto-okn.net/kg/node/2216
    example_object_type: https___wildlife.proto-okn.net_kg_schema_Location
    example_predicate: https://wildlife.proto-okn.net/kg/schema/OBSERVED_AT
    example_subject: https://wildlife.proto-okn.net/kg/node/2217
    example_subject_type: https___wildlife.proto-okn.net_kg_schema_Bird_name
- object:
    example_object: https://wildlife.proto-okn.net/kg/node/2216
    example_object_type: https___wildlife.proto-okn.net_kg_schema_Location
    example_predicate: https://wildlife.proto-okn.net/kg/schema/OBSERVED_AT
    example_subject: https://wildlife.proto-okn.net/kg/node/2861
    example_subject_type: https___wildlife.proto-okn.net_kg_schema_Amphibian_name
from_schema: wildlife-kg
rank: 1000
slot_uri: https://wildlife.proto-okn.net/kg/schema/OBSERVED_AT
alias: https___wildlife.proto_okn.net_kg_schema_OBSERVED_AT
domain_of:
- https___wildlife.proto-okn.net_kg_schema_Amphibian_name
- https___wildlife.proto-okn.net_kg_schema_Bird_name
range: https___wildlife.proto-okn.net_kg_schema_Location

```
</details>