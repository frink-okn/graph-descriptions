

# Slot: hsdo_contributor


_No slot (predicate) description specified_






This slot occurs 32408 times.


URI: [hsdo:contributor](http://schema.org/contributor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No class (type) description specified |  yes  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |







## Properties

* Range: [HsdoPerson](../classes/HsdoPerson.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_Software | hsdo_Person | https://github.com/0vercl0k/rp | https://github.com/0vercl0k | 32408 |




## LinkML Source

<details>

```yaml
name: hsdo_contributor
annotations:
  count:
    tag: count
    value: 32408
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://github.com/0vercl0k
    example_object_type: hsdo_Person
    example_predicate: hsdo:contributor
    example_subject: https://github.com/0vercl0k/rp
    example_subject_type: securechain_Software
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:contributor
alias: hsdo_contributor
domain_of:
- securechain_Software
range: hsdo_Person

```
</details>