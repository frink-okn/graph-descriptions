

# Slot: manufacturer (hsdo_manufacturer)


_The manufacturer of the product._






This slot occurs 54369 times.


URI: [hsdo:manufacturer](http://schema.org/manufacturer)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  yes  |







## Properties

* Range: [SecurechainHardware](../classes/SecurechainHardware.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Organization | securechain_Hardware | schema:Organization/2n | securechain:Hardware/access_unit_2.0 | 54369 |




## LinkML Source

<details>

```yaml
name: hsdo_manufacturer
annotations:
  count:
    tag: count
    value: 54369
description: The manufacturer of the product.
title: manufacturer
examples:
- object:
    example_object: securechain:Hardware/access_unit_2.0
    example_object_type: securechain_Hardware
    example_predicate: hsdo:manufacturer
    example_subject: schema:Organization/2n
    example_subject_type: hsdo_Organization
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:manufacturer
alias: hsdo_manufacturer
domain_of:
- hsdo_Organization
range: securechain_Hardware

```
</details>