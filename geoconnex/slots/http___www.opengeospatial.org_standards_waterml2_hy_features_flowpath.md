

# Slot: http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath


_No slot (predicate) description specified_





URI: [http://www.opengeospatial.org/standards/waterml2/hy_features/flowpath](http://www.opengeospatial.org/standards/waterml2/hy_features/flowpath)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation](../classes/HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation.md) | No class (type) description specified |  no  |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → uri | https://geoconnex.us/ca-gage-assessment/gages/09423350 | http://www.opengeospatial.org/standards/waterml2/hy_features/flowpath | https://geoconnex.us/nhdplusv2/comid/10017314 |
| http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation → uri | https://geoconnex.us/ornl/hydrosource/dams/1 | http://www.opengeospatial.org/standards/waterml2/hy_features/flowpath | https://geoconnex.us/nhdplusv2/comid/NA |


## Comments

* 2536 occurrences with subject type schema_Place and object type uri.
* 3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://www.opengeospatial.org/standards/waterml2/hy_features/flowpath |
| native | geoconnex/:http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath |




## LinkML Source

<details>
```yaml
name: http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath
description: No slot (predicate) description specified
comments:
- 2536 occurrences with subject type schema_Place and object type uri.
- 3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
  and object type uri.
examples:
- description: schema_Place → uri
  object:
    example_object: https://geoconnex.us/nhdplusv2/comid/10017314
    example_predicate: http://www.opengeospatial.org/standards/waterml2/hy_features/flowpath
    example_subject: https://geoconnex.us/ca-gage-assessment/gages/09423350
- description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    → uri
  object:
    example_object: https://geoconnex.us/nhdplusv2/comid/NA
    example_predicate: http://www.opengeospatial.org/standards/waterml2/hy_features/flowpath
    example_subject: https://geoconnex.us/ornl/hydrosource/dams/1
from_schema: geoconnex
rank: 1000
slot_uri: http://www.opengeospatial.org/standards/waterml2/hy_features/flowpath
alias: http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath
domain_of:
- http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
- schema_Place
range: uri

```
</details>