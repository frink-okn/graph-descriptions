

# Slot: No slot (predicate) name specified (securechain_hasHardwareVersion)


_No slot (predicate) description specified_






This slot occurs 57295 times.


URI: [securechain:hasHardwareVersion](https://w3id.org/secure-chain/hasHardwareVersion)



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

* Range: [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Organization | securechain_HardwareVersion | https://www.google.com/search?q=360 | https://www.google.com/search?q=360+- | 53 |
| securechain_Hardware | securechain_HardwareVersion | https://www.google.com/search?q=360 | https://www.google.com/search?q=360+- | 57295 |
| securechain_Software | securechain_HardwareVersion | https://www.google.com/search?q=st | https://www.google.com/search?q=st+14.2 | 24 |




## LinkML Source

<details>

```yaml
name: securechain_hasHardwareVersion
annotations:
  count:
    tag: count
    value: 57295
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: https://www.google.com/search?q=360+-
    example_object_type: securechain_HardwareVersion
    example_predicate: securechain:hasHardwareVersion
    example_subject: https://www.google.com/search?q=360
    example_subject_type: hsdo_Organization
- object:
    example_object: https://www.google.com/search?q=360+-
    example_object_type: securechain_HardwareVersion
    example_predicate: securechain:hasHardwareVersion
    example_subject: https://www.google.com/search?q=360
    example_subject_type: securechain_Hardware
- object:
    example_object: https://www.google.com/search?q=st+14.2
    example_object_type: securechain_HardwareVersion
    example_predicate: securechain:hasHardwareVersion
    example_subject: https://www.google.com/search?q=st
    example_subject_type: securechain_Software
from_schema: secure-chain-kg
rank: 1000
domain: securechain_Hardware
slot_uri: securechain:hasHardwareVersion
alias: securechain_hasHardwareVersion
domain_of:
- hsdo_Organization
- securechain_Hardware
- securechain_Software
range: securechain_HardwareVersion

```
</details>