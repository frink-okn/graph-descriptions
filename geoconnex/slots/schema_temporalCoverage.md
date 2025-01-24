

# Slot: schema_temporalCoverage


_No slot (predicate) description specified_





URI: [schema:temporalCoverage](https://schema.org/temporalCoverage)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaDataset](../classes/SchemaDataset.md) | A body of structured information describing some topic(s) of interest |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Dataset → string | _:b1000000 | schema:temporalCoverage | 2024-08-30T10:00:00Z/2024-09-09T18:00:00Z |


## Comments

* 28169 occurrences with subject type schema_Dataset and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:temporalCoverage |
| native | geoconnex/:schema_temporalCoverage |




## LinkML Source

<details>
```yaml
name: schema_temporalCoverage
description: No slot (predicate) description specified
comments:
- 28169 occurrences with subject type schema_Dataset and object type string.
examples:
- description: schema_Dataset → string
  object:
    example_object: 2024-08-30T10:00:00Z/2024-09-09T18:00:00Z
    example_predicate: schema:temporalCoverage
    example_subject: _:b1000000
from_schema: geoconnex
rank: 1000
slot_uri: schema:temporalCoverage
alias: schema_temporalCoverage
domain_of:
- schema_Dataset
range: string

```
</details>