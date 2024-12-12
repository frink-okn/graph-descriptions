

# Slot: sdoh_name


_No slot description provided_





URI: [sdoh:name](http://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No type description provided |  no  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No type description provided |  no  |
| [SecurechainHardware](../classes/SecurechainHardware.md) | No type description provided |  no  |
| [SdohOrganization](../classes/SdohOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [SdohCreativeWork](../classes/SdohCreativeWork.md) | The most generic kind of creative work, including books, movies, photographs,... |  no  |
| [SecurechainLicense](../classes/SecurechainLicense.md) | No type description provided |  no  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Value |
| --- |
| securechain:Hardware/nvr1xxx sdoh:name nvr1xxx |
| schema:Organization/opencaching sdoh:name opencaching |
| securechain:Software/libdime sdoh:name libdime |
| securechain:License/mit sdoh:name MIT License |

## Comments

* 53378 occurrences with subject type securechain_Hardware and object type string.
* 22002 occurrences with subject type sdoh_Organization and object type string.
* 34469 occurrences with subject type securechain_Software and object type string.
* 20 occurrences with subject type sdoh_CreativeWork and object type string.

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
| self | sdoh:name |
| native | secure-chain-kg/:sdoh_name |




## LinkML Source

<details>
```yaml
name: sdoh_name
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 53378 occurrences with subject type securechain_Hardware and object type string.
- 22002 occurrences with subject type sdoh_Organization and object type string.
- 34469 occurrences with subject type securechain_Software and object type string.
- 20 occurrences with subject type sdoh_CreativeWork and object type string.
examples:
- value: securechain:Hardware/nvr1xxx sdoh:name nvr1xxx
- value: schema:Organization/opencaching sdoh:name opencaching
- value: securechain:Software/libdime sdoh:name libdime
- value: securechain:License/mit sdoh:name MIT License
from_schema: secure-chain-kg
rank: 1000
slot_uri: sdoh:name
alias: sdoh_name
domain_of:
- sdoh_CreativeWork
- sdoh_Organization
- securechain_Hardware
- securechain_Software
range: string

```
</details>