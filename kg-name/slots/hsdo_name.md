

# Slot: hsdo_name


_No slot (predicate) description specified_





URI: [hsdo:name](http://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Organization → string | dreamkg:service/provider/4542572480692224 | hsdo:name | Child Guidance Resource Centers |
| hsdo_Service → string | dreamkg:service/4542572480692224 | hsdo:name | Drug and Alcohol Services |


## Comments

* 89 occurrences with subject type hsdo_Organization and object type string.
* 88 occurrences with subject type hsdo_Service and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: kg-name




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:name |
| native | kg-name/:hsdo_name |




## LinkML Source

<details>
```yaml
name: hsdo_name
description: No slot (predicate) description specified
comments:
- 89 occurrences with subject type hsdo_Organization and object type string.
- 88 occurrences with subject type hsdo_Service and object type string.
examples:
- description: hsdo_Organization → string
  object:
    example_object: Child Guidance Resource Centers
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: dreamkg:service/provider/4542572480692224
    example_subject_type: hsdo_Organization
- description: hsdo_Service → string
  object:
    example_object: Drug and Alcohol Services
    example_object_type: string
    example_predicate: hsdo:name
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
from_schema: kg-name
rank: 1000
slot_uri: hsdo:name
alias: hsdo_name
domain_of:
- hsdo_Organization
- hsdo_Service
range: string

```
</details>