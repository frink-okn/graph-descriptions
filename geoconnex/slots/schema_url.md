

# Slot: schema_url


_No slot (predicate) description specified_





URI: [schema:url](https://schema.org/url)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |
| [SchemaDataset](../classes/SchemaDataset.md) | A body of structured information describing some topic(s) of interest |  no  |
| [SchemaOrganization](../classes/SchemaOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [SchemaPropertyValue](../classes/SchemaPropertyValue.md) | A property-value pair, e |  no  |
| [SchemaGovernmentOrganization](../classes/SchemaGovernmentOrganization.md) | A governmental organization or agency |  no  |







## Properties

* Range: [xsd:string](xsd:string)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | [schema_provider](../slots/schema_provider.md) | any_of[range] | [schema_url](../slots/schema_url.md) |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | [schema_provider](../slots/schema_provider.md) | any_of[range] | [schema_url](../slots/schema_url.md) |
| [RdfsResource](../classes/RdfsResource.md) | [schema_provider](../slots/schema_provider.md) | any_of[range] | [schema_url](../slots/schema_url.md) |
| [SchemaDataset](../classes/SchemaDataset.md) | [schema_provider](../slots/schema_provider.md) | any_of[range] | [schema_url](../slots/schema_url.md) |
| [SchemaPlace](../classes/SchemaPlace.md) | [schema_provider](../slots/schema_provider.md) | any_of[range] | [schema_url](../slots/schema_url.md) |







## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Dataset → string | _:b1000000 | schema:url | https://waterdata.usgs.gov/monitoring-location/293229091230800/#parameterCode=00010 |
| schema_GovernmentOrganization → string | _:b1000006 | schema:url | https://waterdata.usgs.gov |
| schema_PropertyValue → string | _:b1000007 | schema:url | https://en.wikipedia.org/w/index.php?search=Gage height |
| None → string | _:b1064837 | schema:url | https://waterdata.usgs.gov/monitoring-location/14206920 |
| schema_Place → string | https://geoconnex.us/ca-gage-assessment/gages/09423350 | schema:url | https://waterdata.usgs.gov |
| schema_Organization → string | https://gleaner.io/id/org/CUAHSI_CUAHSI_HIS_CRWA_ids__0 | schema:url | https://geoconnex.us/sitemap/CUAHSI/CUAHSI_HIS_CRWA_ids__0.xml |


## Comments

* 28216 occurrences with subject type schema_Dataset and object type string.
* 41703 occurrences with subject type schema_GovernmentOrganization and object type string.
* 28217 occurrences with subject type schema_PropertyValue and object type string.
* 185722 occurrences with untyped subjects and object type string.
* 2535 occurrences with subject type schema_Place and object type string.
* 247 occurrences with subject type schema_Organization and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:url |
| native | geoconnex/:schema_url |




## LinkML Source

<details>
```yaml
name: schema_url
description: No slot (predicate) description specified
comments:
- 28216 occurrences with subject type schema_Dataset and object type string.
- 41703 occurrences with subject type schema_GovernmentOrganization and object type
  string.
- 28217 occurrences with subject type schema_PropertyValue and object type string.
- 185722 occurrences with untyped subjects and object type string.
- 2535 occurrences with subject type schema_Place and object type string.
- 247 occurrences with subject type schema_Organization and object type string.
examples:
- description: schema_Dataset → string
  object:
    example_object: https://waterdata.usgs.gov/monitoring-location/293229091230800/#parameterCode=00010
    example_predicate: schema:url
    example_subject: _:b1000000
- description: schema_GovernmentOrganization → string
  object:
    example_object: https://waterdata.usgs.gov
    example_predicate: schema:url
    example_subject: _:b1000006
- description: schema_PropertyValue → string
  object:
    example_object: https://en.wikipedia.org/w/index.php?search=Gage height
    example_predicate: schema:url
    example_subject: _:b1000007
- description: None → string
  object:
    example_object: https://waterdata.usgs.gov/monitoring-location/14206920
    example_predicate: schema:url
    example_subject: _:b1064837
- description: schema_Place → string
  object:
    example_object: https://waterdata.usgs.gov
    example_predicate: schema:url
    example_subject: https://geoconnex.us/ca-gage-assessment/gages/09423350
- description: schema_Organization → string
  object:
    example_object: https://geoconnex.us/sitemap/CUAHSI/CUAHSI_HIS_CRWA_ids__0.xml
    example_predicate: schema:url
    example_subject: https://gleaner.io/id/org/CUAHSI_CUAHSI_HIS_CRWA_ids__0
from_schema: geoconnex
rank: 1000
slot_uri: schema:url
alias: schema_url
domain_of:
- schema_Dataset
- schema_GovernmentOrganization
- schema_Organization
- schema_Place
- schema_PropertyValue
range: string

```
</details>