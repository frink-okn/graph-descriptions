

# Slot: securechain_vulnerableTo


_No slot description provided_





URI: [securechain:vulnerableTo](https://w3id.org/secure-chain/vulnerableTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No type description provided |  no  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No type description provided |  no  |







## Properties

* Range: [SecurechainVulnerability](../classes/SecurechainVulnerability.md)






## Examples

| Value |
| --- |
| securechain:HardwareVersion/x12dpl-i6#- securechain:vulnerableTo securechain:Vulnerability/CVE-2023-33412 |
| securechain:HardwareVersion/wireless-n_7260#- securechain:vulnerableTo securechain:Vulnerability/CVE-2018-12177 |
| securechain:SoftwareVersion/freetype#2.2.1-5 securechain:vulnerableTo securechain:Vulnerability/CVE-2011-0226 |

## Comments

* 445386 occurrences with subject type securechain_HardwareVersion and object type securechain_Vulnerability.
* 21897 occurrences with untyped subjects and object type https://w3id.org/secure-chain/Vulnerability.
* 5067 occurrences with subject type securechain_SoftwareVersion and object type securechain_Vulnerability.

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
| self | securechain:vulnerableTo |
| native | secure-chain-kg/:securechain_vulnerableTo |




## LinkML Source

<details>
```yaml
name: securechain_vulnerableTo
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 445386 occurrences with subject type securechain_HardwareVersion and object type
  securechain_Vulnerability.
- 21897 occurrences with untyped subjects and object type https://w3id.org/secure-chain/Vulnerability.
- 5067 occurrences with subject type securechain_SoftwareVersion and object type securechain_Vulnerability.
examples:
- value: securechain:HardwareVersion/x12dpl-i6#- securechain:vulnerableTo securechain:Vulnerability/CVE-2023-33412
- value: securechain:HardwareVersion/wireless-n_7260#- securechain:vulnerableTo securechain:Vulnerability/CVE-2018-12177
- value: securechain:SoftwareVersion/freetype#2.2.1-5 securechain:vulnerableTo securechain:Vulnerability/CVE-2011-0226
from_schema: secure-chain-kg
rank: 1000
slot_uri: securechain:vulnerableTo
alias: securechain_vulnerableTo
domain_of:
- securechain_HardwareVersion
- securechain_SoftwareVersion
range: securechain_Vulnerability

```
</details>