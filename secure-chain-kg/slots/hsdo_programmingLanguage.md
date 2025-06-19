

# Slot: hsdo_programmingLanguage


_No slot (predicate) description specified_






This slot occurs 803769 times.


URI: [hsdo:programmingLanguage](http://schema.org/programmingLanguage)



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

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_Software | string | https://www.google.com/search?q=amd | C/C++ | 803747 |
| securechain_Hardware | string | https://www.google.com/search?q=st | C/C++ | 22 |




## LinkML Source

<details>

```yaml
name: hsdo_programmingLanguage
annotations:
  count:
    tag: count
    value: 803769
description: No slot (predicate) description specified
examples:
- object:
    example_object: C/C++
    example_object_type: string
    example_predicate: hsdo:programmingLanguage
    example_subject: https://www.google.com/search?q=amd
    example_subject_type: securechain_Software
- object:
    example_object: C/C++
    example_object_type: string
    example_predicate: hsdo:programmingLanguage
    example_subject: https://www.google.com/search?q=st
    example_subject_type: securechain_Hardware
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:programmingLanguage
alias: hsdo_programmingLanguage
domain_of:
- hsdo_Organization
- securechain_Hardware
- securechain_Software
range: string

```
</details>