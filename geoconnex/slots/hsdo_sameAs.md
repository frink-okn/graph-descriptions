

# Slot: hsdo_sameAs


_No slot (predicate) description specified_





URI: [hsdo:sameAs](http://schema.org/sameAs)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Organization → uri | https://internetofwater.org/#organization | hsdo:sameAs | https://twitter.com/internetofh2o |


## Comments

* 3 occurrences with subject type hsdo_Organization and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:sameAs |
| native | geoconnex/:hsdo_sameAs |




## LinkML Source

<details>
```yaml
name: hsdo_sameAs
description: No slot (predicate) description specified
comments:
- 3 occurrences with subject type hsdo_Organization and object type uri.
examples:
- description: hsdo_Organization → uri
  object:
    example_object: https://twitter.com/internetofh2o
    example_predicate: hsdo:sameAs
    example_subject: https://internetofwater.org/#organization
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:sameAs
alias: hsdo_sameAs
domain_of:
- hsdo_Organization
range: uri

```
</details>