

# Slot: securechain_vulnerableTo


_No slot (predicate) description specified_





URI: [securechain:vulnerableTo](https://w3id.org/secure-chain/vulnerableTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  no  |







## Properties

* Range: [SecurechainVulnerability](../classes/SecurechainVulnerability.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| securechain_HardwareVersion → securechain_Vulnerability | securechain:HardwareVersion/zz_qcs605#- | securechain:vulnerableTo | securechain:Vulnerability/CVE-2018-13888 |
| securechain_SoftwareVersion → securechain_Vulnerability | securechain:SoftwareVersion/zutils#1.8-3 | securechain:vulnerableTo | securechain:Vulnerability/CVE-2018-1000637 |
| None → securechain_Vulnerability | securechain:HardwareVersion/zywall_2#%2A | securechain:vulnerableTo | securechain:Vulnerability/CVE-2007-4319 |


## Comments

* 445386 occurrences with subject type securechain_HardwareVersion and object type securechain_Vulnerability.
* 5067 occurrences with subject type securechain_SoftwareVersion and object type securechain_Vulnerability.
* 21897 occurrences with untyped subjects and object type https://w3id.org/secure-chain/Vulnerability.

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
description: No slot (predicate) description specified
comments:
- 445386 occurrences with subject type securechain_HardwareVersion and object type
  securechain_Vulnerability.
- 5067 occurrences with subject type securechain_SoftwareVersion and object type securechain_Vulnerability.
- 21897 occurrences with untyped subjects and object type https://w3id.org/secure-chain/Vulnerability.
examples:
- description: securechain_HardwareVersion → securechain_Vulnerability
  object:
    example_object: securechain:Vulnerability/CVE-2018-13888
    example_object_type: securechain_Vulnerability
    example_predicate: securechain:vulnerableTo
    example_subject: securechain:HardwareVersion/zz_qcs605#-
    example_subject_type: securechain_HardwareVersion
- description: securechain_SoftwareVersion → securechain_Vulnerability
  object:
    example_object: securechain:Vulnerability/CVE-2018-1000637
    example_object_type: securechain_Vulnerability
    example_predicate: securechain:vulnerableTo
    example_subject: securechain:SoftwareVersion/zutils#1.8-3
    example_subject_type: securechain_SoftwareVersion
- description: None → securechain_Vulnerability
  object:
    example_object: securechain:Vulnerability/CVE-2007-4319
    example_object_type: securechain_Vulnerability
    example_predicate: securechain:vulnerableTo
    example_subject: securechain:HardwareVersion/zywall_2#%2A
    example_subject_type: None
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