

# Slot: niem50_AdministrationId


_No slot (predicate) description specified_





URI: [niem50:AdministrationId](http://release.niem.gov/niem/niem-core/5.0/AdministrationId)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72DetentionFacility](../classes/Jxdm72DetentionFacility.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:integer](xsd:integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_DetentionFacility → integer | scales/BookingDetentionFacility/ga-fulton-01 | niem50:AdministrationId | 1 |


## Comments

* 1 occurrences with subject type jxdm72_DetentionFacility and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | niem50:AdministrationId |
| native | scales-kg-new/:niem50_AdministrationId |




## LinkML Source

<details>

```yaml
name: niem50_AdministrationId
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type jxdm72_DetentionFacility and object type integer.
examples:
- description: jxdm72_DetentionFacility → integer
  object:
    example_object: '1'
    example_object_type: integer
    example_predicate: niem50:AdministrationId
    example_subject: scales/BookingDetentionFacility/ga-fulton-01
    example_subject_type: jxdm72_DetentionFacility
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:AdministrationId
alias: niem50_AdministrationId
domain_of:
- jxdm72_DetentionFacility
range: integer

```
</details>