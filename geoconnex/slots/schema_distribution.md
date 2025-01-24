

# Slot: schema_distribution


_No slot (predicate) description specified_





URI: [schema:distribution](https://schema.org/distribution)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaDataset](../classes/SchemaDataset.md) | A body of structured information describing some topic(s) of interest |  no  |







## Properties

* Range: [SchemaDataDownload](../classes/SchemaDataDownload.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Dataset → schema_DataDownload | https://gleaner.io/xid/genid/cri6355vd7os738ck6jg | schema:distribution | https://gleaner.io/xid/genid/cri6355vd7os738ck6gg |


## Comments

* 56432 occurrences with subject type schema_Dataset and object type schema_DataDownload.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:distribution |
| native | geoconnex/:schema_distribution |




## LinkML Source

<details>
```yaml
name: schema_distribution
description: No slot (predicate) description specified
comments:
- 56432 occurrences with subject type schema_Dataset and object type schema_DataDownload.
examples:
- description: schema_Dataset → schema_DataDownload
  object:
    example_object: https://gleaner.io/xid/genid/cri6355vd7os738ck6gg
    example_predicate: schema:distribution
    example_subject: https://gleaner.io/xid/genid/cri6355vd7os738ck6jg
from_schema: geoconnex
rank: 1000
slot_uri: schema:distribution
alias: schema_distribution
domain_of:
- schema_Dataset
range: schema_DataDownload

```
</details>