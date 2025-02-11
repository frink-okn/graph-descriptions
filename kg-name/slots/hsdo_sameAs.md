

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
| hsdo_Organization → uri | dreamkg:service/provider/4542572480692224 | hsdo:sameAs | https://www.facebook.com/ChildGuidanceResourceCenters |


## Comments

* 127 occurrences with subject type hsdo_Organization and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: kg-name




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:sameAs |
| native | kg-name/:hsdo_sameAs |




## LinkML Source

<details>
```yaml
name: hsdo_sameAs
description: No slot (predicate) description specified
comments:
- 127 occurrences with subject type hsdo_Organization and object type uri.
examples:
- description: hsdo_Organization → uri
  object:
    example_object: https://www.facebook.com/ChildGuidanceResourceCenters
    example_object_type: uri
    example_predicate: hsdo:sameAs
    example_subject: dreamkg:service/provider/4542572480692224
    example_subject_type: hsdo_Organization
from_schema: kg-name
rank: 1000
slot_uri: hsdo:sameAs
alias: hsdo_sameAs
domain_of:
- hsdo_Organization
range: uri

```
</details>