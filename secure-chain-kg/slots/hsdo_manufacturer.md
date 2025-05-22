

# Slot: hsdo_manufacturer


_No slot (predicate) description specified_






This slot occurs 54369 times.


URI: [hsdo:manufacturer](http://schema.org/manufacturer)



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

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoOrganization](../classes/HsdoOrganization.md)&nbsp;or&nbsp;<br />[SecurechainHardware](../classes/SecurechainHardware.md)&nbsp;or&nbsp;<br />[SecurechainSoftware](../classes/SecurechainSoftware.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Organization | hsdo_Organization | https://www.google.com/search?q=360 | https://www.google.com/search?q=hp | 53 |
| securechain_Hardware | hsdo_Organization | https://www.google.com/search?q=360 | https://www.google.com/search?q=hp | 54369 |
| hsdo_Organization | securechain_Hardware | https://www.google.com/search?q=arduino | https://www.google.com/search?q=arduino | 23 |
| securechain_Hardware | securechain_Hardware | https://www.google.com/search?q=arduino | https://www.google.com/search?q=arduino | 2372 |
| hsdo_Organization | securechain_Software | https://www.google.com/search?q=milan | https://www.google.com/search?q=amd | 1 |
| securechain_Hardware | securechain_Software | https://www.google.com/search?q=milan | https://www.google.com/search?q=amd | 1252 |
| securechain_Software | hsdo_Organization | https://www.google.com/search?q=st | https://www.google.com/search?q=mitel | 26 |
| securechain_Software | securechain_Software | https://www.google.com/search?q=rift | https://www.google.com/search?q=oculus | 1 |




## LinkML Source

<details>

```yaml
name: hsdo_manufacturer
annotations:
  count:
    tag: count
    value: 54369
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://www.google.com/search?q=hp
    example_object_type: hsdo_Organization
    example_predicate: hsdo:manufacturer
    example_subject: https://www.google.com/search?q=360
    example_subject_type: hsdo_Organization
- object:
    example_object: https://www.google.com/search?q=hp
    example_object_type: hsdo_Organization
    example_predicate: hsdo:manufacturer
    example_subject: https://www.google.com/search?q=360
    example_subject_type: securechain_Hardware
- object:
    example_object: https://www.google.com/search?q=arduino
    example_object_type: securechain_Hardware
    example_predicate: hsdo:manufacturer
    example_subject: https://www.google.com/search?q=arduino
    example_subject_type: hsdo_Organization
- object:
    example_object: https://www.google.com/search?q=arduino
    example_object_type: securechain_Hardware
    example_predicate: hsdo:manufacturer
    example_subject: https://www.google.com/search?q=arduino
    example_subject_type: securechain_Hardware
- object:
    example_object: https://www.google.com/search?q=amd
    example_object_type: securechain_Software
    example_predicate: hsdo:manufacturer
    example_subject: https://www.google.com/search?q=milan
    example_subject_type: hsdo_Organization
- object:
    example_object: https://www.google.com/search?q=amd
    example_object_type: securechain_Software
    example_predicate: hsdo:manufacturer
    example_subject: https://www.google.com/search?q=milan
    example_subject_type: securechain_Hardware
- object:
    example_object: https://www.google.com/search?q=mitel
    example_object_type: hsdo_Organization
    example_predicate: hsdo:manufacturer
    example_subject: https://www.google.com/search?q=st
    example_subject_type: securechain_Software
- object:
    example_object: https://www.google.com/search?q=oculus
    example_object_type: securechain_Software
    example_predicate: hsdo:manufacturer
    example_subject: https://www.google.com/search?q=rift
    example_subject_type: securechain_Software
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:manufacturer
alias: hsdo_manufacturer
domain_of:
- hsdo_Organization
- securechain_Hardware
- securechain_Software
range: Any
any_of:
- range: hsdo_Organization
- range: securechain_Hardware
- range: securechain_Software

```
</details>