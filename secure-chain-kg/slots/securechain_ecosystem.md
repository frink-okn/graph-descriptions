

# Slot: No slot (predicate) name specified (securechain_ecosystem)


_No slot (predicate) description specified_






This slot occurs 803769 times.


URI: [securechain:ecosystem](https://w3id.org/secure-chain/ecosystem)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | No class (type) description specified |  no  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No class (type) description specified |  yes  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainHardware](../classes/SecurechainHardware.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoText](../classes/HsdoText.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_Software | string | https://www.google.com/search?q=amd | Unknown | 803747 |
| securechain_Hardware | string | https://www.google.com/search?q=st | Unknown | 22 |




## LinkML Source

<details>

```yaml
name: securechain_ecosystem
annotations:
  count:
    tag: count
    value: 803769
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Unknown
    example_object_type: string
    example_predicate: securechain:ecosystem
    example_subject: https://www.google.com/search?q=amd
    example_subject_type: securechain_Software
- object:
    example_object: Unknown
    example_object_type: string
    example_predicate: securechain:ecosystem
    example_subject: https://www.google.com/search?q=st
    example_subject_type: securechain_Hardware
from_schema: secure-chain-kg
rank: 1000
domain: securechain_Software
slot_uri: securechain:ecosystem
alias: securechain_ecosystem
domain_of:
- hsdo_Organization
- securechain_Hardware
- securechain_Software
range: Any
any_of:
- range: hsdo_Text
- range: string

```
</details>