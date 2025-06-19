

# Slot: No slot (predicate) name specified (securechain_hasSoftwareVersion)


_No slot (predicate) description specified_






This slot occurs 8593149 times.


URI: [securechain:hasSoftwareVersion](https://w3id.org/secure-chain/hasSoftwareVersion)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | No class (type) description specified |  yes  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No class (type) description specified |  yes  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainHardware](../classes/SecurechainHardware.md) | No class (type) description specified |  yes  |







## Properties

* Range: [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Organization | securechain_SoftwareVersion | https://www.google.com/search?q=amd | https://www.google.com/search?q=amd+64 | 1437 |
| securechain_Software | securechain_SoftwareVersion | https://www.google.com/search?q=amd | https://www.google.com/search?q=amd+64 | 8593149 |
| securechain_Hardware | securechain_SoftwareVersion | https://www.google.com/search?q=st | https://www.google.com/search?q=st+* | 73 |




## LinkML Source

<details>

```yaml
name: securechain_hasSoftwareVersion
annotations:
  count:
    tag: count
    value: 8593149
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: https://www.google.com/search?q=amd+64
    example_object_type: securechain_SoftwareVersion
    example_predicate: securechain:hasSoftwareVersion
    example_subject: https://www.google.com/search?q=amd
    example_subject_type: hsdo_Organization
- object:
    example_object: https://www.google.com/search?q=amd+64
    example_object_type: securechain_SoftwareVersion
    example_predicate: securechain:hasSoftwareVersion
    example_subject: https://www.google.com/search?q=amd
    example_subject_type: securechain_Software
- object:
    example_object: https://www.google.com/search?q=st+*
    example_object_type: securechain_SoftwareVersion
    example_predicate: securechain:hasSoftwareVersion
    example_subject: https://www.google.com/search?q=st
    example_subject_type: securechain_Hardware
from_schema: secure-chain-kg
rank: 1000
domain: securechain_Software
slot_uri: securechain:hasSoftwareVersion
alias: securechain_hasSoftwareVersion
domain_of:
- hsdo_Organization
- securechain_Hardware
- securechain_Software
range: securechain_SoftwareVersion

```
</details>