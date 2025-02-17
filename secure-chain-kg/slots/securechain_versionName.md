

# Slot: No slot (predicate) name specified (securechain_versionName)


_No slot (predicate) description specified_






This slot occurs 221295 times.


URI: [securechain:versionName](https://w3id.org/secure-chain/versionName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  yes  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_HardwareVersion | string | securechain:HardwareVersion/-#- | - | 57295 |
| securechain_SoftwareVersion | string | securechain:SoftwareVersion/#%22%2F%2Fapi%23%2A | "//api#* | 164000 |




## LinkML Source

<details>

```yaml
name: securechain_versionName
annotations:
  count:
    tag: count
    value: 221295
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '-'
    example_object_type: string
    example_predicate: securechain:versionName
    example_subject: securechain:HardwareVersion/-#-
    example_subject_type: securechain_HardwareVersion
- object:
    example_object: '"//api#*'
    example_object_type: string
    example_predicate: securechain:versionName
    example_subject: securechain:SoftwareVersion/#%22%2F%2Fapi%23%2A
    example_subject_type: securechain_SoftwareVersion
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