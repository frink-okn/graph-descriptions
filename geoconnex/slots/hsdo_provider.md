

# Slot: hsdo_provider


_No slot (predicate) description specified_





URI: [hsdo:provider](http://schema.org/provider)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |
| [HsdoWebPage](../classes/HsdoWebPage.md) | A web page |  no  |
| [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None → uri | http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html | hsdo:provider | https://labs.waterdata.usgs.gov |
| http___rdfs.org_ns_void#Dataset → uri | https://info.geoconnex.us/chyld-pilot/data/node/all | hsdo:provider | https://labs.waterdata.usgs.gov |
| rdfs_Resource → uri | https://info.geoconnex.us/chyld-pilot/data/node/connect | hsdo:provider | https://labs.waterdata.usgs.gov |
| hsdo_WebPage → string | https://geoconnex.us/epa/hmw/010100020101 | hsdo:provider | https://epa.gov |


## Comments

* 3194 occurrences with untyped subjects and object type uri.
* 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.
* 2 occurrences with subject type rdfs_Resource and object type uri.
* 48672 occurrences with subject type hsdo_WebPage and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:provider |
| native | geoconnex/:hsdo_provider |




## LinkML Source

<details>
```yaml
name: hsdo_provider
description: No slot (predicate) description specified
comments:
- 3194 occurrences with untyped subjects and object type uri.
- 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
  uri.
- 2 occurrences with subject type rdfs_Resource and object type uri.
- 48672 occurrences with subject type hsdo_WebPage and object type string.
examples:
- description: None → uri
  object:
    example_object: https://labs.waterdata.usgs.gov
    example_predicate: hsdo:provider
    example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
- description: http___rdfs.org_ns_void#Dataset → uri
  object:
    example_object: https://labs.waterdata.usgs.gov
    example_predicate: hsdo:provider
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
- description: rdfs_Resource → uri
  object:
    example_object: https://labs.waterdata.usgs.gov
    example_predicate: hsdo:provider
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
- description: hsdo_WebPage → string
  object:
    example_object: https://epa.gov
    example_predicate: hsdo:provider
    example_subject: https://geoconnex.us/epa/hmw/010100020101
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:provider
alias: hsdo_provider
domain_of:
- hsdo_WebPage
- http___rdfs.org_ns_void#Dataset
- rdfs_Resource
range: Any
any_of:
- range: uri
- range: string

```
</details>