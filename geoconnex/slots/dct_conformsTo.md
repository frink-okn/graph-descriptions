

# Slot: dct_conformsTo


_No slot (predicate) description specified_





URI: [dct:conformsTo](http://purl.org/dc/terms/conformsTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaDataDownload](../classes/SchemaDataDownload.md) | All or part of a [[Dataset]] in downloadable form |  no  |
| [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No class (type) description specified |  no  |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_DataDownload → string | _:b1000004 | dct:conformsTo | https://labs.waterdata.usgs.gov/docs/sensorthings/index.html |
| None → uri | http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html | dct:conformsTo | https://github.com/NRCan/GSIP |
| http___rdfs.org_ns_void#Dataset → uri | https://info.geoconnex.us/chyld-pilot/data/node/all | dct:conformsTo | https://github.com/NRCan/GSIP |
| rdfs_Resource → uri | https://info.geoconnex.us/chyld-pilot/data/node/connect | dct:conformsTo | https://github.com/NRCan/GSIP |


## Comments

* 56432 occurrences with subject type schema_DataDownload and object type string.
* 3194 occurrences with untyped subjects and object type uri.
* 2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.
* 4 occurrences with subject type rdfs_Resource and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | dct:conformsTo |
| native | geoconnex/:dct_conformsTo |




## LinkML Source

<details>
```yaml
name: dct_conformsTo
description: No slot (predicate) description specified
comments:
- 56432 occurrences with subject type schema_DataDownload and object type string.
- 3194 occurrences with untyped subjects and object type uri.
- 2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
  uri.
- 4 occurrences with subject type rdfs_Resource and object type uri.
examples:
- description: schema_DataDownload → string
  object:
    example_object: https://labs.waterdata.usgs.gov/docs/sensorthings/index.html
    example_predicate: dct:conformsTo
    example_subject: _:b1000004
- description: None → uri
  object:
    example_object: https://github.com/NRCan/GSIP
    example_predicate: dct:conformsTo
    example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
- description: http___rdfs.org_ns_void#Dataset → uri
  object:
    example_object: https://github.com/NRCan/GSIP
    example_predicate: dct:conformsTo
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
- description: rdfs_Resource → uri
  object:
    example_object: https://github.com/NRCan/GSIP
    example_predicate: dct:conformsTo
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
from_schema: geoconnex
rank: 1000
slot_uri: dct:conformsTo
alias: dct_conformsTo
domain_of:
- http___rdfs.org_ns_void#Dataset
- rdfs_Resource
- schema_DataDownload
range: Any
any_of:
- range: uri
- range: string

```
</details>