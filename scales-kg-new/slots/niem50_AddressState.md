

# Slot: niem50_AddressState


_No slot (predicate) description specified_





URI: [niem50:AddressState](http://release.niem.gov/niem/niem-core/5.0/AddressState)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72DetentionFacility](../classes/Jxdm72DetentionFacility.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_DetentionFacility → string | scales/BookingDetentionFacility/ga-fulton-01 | niem50:AddressState | Georgia |


## Comments

* 1 occurrences with subject type jxdm72_DetentionFacility and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | niem50:AddressState |
| native | scales-kg-new/:niem50_AddressState |




## LinkML Source

<details>
```yaml
name: niem50_AddressState
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type jxdm72_DetentionFacility and object type string.
examples:
- description: jxdm72_DetentionFacility → string
  object:
    example_object: Georgia
    example_object_type: string
    example_predicate: niem50:AddressState
    example_subject: scales/BookingDetentionFacility/ga-fulton-01
    example_subject_type: jxdm72_DetentionFacility
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:AddressState
alias: niem50_AddressState
domain_of:
- jxdm72_DetentionFacility
range: string

```
</details>