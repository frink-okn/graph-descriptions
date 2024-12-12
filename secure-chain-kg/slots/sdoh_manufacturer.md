

# Slot: sdoh_manufacturer


_No slot description provided_





URI: [sdoh:manufacturer](http://schema.org/manufacturer)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohOrganization](../classes/SdohOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |







## Properties

* Range: [SecurechainHardware](../classes/SecurechainHardware.md)






## Examples

| Value |
| --- |
| schema:Organization/hp sdoh:manufacturer securechain:Hardware/laptop_15-da0xxx |

## Comments

* 54369 occurrences with subject type sdoh_Organization and object type securechain_Hardware.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:manufacturer |
| native | secure-chain-kg/:sdoh_manufacturer |




## LinkML Source

<details>
```yaml
name: sdoh_manufacturer
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 54369 occurrences with subject type sdoh_Organization and object type securechain_Hardware.
examples:
- value: schema:Organization/hp sdoh:manufacturer securechain:Hardware/laptop_15-da0xxx
from_schema: secure-chain-kg
rank: 1000
slot_uri: sdoh:manufacturer
alias: sdoh_manufacturer
domain_of:
- sdoh_Organization
range: securechain_Hardware

```
</details>