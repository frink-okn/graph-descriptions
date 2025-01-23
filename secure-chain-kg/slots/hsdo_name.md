

# Slot: hsdo_name


_No slot (predicate) description specified_





URI: [hsdo:name](http://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoCreativeWork](../classes/HsdoCreativeWork.md) | The most generic kind of creative work, including books, movies, photographs,... |  no  |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [SecurechainLicense](../classes/SecurechainLicense.md) | No class (type) description specified |  no  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | No class (type) description specified |  no  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No class (type) description specified |  no  |
| [SecurechainHardware](../classes/SecurechainHardware.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| securechain_Hardware → string | securechain:Hardware/- | hsdo:name | - |
| hsdo_Organization → string | schema:Organization/%25240.99_kindle_books_project | hsdo:name | %240.99_kindle_books_project |
| hsdo_CreativeWork → string | securechain:License/0bsd | hsdo:name | Permission to use, copy, modify, and/or distribute this software for any |
| securechain_Software → string | securechain:Software/ | hsdo:name |  |


## Comments

* 53378 occurrences with subject type securechain_Hardware and object type string.
* 22002 occurrences with subject type hsdo_Organization and object type string.
* 20 occurrences with subject type hsdo_CreativeWork and object type string.
* 34466 occurrences with subject type securechain_Software and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:name |
| native | secure-chain-kg/:hsdo_name |




## LinkML Source

<details>
```yaml
name: hsdo_name
description: No slot (predicate) description specified
comments:
- 53378 occurrences with subject type securechain_Hardware and object type string.
- 22002 occurrences with subject type hsdo_Organization and object type string.
- 20 occurrences with subject type hsdo_CreativeWork and object type string.
- 34466 occurrences with subject type securechain_Software and object type string.
examples:
- description: securechain_Hardware → string
  object:
    example_object: '-'
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: securechain:Hardware/-
    example_subject_type: securechain_Hardware
- description: hsdo_Organization → string
  object:
    example_object: '%240.99_kindle_books_project'
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: schema:Organization/%25240.99_kindle_books_project
    example_subject_type: hsdo_Organization
- description: hsdo_CreativeWork → string
  object:
    example_object: Permission to use, copy, modify, and/or distribute this software
      for any
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: securechain:License/0bsd
    example_subject_type: hsdo_CreativeWork
- description: securechain_Software → string
  object:
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