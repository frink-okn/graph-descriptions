

# Slot: No slot (predicate) name specified (securechain_versionName)


_No slot (predicate) description specified_






This slot occurs 8650443 times.


URI: [securechain:versionName](https://w3id.org/secure-chain/versionName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  yes  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoText](../classes/HsdoText.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_SoftwareVersion | string | https://conan.io/center/recipes/7bitconf?version=1.0.0 | 1.0.0 | 8593148 |
| securechain_HardwareVersion | string | https://www.google.com/search?q=-+- | - | 57295 |




## LinkML Source

<details>

```yaml
name: securechain_versionName
annotations:
  count:
    tag: count
    value: 8650443
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: 1.0.0
    example_object_type: string
    example_predicate: securechain:versionName
    example_subject: https://conan.io/center/recipes/7bitconf?version=1.0.0
    example_subject_type: securechain_SoftwareVersion
- object:
    example_object: '-'
    example_object_type: string
    example_predicate: securechain:versionName
    example_subject: https://www.google.com/search?q=-+-
    example_subject_type: securechain_HardwareVersion
from_schema: secure-chain-kg
rank: 1000
domain: __Bcfd3c14c389f3c8ba32c30498a1d8b29
slot_uri: securechain:versionName
alias: securechain_versionName
domain_of:
- securechain_HardwareVersion
- securechain_SoftwareVersion
range: Any
any_of:
- range: hsdo_Text
- range: string

```
</details>