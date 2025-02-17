

# Slot: No slot (predicate) name specified (securechain_vulnerableTo)


_No slot (predicate) description specified_






This slot occurs 472350 times.


URI: [securechain:vulnerableTo](https://w3id.org/secure-chain/vulnerableTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  yes  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  yes  |







## Properties

* Range: [SecurechainVulnerability](../classes/SecurechainVulnerability.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_HardwareVersion | securechain_Vulnerability | securechain:HardwareVersion/-#- | securechain:Vulnerability/CVE-2019-0162 | 445386 |
| securechain_SoftwareVersion | securechain_Vulnerability | securechain:SoftwareVersion/abiword#3.0.2-2%2Bdeb9u2 | securechain:Vulnerability/CVE-2017-17529 | 5067 |
| None | securechain_Vulnerability | securechain:HardwareVersion/zywall_2#%2A | securechain:Vulnerability/CVE-2007-4319 | 21897 |




## LinkML Source

<details>

```yaml
name: securechain_vulnerableTo
annotations:
  count:
    tag: count
    value: 472350
  securechain_Vulnerability:
    tag: securechain_Vulnerability
    value: 21897
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: securechain:Vulnerability/CVE-2019-0162
    example_object_type: securechain_Vulnerability
    example_predicate: securechain:vulnerableTo
    example_subject: securechain:HardwareVersion/-#-
    example_subject_type: securechain_HardwareVersion
- object:
    example_object: securechain:Vulnerability/CVE-2017-17529
    example_object_type: securechain_Vulnerability
    example_predicate: securechain:vulnerableTo
    example_subject: securechain:SoftwareVersion/abiword#3.0.2-2%2Bdeb9u2
    example_subject_type: securechain_SoftwareVersion
- object:
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