

# Slot: dct_format


_No slot (predicate) description specified_





URI: [dct:format](http://purl.org/dc/terms/format)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |
| [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None → string | http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html | dct:format | text/html |
| http___rdfs.org_ns_void#Dataset → string | https://info.geoconnex.us/chyld-pilot/data/node/all | dct:format | application/ld+json |
| rdfs_Resource → string | https://info.geoconnex.us/chyld-pilot/data/node/connect | dct:format | application/ld+json |


## Comments

* 7697 occurrences with untyped subjects and object type string.
* 3 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.
* 6 occurrences with subject type rdfs_Resource and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | dct:format |
| native | geoconnex/:dct_format |




## LinkML Source

<details>
```yaml
name: dct_format
description: No slot (predicate) description specified
comments:
- 7697 occurrences with untyped subjects and object type string.
- 3 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
  string.
- 6 occurrences with subject type rdfs_Resource and object type string.
examples:
- description: None → string
  object:
    example_object: text/html
    example_predicate: dct:format
    example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
- description: http___rdfs.org_ns_void#Dataset → string
  object:
    example_object: application/ld+json
    example_predicate: dct:format
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
- description: rdfs_Resource → string
  object:
    example_object: application/ld+json
    example_predicate: dct:format
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
from_schema: geoconnex
rank: 1000
slot_uri: dct:format
alias: dct_format
domain_of:
- http___rdfs.org_ns_void#Dataset
- rdfs_Resource
range: string

```
</details>