

# Slot: schema_name


_No slot (predicate) description specified_





URI: [schema:name](https://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation](../classes/HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation.md) | No class (type) description specified |  no  |
| [SchemaOrganization](../classes/SchemaOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [SchemaDataDownload](../classes/SchemaDataDownload.md) | All or part of a [[Dataset]] in downloadable form |  no  |
| [SchemaPropertyValue](../classes/SchemaPropertyValue.md) | A property-value pair, e |  no  |
| [SchemaDataset](../classes/SchemaDataset.md) | A body of structured information describing some topic(s) of interest |  no  |
| [SchemaGovernmentOrganization](../classes/SchemaGovernmentOrganization.md) | A governmental organization or agency |  no  |
| [SchemaCreativeWork](../classes/SchemaCreativeWork.md) | The most generic kind of creative work, including books, movies, photographs,... |  no  |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Dataset → string | _:b1000000 | schema:name | USGS-293229091230800 |
| schema_DataDownload → string | _:b1000004 | schema:name | USGS SensorThings API |
| schema_GovernmentOrganization → string | _:b1000006 | schema:name | U.S. Geological Survey Water Data for the Nation |
| schema_PropertyValue → string | _:b1000007 | schema:name | Gage height |
| None → string | _:b1548067 | schema:name | Mancos River at Anitas Flat Below Mancos CO |
| schema_Place → string | https://geoconnex.us/ref/hu02/01 | schema:name | New England Region |
| hyf__HY_HydroLocation → string | https://geoconnex.us/iow/demo/AL00017 | schema:name | BIG CREEK |
| http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation → string | https://geoconnex.us/ornl/hydrosource/dams/1 | schema:name | ALCOVA |
| schema_Organization → string | https://gleaner.io/id/org/CUAHSI_CUAHSI_HIS_CRWA_ids__0 | schema:name | CUAHSI_CUAHSI_HIS_CRWA_ids__0 |
| schema_CreativeWork → string | https://gleaner.io/xid/genid/cksjodsip8t6t2qulttg | schema:name | HUC12 Pour Points |


## Comments

* 28216 occurrences with subject type schema_Dataset and object type string.
* 56432 occurrences with subject type schema_DataDownload and object type string.
* 41703 occurrences with subject type schema_GovernmentOrganization and object type string.
* 28216 occurrences with subject type schema_PropertyValue and object type string.
* 45727 occurrences with untyped subjects and object type string.
* 243268 occurrences with subject type schema_Place and object type string.
* 201357 occurrences with subject type hyf__HY_HydroLocation and object type string.
* 2741 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type string.
* 247 occurrences with subject type schema_Organization and object type string.
* 165029 occurrences with subject type schema_CreativeWork and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:name |
| native | geoconnex/:schema_name |




## LinkML Source

<details>
```yaml
name: schema_name
description: No slot (predicate) description specified
comments:
- 28216 occurrences with subject type schema_Dataset and object type string.
- 56432 occurrences with subject type schema_DataDownload and object type string.
- 41703 occurrences with subject type schema_GovernmentOrganization and object type
  string.
- 28216 occurrences with subject type schema_PropertyValue and object type string.
- 45727 occurrences with untyped subjects and object type string.
- 243268 occurrences with subject type schema_Place and object type string.
- 201357 occurrences with subject type hyf__HY_HydroLocation and object type string.
- 2741 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
  and object type string.
- 247 occurrences with subject type schema_Organization and object type string.
- 165029 occurrences with subject type schema_CreativeWork and object type string.
examples:
- description: schema_Dataset → string
  object:
    example_object: USGS-293229091230800
    example_predicate: schema:name
    example_subject: _:b1000000
- description: schema_DataDownload → string
  object:
    example_object: USGS SensorThings API
    example_predicate: schema:name
    example_subject: _:b1000004
- description: schema_GovernmentOrganization → string
  object:
    example_object: U.S. Geological Survey Water Data for the Nation
    example_predicate: schema:name
    example_subject: _:b1000006
- description: schema_PropertyValue → string
  object:
    example_object: Gage height
    example_predicate: schema:name
    example_subject: _:b1000007
- description: None → string
  object:
    example_object: Mancos River at Anitas Flat Below Mancos CO
    example_predicate: schema:name
    example_subject: _:b1548067
- description: schema_Place → string
  object:
    example_object: New England Region
    example_predicate: schema:name
    example_subject: https://geoconnex.us/ref/hu02/01
- description: hyf__HY_HydroLocation → string
  object:
    example_object: BIG CREEK
    example_predicate: schema:name
    example_subject: https://geoconnex.us/iow/demo/AL00017
- description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    → string
  object:
    example_object: ALCOVA
    example_predicate: schema:name
    example_subject: https://geoconnex.us/ornl/hydrosource/dams/1
- description: schema_Organization → string
  object:
    example_object: CUAHSI_CUAHSI_HIS_CRWA_ids__0
    example_predicate: schema:name
    example_subject: https://gleaner.io/id/org/CUAHSI_CUAHSI_HIS_CRWA_ids__0
- description: schema_CreativeWork → string
  object:
    example_object: HUC12 Pour Points
    example_predicate: schema:name
    example_subject: https://gleaner.io/xid/genid/cksjodsip8t6t2qulttg
from_schema: geoconnex
rank: 1000
slot_uri: schema:name
alias: schema_name
domain_of:
- http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
- hyf__HY_HydroLocation
- schema_CreativeWork
- schema_DataDownload
- schema_Dataset
- schema_GovernmentOrganization
- schema_Organization
- schema_Place
- schema_PropertyValue
range: string

```
</details>