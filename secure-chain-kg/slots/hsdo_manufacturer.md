

# Slot: hsdo_manufacturer


_No slot (predicate) description specified_





URI: [hsdo:manufacturer](http://schema.org/manufacturer)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |







## Properties

* Range: [SecurechainHardware](../classes/SecurechainHardware.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Organization → securechain_Hardware | schema:Organization/zzinc | hsdo:manufacturer | securechain:Hardware/keymouse |


## Comments

* 54369 occurrences with subject type hsdo_Organization and object type securechain_Hardware.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:manufacturer |
| native | secure-chain-kg/:hsdo_manufacturer |




## LinkML Source

<details>
```yaml
name: hsdo_manufacturer
description: No slot (predicate) description specified
comments:
- 54369 occurrences with subject type hsdo_Organization and object type securechain_Hardware.
examples:
- description: hsdo_Organization → securechain_Hardware
  object:
    example_object: securechain:Hardware/keymouse
    example_object_type: securechain_Hardware
    example_predicate: hsdo:manufacturer
    example_subject: schema:Organization/zzinc
    example_subject_type: hsdo_Organization
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:manufacturer
alias: hsdo_manufacturer
domain_of:
- hsdo_Organization
range: securechain_Hardware

```
</details>