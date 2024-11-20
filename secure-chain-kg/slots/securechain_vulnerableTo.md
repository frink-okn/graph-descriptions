

# Slot: securechain_vulnerableTo


_TODO -- tell the world what this slot (predicate) describes._





URI: [securechain:vulnerableTo](https://w3id.org/secure-chain/vulnerableTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SecurechainVulnerability](../classes/SecurechainVulnerability.md)&nbsp;or&nbsp;<br />[SecurechainVulnerability](../classes/SecurechainVulnerability.md)






## Examples

| Value |
| --- |
| securechain:HardwareVersion/xeon_e5-2699r_v4#- securechain:vulnerableTo securechain:Vulnerability/CVE-2021-0114 |
| securechain:SoftwareVersion/mapserver#4.10.0-5%2Betch1 securechain:vulnerableTo securechain:Vulnerability/CVE-2009-0839 |

## Comments

* 445386 occurrences with subject type securechain_HardwareVersion and object type securechain_Vulnerability.
* 5067 occurrences with subject type securechain_SoftwareVersion and object type securechain_Vulnerability.
* 21897 occurrences on untyped entities with type securechain_Vulnerability.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg/develop




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:vulnerableTo |
| native | secure-chain-kg/develop/:securechain_vulnerableTo |




## LinkML Source

<details>
```yaml
name: securechain_vulnerableTo
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 445386 occurrences with subject type securechain_HardwareVersion and object type
  securechain_Vulnerability.
- 5067 occurrences with subject type securechain_SoftwareVersion and object type securechain_Vulnerability.
- 21897 occurrences on untyped entities with type securechain_Vulnerability.
examples:
- value: securechain:HardwareVersion/xeon_e5-2699r_v4#- securechain:vulnerableTo securechain:Vulnerability/CVE-2021-0114
- value: securechain:SoftwareVersion/mapserver#4.10.0-5%2Betch1 securechain:vulnerableTo
    securechain:Vulnerability/CVE-2009-0839
from_schema: secure-chain-kg/develop
rank: 1000
slot_uri: securechain:vulnerableTo
alias: securechain_vulnerableTo
domain_of:
- securechain_HardwareVersion
- securechain_SoftwareVersion
range: Any
any_of:
- range: securechain_Vulnerability
- range: securechain_Vulnerability

```
</details>