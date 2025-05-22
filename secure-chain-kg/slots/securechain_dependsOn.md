

# Slot: No slot (predicate) name specified (securechain_dependsOn)


_No slot (predicate) description specified_






This slot occurs 29787726 times.


URI: [securechain:dependsOn](https://w3id.org/secure-chain/dependsOn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  yes  |







## Properties

* Range: [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_SoftwareVersion | securechain_SoftwareVersion | https://conan.io/center/recipes/7bitconf?version=1.0.0 | https://conan.io/center/recipes/taocpp-json?version=1.0.0-beta.14 | 29574574 |
| None | securechain_SoftwareVersion | https://github.com/ArduinoJson/releases/tag/v4.0 | https://www.google.com/search?q=arduinojson+* | 213152 |




## LinkML Source

<details>

```yaml
name: securechain_dependsOn
annotations:
  count:
    tag: count
    value: 29787726
  securechain_SoftwareVersion:
    tag: securechain_SoftwareVersion
    value: 213152
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: https://conan.io/center/recipes/taocpp-json?version=1.0.0-beta.14
    example_object_type: securechain_SoftwareVersion
    example_predicate: securechain:dependsOn
    example_subject: https://conan.io/center/recipes/7bitconf?version=1.0.0
    example_subject_type: securechain_SoftwareVersion
- object:
    example_object: https://www.google.com/search?q=arduinojson+*
    example_object_type: securechain_SoftwareVersion
    example_predicate: securechain:dependsOn
    example_subject: https://github.com/ArduinoJson/releases/tag/v4.0
    example_subject_type: None
from_schema: secure-chain-kg
rank: 1000
domain: securechain_SoftwareVersion
slot_uri: securechain:dependsOn
alias: securechain_dependsOn
domain_of:
- securechain_SoftwareVersion
range: securechain_SoftwareVersion

```
</details>