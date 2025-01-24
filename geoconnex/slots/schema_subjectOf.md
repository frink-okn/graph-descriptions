

# Slot: schema_subjectOf


_No slot (predicate) description specified_





URI: [schema:subjectOf](https://schema.org/subjectOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation](../classes/HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation.md) | No class (type) description specified |  no  |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SchemaDataset](../classes/SchemaDataset.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → uri | https://geoconnex.us/ref/hu02/01 | schema:subjectOf | https://geonames.usgs.gov/apex/f?p=gnispq:3:::NO::P3_FID:2730131 |
| http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation → uri | https://geoconnex.us/ornl/hydrosource/dams/1 | schema:subjectOf | https://hydrosource.ornl.gov/dataset/existing-hydropower-assets-eha-capacity-factor-plant-database-2005-2019 |
| hyf__HY_HydroLocation → uri | https://geoconnex.us/ref/gages/1000001 | schema:subjectOf | _:b1159177 |
| hyf__HY_HydroLocation → schema_Dataset | https://sta.geoconnex.dev/collections/USGS/Things/items/'USGS-625632151172901' | schema:subjectOf | _:b939199 |


## Comments

* 78891 occurrences with subject type schema_Place and object type uri.
* 8804 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type uri.
* 185645 occurrences with subject type hyf__HY_HydroLocation and object type uri.
* 28216 occurrences with subject type hyf__HY_HydroLocation and object type schema_Dataset.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:subjectOf |
| native | geoconnex/:schema_subjectOf |




## LinkML Source

<details>
```yaml
name: schema_subjectOf
description: No slot (predicate) description specified
comments:
- 78891 occurrences with subject type schema_Place and object type uri.
- 8804 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
  and object type uri.
- 185645 occurrences with subject type hyf__HY_HydroLocation and object type uri.
- 28216 occurrences with subject type hyf__HY_HydroLocation and object type schema_Dataset.
examples:
- description: schema_Place → uri
  object:
    example_object: https://geonames.usgs.gov/apex/f?p=gnispq:3:::NO::P3_FID:2730131
    example_predicate: schema:subjectOf
    example_subject: https://geoconnex.us/ref/hu02/01
- description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    → uri
  object:
    example_object: https://hydrosource.ornl.gov/dataset/existing-hydropower-assets-eha-capacity-factor-plant-database-2005-2019
    example_predicate: schema:subjectOf
    example_subject: https://geoconnex.us/ornl/hydrosource/dams/1
- description: hyf__HY_HydroLocation → uri
  object:
    example_object: _:b1159177
    example_predicate: schema:subjectOf
    example_subject: https://geoconnex.us/ref/gages/1000001
- description: hyf__HY_HydroLocation → schema_Dataset
  object:
    example_object: _:b939199
    example_predicate: schema:subjectOf
    example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'USGS-625632151172901'
from_schema: geoconnex
rank: 1000
slot_uri: schema:subjectOf
alias: schema_subjectOf
domain_of:
- http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
- hyf__HY_HydroLocation
- schema_Place
range: Any
any_of:
- range: schema_Dataset
- range: uri

```
</details>