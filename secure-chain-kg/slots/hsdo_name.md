

# Slot: hsdo_name


_No slot (predicate) description specified_






This slot occurs 906771 times.


URI: [hsdo:name](http://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | No class (type) description specified |  yes  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No class (type) description specified |  yes  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |
| [HsdoPerson](../classes/HsdoPerson.md) | No class (type) description specified |  yes  |
| [SecurechainLicense](../classes/SecurechainLicense.md) | No class (type) description specified |  yes  |
| [SecurechainHardware](../classes/SecurechainHardware.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Person | string | https://github.com/0----0 | 0----0 | 27009 |
| securechain_License | string | https://spdx.org/licenses/0bsd.html | Permission to use, copy, modify, and/or distribute this software for any | 20 |
| hsdo_Organization | string | https://www.google.com/search?q=2n | 2n | 22620 |
| securechain_Hardware | string | https://www.google.com/search?q=360 | 360 | 53378 |
| securechain_Software | string | https://www.google.com/search?q=amd | amd | 803744 |




## LinkML Source

<details>

```yaml
name: hsdo_name
annotations:
  count:
    tag: count
    value: 906771
description: No slot (predicate) description specified
examples:
- object:
    example_object: 0----0
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: https://github.com/0----0
    example_subject_type: hsdo_Person
- object:
    example_object: Permission to use, copy, modify, and/or distribute this software
      for any
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: https://spdx.org/licenses/0bsd.html
    example_subject_type: securechain_License
- object:
    example_object: 2n
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: https://www.google.com/search?q=2n
    example_subject_type: hsdo_Organization
- object:
    example_object: '360'
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: https://www.google.com/search?q=360
    example_subject_type: securechain_Hardware
- object:
    example_object: amd
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: https://www.google.com/search?q=amd
    example_subject_type: securechain_Software
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:name
alias: hsdo_name
domain_of:
- hsdo_Organization
- hsdo_Person
- securechain_Hardware
- securechain_License
- securechain_Software
range: string

```
</details>