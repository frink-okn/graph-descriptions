

# Slot: schema_provider


_No slot (predicate) description specified_





URI: [schema:provider](https://schema.org/provider)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaDataset](../classes/SchemaDataset.md) | A body of structured information describing some topic(s) of interest |  no  |
| [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No class (type) description specified |  no  |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[SchemaGovernmentOrganization](../classes/SchemaGovernmentOrganization.md)&nbsp;or&nbsp;<br />[schema_url](../slots/schema_url.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Dataset → schema_GovernmentOrganization | https://gleaner.io/xid/genid/cri6355vd7os738ck6jg | schema:provider | https://gleaner.io/xid/genid/cri6355vd7os738ck6h0 |
| http___rdfs.org_ns_void#Dataset → uri | https://info.geoconnex.us/chyld-pilot/data/node/all | schema:provider | https://labs.waterdata.usgs.gov |
| rdfs_Resource → uri | https://info.geoconnex.us/chyld-pilot/data/node/connect | schema:provider | https://labs.waterdata.usgs.gov |
| schema_Place → schema_url | https://geoconnex.us/ref/dams/1000001 | schema:provider | https://nid.usace.army.mil |
| hyf__HY_HydroLocation → uri | https://geoconnex.us/ref/gages/1000001 | schema:provider | https://waterdata.usgs.gov |
| hyf__HY_HydroLocation → schema_GovernmentOrganization | https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900' | schema:provider | _:b850488 |


## Comments

* 28216 occurrences with subject type schema_Dataset and object type schema_GovernmentOrganization.
* 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.
* 2 occurrences with subject type rdfs_Resource and object type uri.
* 98534 occurrences with subject type schema_Place and object type schema_url.
* 185872 occurrences with subject type hyf__HY_HydroLocation and object type uri.
* 13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_GovernmentOrganization.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:provider |
| native | geoconnex/:schema_provider |




## LinkML Source

<details>
```yaml
name: schema_provider
description: No slot (predicate) description specified
comments:
- 28216 occurrences with subject type schema_Dataset and object type schema_GovernmentOrganization.
- 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
  uri.
- 2 occurrences with subject type rdfs_Resource and object type uri.
- 98534 occurrences with subject type schema_Place and object type schema_url.
- 185872 occurrences with subject type hyf__HY_HydroLocation and object type uri.
- 13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_GovernmentOrganization.
examples:
- description: schema_Dataset → schema_GovernmentOrganization
  object:
    example_object: https://gleaner.io/xid/genid/cri6355vd7os738ck6h0
    example_predicate: schema:provider
    example_subject: https://gleaner.io/xid/genid/cri6355vd7os738ck6jg
- description: http___rdfs.org_ns_void#Dataset → uri
  object:
    example_object: https://labs.waterdata.usgs.gov
    example_predicate: schema:provider
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
- description: rdfs_Resource → uri
  object:
    example_object: https://labs.waterdata.usgs.gov
    example_predicate: schema:provider
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
- description: schema_Place → schema_url
  object:
    example_object: https://nid.usace.army.mil
    example_predicate: schema:provider
    example_subject: https://geoconnex.us/ref/dams/1000001
- description: hyf__HY_HydroLocation → uri
  object:
    example_object: https://waterdata.usgs.gov
    example_predicate: schema:provider
    example_subject: https://geoconnex.us/ref/gages/1000001
- description: hyf__HY_HydroLocation → schema_GovernmentOrganization
  object:
    example_object: _:b850488
    example_predicate: schema:provider
    example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900'
from_schema: geoconnex
rank: 1000
slot_uri: schema:provider
alias: schema_provider
domain_of:
- http___rdfs.org_ns_void#Dataset
- hyf__HY_HydroLocation
- rdfs_Resource
- schema_Dataset
- schema_Place
range: Any
any_of:
- range: uri
- range: schema_GovernmentOrganization
- range: schema_url

```
</details>