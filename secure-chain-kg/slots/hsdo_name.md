

# Slot: name (hsdo_name)


_The name of the item._






This slot occurs 109866 times.


URI: [hsdo:name](http://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  yes  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No class (type) description specified |  yes  |
| [SecurechainHardware](../classes/SecurechainHardware.md) | No class (type) description specified |  yes  |
| [HsdoCreativeWork](../classes/HsdoCreativeWork.md) | The most generic kind of creative work, including books, movies, photographs,... |  yes  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainLicense](../classes/SecurechainLicense.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| securechain_Hardware | string | securechain:Hardware/- | - | 53378 |
| hsdo_Organization | string | schema:Organization/%25240.99_kindle_books_project | %240.99_kindle_books_project | 22002 |
| hsdo_CreativeWork | string | securechain:License/0bsd | Permission to use, copy, modify, and/or distribute this software for any | 20 |
| securechain_Software | string | securechain:Software/ |  | 34466 |




## LinkML Source

<details>

```yaml
name: hsdo_name
annotations:
  count:
    tag: count
    value: 109866
description: The name of the item.
title: name
examples:
- object:
    example_object: '-'
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: securechain:Hardware/-
    example_subject_type: securechain_Hardware
- object:
    example_object: '%240.99_kindle_books_project'
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: schema:Organization/%25240.99_kindle_books_project
    example_subject_type: hsdo_Organization
- object:
    example_object: Permission to use, copy, modify, and/or distribute this software
      for any
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: securechain:License/0bsd
    example_subject_type: hsdo_CreativeWork
- object:
    example_object: ''
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: securechain:Software/
    example_subject_type: securechain_Software
from_schema: secure-chain-kg
rank: 1000
slot_uri: hsdo:name
alias: hsdo_name
domain_of:
- hsdo_CreativeWork
- hsdo_Organization
- securechain_Hardware
- securechain_Software
range: string

```
</details>