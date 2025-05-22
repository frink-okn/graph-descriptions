

# Slot: hsdo_license


_No slot (predicate) description specified_






This slot occurs 5018025 times.


URI: [hsdo:license](http://schema.org/license)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  yes  |







## Properties

* Range: [SecurechainLicense](../classes/SecurechainLicense.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_SoftwareVersion | securechain_License | https://crates.io/crates/a-bot/0.0.1/ | https://spdx.org/licenses/BSD-3-Clause.html | 5018025 |




## LinkML Source

<details>

```yaml
name: hsdo_license
annotations:
  count:
    tag: count
    value: 5018025
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://spdx.org/licenses/BSD-3-Clause.html
    example_object_type: securechain_License
    example_predicate: hsdo:license
    example_subject: https://crates.io/crates/a-bot/0.0.1/
    example_subject_type: securechain_SoftwareVersion
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:license
alias: hsdo_license
domain_of:
- securechain_SoftwareVersion
range: securechain_License

```
</details>