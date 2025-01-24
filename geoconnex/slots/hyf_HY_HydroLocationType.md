

# Slot: hyf_HY_HydroLocationType


_No slot (predicate) description specified_





URI: [hyf:HY_HydroLocationType](https://www.opengis.net/def/schema/hy_features/hyfHY_HydroLocationType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation](../classes/HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation.md) | No class (type) description specified |  no  |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hyf__HY_HydroLocation → string | https://geoconnex.us/ref/gages/1000482 | hyf:HY_HydroLocationType | hydrometricStation |
| http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation → string | https://waterdata.usgs.gov/monitoring-location/00000000/ | hyf:HY_HydroLocationType | hydrometricStation |


## Comments

* 42 occurrences with subject type hyf__HY_HydroLocation and object type string.
* 1617371 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hyf:HY_HydroLocationType |
| native | geoconnex/:hyf_HY_HydroLocationType |




## LinkML Source

<details>
```yaml
name: hyf_HY_HydroLocationType
description: No slot (predicate) description specified
comments:
- 42 occurrences with subject type hyf__HY_HydroLocation and object type string.
- 1617371 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
  and object type string.
examples:
- description: hyf__HY_HydroLocation → string
  object:
    example_object: hydrometricStation
    example_predicate: hyf:HY_HydroLocationType
    example_subject: https://geoconnex.us/ref/gages/1000482
- description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    → string
  object:
    example_object: hydrometricStation
    example_predicate: hyf:HY_HydroLocationType
    example_subject: https://waterdata.usgs.gov/monitoring-location/00000000/
from_schema: geoconnex
rank: 1000
slot_uri: hyf:HY_HydroLocationType
alias: hyf_HY_HydroLocationType
domain_of:
- http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
- hyf__HY_HydroLocation
range: string

```
</details>