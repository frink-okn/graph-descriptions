

# Slot: No slot (predicate) name specified (securechain_vulnerableTo)


_No slot (predicate) description specified_






This slot occurs 835140 times.


URI: [securechain:vulnerableTo](https://w3id.org/secure-chain/vulnerableTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  yes  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  yes  |







## Properties

* Range: [SecurechainVulnerability](../classes/SecurechainVulnerability.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_SoftwareVersion | securechain_Vulnerability | https://conan.io/center/recipes/asn1c?version=0.9.28 | https://nvd.nist.gov/vuln/detail/CVE-2017-12966 | 383356 |
| securechain_HardwareVersion | securechain_Vulnerability | https://www.google.com/search?q=-+- | https://nvd.nist.gov/vuln/detail/CVE-2019-0162 | 451784 |




## LinkML Source

<details>

```yaml
name: securechain_vulnerableTo
annotations:
  count:
    tag: count
    value: 835140
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: https://nvd.nist.gov/vuln/detail/CVE-2017-12966
    example_object_type: securechain_Vulnerability
    example_predicate: securechain:vulnerableTo
    example_subject: https://conan.io/center/recipes/asn1c?version=0.9.28
    example_subject_type: securechain_SoftwareVersion
- object:
    example_object: https://nvd.nist.gov/vuln/detail/CVE-2019-0162
    example_object_type: securechain_Vulnerability
    example_predicate: securechain:vulnerableTo
    example_subject: https://www.google.com/search?q=-+-
    example_subject_type: securechain_HardwareVersion
from_schema: secure-chain-kg
rank: 1000
domain: securechain_SoftwareVersion
slot_uri: securechain:vulnerableTo
alias: securechain_vulnerableTo
domain_of:
- securechain_HardwareVersion
- securechain_SoftwareVersion
range: securechain_Vulnerability

```
</details>