

# Slot: niem50_AddressCityName


_No slot (predicate) description specified_





URI: [niem50:AddressCityName](http://release.niem.gov/niem/niem-core/5.0/AddressCityName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72DetentionFacility](../classes/Jxdm72DetentionFacility.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_DetentionFacility → string | scales/BookingDetentionFacility/ga-fulton-01 | niem50:AddressCityName | Atlanta |


## Comments

* 1 occurrences with subject type jxdm72_DetentionFacility and object type string.



## LinkML Source

<details>

```yaml
name: niem50_AddressCityName
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type jxdm72_DetentionFacility and object type string.
examples:
- description: jxdm72_DetentionFacility → string
  object:
    example_object: Atlanta
    example_object_type: string
    example_predicate: niem50:AddressCityName
    example_subject: scales/BookingDetentionFacility/ga-fulton-01
    example_subject_type: jxdm72_DetentionFacility
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:AddressCityName
alias: niem50_AddressCityName
domain_of:
- jxdm72_DetentionFacility
range: string

```
</details>