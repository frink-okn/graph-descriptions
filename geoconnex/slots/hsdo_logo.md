

# Slot: hsdo_logo


_No slot (predicate) description specified_





URI: [hsdo:logo](http://schema.org/logo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |







## Properties

* Range: [HsdoImageObject](../classes/HsdoImageObject.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Organization → hsdo_ImageObject | https://internetofwater.org/#organization | hsdo:logo | https://internetofwater.org/who-we-are/#organizationLogo |


## Comments

* 5 occurrences with subject type hsdo_Organization and object type hsdo_ImageObject.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:logo |
| native | geoconnex/:hsdo_logo |




## LinkML Source

<details>
```yaml
name: hsdo_logo
description: No slot (predicate) description specified
comments:
- 5 occurrences with subject type hsdo_Organization and object type hsdo_ImageObject.
examples:
- description: hsdo_Organization → hsdo_ImageObject
  object:
    example_object: https://internetofwater.org/who-we-are/#organizationLogo
    example_predicate: hsdo:logo
    example_subject: https://internetofwater.org/#organization
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:logo
alias: hsdo_logo
domain_of:
- hsdo_Organization
range: hsdo_ImageObject

```
</details>