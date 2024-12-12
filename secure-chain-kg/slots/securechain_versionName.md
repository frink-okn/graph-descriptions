

# Slot: securechain_versionName


_No slot description provided_





URI: [securechain:versionName](https://w3id.org/secure-chain/versionName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No type description provided |  no  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Value |
| --- |
| securechain:SoftwareVersion/libaudcore5#%3E%3D+3.9 securechain:versionName >= 3.9 |
| securechain:HardwareVersion/vantage_velocity#- securechain:versionName - |

## Comments

* 164001 occurrences with subject type securechain_SoftwareVersion and object type string.
* 57295 occurrences with subject type securechain_HardwareVersion and object type string.

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
| self | securechain:versionName |
| native | secure-chain-kg/:securechain_versionName |




## LinkML Source

<details>
```yaml
name: securechain_versionName
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 164001 occurrences with subject type securechain_SoftwareVersion and object type
  string.
- 57295 occurrences with subject type securechain_HardwareVersion and object type
  string.
examples:
- value: securechain:SoftwareVersion/libaudcore5#%3E%3D+3.9 securechain:versionName
    >= 3.9
- value: securechain:HardwareVersion/vantage_velocity#- securechain:versionName -
from_schema: secure-chain-kg
rank: 1000
slot_uri: securechain:versionName
alias: securechain_versionName
domain_of:
- securechain_HardwareVersion
- securechain_SoftwareVersion
range: string

```
</details>