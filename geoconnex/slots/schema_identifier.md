

# Slot: schema_identifier


_No slot (predicate) description specified_





URI: [schema:identifier](https://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaCreativeWork](../classes/SchemaCreativeWork.md) | The most generic kind of creative work, including books, movies, photographs,... |  no  |
| [SchemaOrganization](../classes/SchemaOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation](../classes/HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation.md) | No class (type) description specified |  no  |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)&nbsp;or&nbsp;<br />[SchemaPropertyValue](../classes/SchemaPropertyValue.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation → schema_PropertyValue | https://geoconnex.us/ornl/hydrosource/dams/999 | schema:identifier | https://gleaner.io/xid/genid/ckh8pd4ip8t5ksin207g |
| schema_Organization → schema_PropertyValue | https://gleaner.io/id/org/wade_wade__9 | schema:identifier | https://gleaner.io/genid/geoconnex |
| schema_CreativeWork → string | https://gleaner.io/xid/genid/cksjodsip8t6t2qulttg | schema:identifier | huc12pp |
| hyf__HY_HydroLocation → schema_PropertyValue | https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900' | schema:identifier | _:b850487 |


## Comments

* 40988 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type schema_PropertyValue.
* 247 occurrences with subject type schema_Organization and object type schema_PropertyValue.
* 165029 occurrences with subject type schema_CreativeWork and object type string.
* 13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_PropertyValue.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:identifier |
| native | geoconnex/:schema_identifier |




## LinkML Source

<details>
```yaml
name: schema_identifier
description: No slot (predicate) description specified
comments:
- 40988 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
  and object type schema_PropertyValue.
- 247 occurrences with subject type schema_Organization and object type schema_PropertyValue.
- 165029 occurrences with subject type schema_CreativeWork and object type string.
- 13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_PropertyValue.
examples:
- description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    → schema_PropertyValue
  object:
    example_object: https://gleaner.io/xid/genid/ckh8pd4ip8t5ksin207g
    example_predicate: schema:identifier
    example_subject: https://geoconnex.us/ornl/hydrosource/dams/999
- description: schema_Organization → schema_PropertyValue
  object:
    example_object: https://gleaner.io/genid/geoconnex
    example_predicate: schema:identifier
    example_subject: https://gleaner.io/id/org/wade_wade__9
- description: schema_CreativeWork → string
  object:
    example_object: huc12pp
    example_predicate: schema:identifier
    example_subject: https://gleaner.io/xid/genid/cksjodsip8t6t2qulttg
- description: hyf__HY_HydroLocation → schema_PropertyValue
  object:
    example_object: _:b850487
    example_predicate: schema:identifier
    example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900'
from_schema: geoconnex
rank: 1000
slot_uri: schema:identifier
alias: schema_identifier
domain_of:
- http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
- hyf__HY_HydroLocation
- schema_CreativeWork
- schema_Organization
range: Any
any_of:
- range: string
- range: schema_PropertyValue

```
</details>