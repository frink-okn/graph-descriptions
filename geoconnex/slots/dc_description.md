

# Slot: dc_description


_No slot (predicate) description specified_





URI: [dc:description](http://purl.org/dc/elements/1.1/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No class (type) description specified |  no  |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| http___rdfs.org_ns_void#Dataset → string | https://info.geoconnex.us/chyld-pilot/data/node/all | dc:description | Representation of the data node: catalog of features i.e. /id/s. Contains triples like: CAN_Watershed gsip:inNodeCatalog /id/CAN_LOD_Node |
| rdfs_Resource → string | https://info.geoconnex.us/chyld-pilot/data/node/connect | dc:description | Representation containing links between data nodes. Only contains triples like: /id/CAN_LOD_Node connectedTo /id/US_LOD_Node |


## Comments

* 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.
* 2 occurrences with subject type rdfs_Resource and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | dc:description |
| native | geoconnex/:dc_description |




## LinkML Source

<details>
```yaml
name: dc_description
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
  string.
- 2 occurrences with subject type rdfs_Resource and object type string.
examples:
- description: http___rdfs.org_ns_void#Dataset → string
  object:
    example_object: 'Representation of the data node: catalog of features i.e. /id/s.
      Contains triples like: CAN_Watershed gsip:inNodeCatalog /id/CAN_LOD_Node'
    example_predicate: dc:description
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
- description: rdfs_Resource → string
  object:
    example_object: 'Representation containing links between data nodes. Only contains
      triples like: /id/CAN_LOD_Node connectedTo /id/US_LOD_Node'
    example_predicate: dc:description
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
from_schema: geoconnex
rank: 1000
slot_uri: dc:description
alias: dc_description
domain_of:
- http___rdfs.org_ns_void#Dataset
- rdfs_Resource
range: string

```
</details>