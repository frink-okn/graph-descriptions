

# Slot: schema_contentUrl


_No slot (predicate) description specified_





URI: [schema:contentUrl](https://schema.org/contentUrl)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaDataDownload](../classes/SchemaDataDownload.md) | All or part of a [[Dataset]] in downloadable form |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_DataDownload → string | _:b1000004 | schema:contentUrl | https://labs.waterdata.usgs.gov/sta/v1.1/Datastreams('b9c7e441fc154190b69f5dee407b533b')?$expand=Thing,Observations |


## Comments

* 56432 occurrences with subject type schema_DataDownload and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:contentUrl |
| native | geoconnex/:schema_contentUrl |




## LinkML Source

<details>
```yaml
name: schema_contentUrl
description: No slot (predicate) description specified
comments:
- 56432 occurrences with subject type schema_DataDownload and object type string.
examples:
- description: schema_DataDownload → string
  object:
    example_object: https://labs.waterdata.usgs.gov/sta/v1.1/Datastreams('b9c7e441fc154190b69f5dee407b533b')?$expand=Thing,Observations
    example_predicate: schema:contentUrl
    example_subject: _:b1000004
from_schema: geoconnex
rank: 1000
slot_uri: schema:contentUrl
alias: schema_contentUrl
domain_of:
- schema_DataDownload
range: string

```
</details>