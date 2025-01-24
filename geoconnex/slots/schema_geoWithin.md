

# Slot: schema_geoWithin


_No slot (predicate) description specified_





URI: [schema:geoWithin](https://schema.org/geoWithin)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation](../classes/HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation.md) | No class (type) description specified |  no  |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)&nbsp;or&nbsp;<br />[SchemaPlace](../classes/SchemaPlace.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → schema_Place | https://geoconnex.us/ref/pws/WY5680122 | schema:geoWithin | https://geoconnex.us/ref/states/56 |
| schema_Place → uri | https://geoconnex.us/ca-gage-assessment/gages/09423350 | schema:geoWithin | https://geoconnex.us/nhdplusv2/huc12/150301020203 |
| hyf__HY_HydroLocation → string | https://geoconnex.us/iow/demo/AL00017 | schema:geoWithin | https://geoconnex.us/ref/hu08/03170008 |
| http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation → schema_Place | https://geoconnex.us/ornl/hydrosource/dams/999 | schema:geoWithin | https://geoconnex.us/ref/states/53 |
| http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation → uri | https://geoconnex.us/ornl/hydrosource/dams/1 | schema:geoWithin | https://geoconnex.us/nhdplusv2/huc12/102000000000 |


## Comments

* 53554 occurrences with subject type schema_Place and object type schema_Place.
* 2536 occurrences with subject type schema_Place and object type uri.
* 2014 occurrences with subject type hyf__HY_HydroLocation and object type string.
* 3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type schema_Place.
* 3075 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:geoWithin |
| native | geoconnex/:schema_geoWithin |




## LinkML Source

<details>
```yaml
name: schema_geoWithin
description: No slot (predicate) description specified
comments:
- 53554 occurrences with subject type schema_Place and object type schema_Place.
- 2536 occurrences with subject type schema_Place and object type uri.
- 2014 occurrences with subject type hyf__HY_HydroLocation and object type string.
- 3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
  and object type schema_Place.
- 3075 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
  and object type uri.
examples:
- description: schema_Place → schema_Place
  object:
    example_object: https://geoconnex.us/ref/states/56
    example_predicate: schema:geoWithin
    example_subject: https://geoconnex.us/ref/pws/WY5680122
- description: schema_Place → uri
  object:
    example_object: https://geoconnex.us/nhdplusv2/huc12/150301020203
    example_predicate: schema:geoWithin
    example_subject: https://geoconnex.us/ca-gage-assessment/gages/09423350
- description: hyf__HY_HydroLocation → string
  object:
    example_object: https://geoconnex.us/ref/hu08/03170008
    example_predicate: schema:geoWithin
    example_subject: https://geoconnex.us/iow/demo/AL00017
- description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    → schema_Place
  object:
    example_object: https://geoconnex.us/ref/states/53
    example_predicate: schema:geoWithin
    example_subject: https://geoconnex.us/ornl/hydrosource/dams/999
- description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    → uri
  object:
    example_object: https://geoconnex.us/nhdplusv2/huc12/102000000000
    example_predicate: schema:geoWithin
    example_subject: https://geoconnex.us/ornl/hydrosource/dams/1
from_schema: geoconnex
rank: 1000
slot_uri: schema:geoWithin
alias: schema_geoWithin
domain_of:
- http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
- hyf__HY_HydroLocation
- schema_Place
range: Any
any_of:
- range: uri
- range: string
- range: schema_Place

```
</details>