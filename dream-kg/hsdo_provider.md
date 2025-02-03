

# Slot: hsdo_provider


_No slot (predicate) description specified_





URI: [hsdo:provider](http://schema.org/provider)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](HsdoService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [HsdoOrganization](HsdoOrganization.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Service → hsdo_Organization | dreamkg:service/6710596967858176 | hsdo:provider | dreamkg:service/provider/6710596967858176 |


## Comments

* 87 occurrences with subject type hsdo_Service and object type hsdo_Organization.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:provider |
| native | dream-kg/:hsdo_provider |




## LinkML Source

<details>
```yaml
name: hsdo_provider
description: No slot (predicate) description specified
comments:
- 87 occurrences with subject type hsdo_Service and object type hsdo_Organization.
examples:
- description: hsdo_Service → hsdo_Organization
  object:
    example_object: dreamkg:service/provider/6710596967858176
    example_object_type: hsdo_Organization
    example_predicate: hsdo:provider
    example_subject: dreamkg:service/6710596967858176
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:provider
alias: hsdo_provider
domain_of:
- hsdo_Service
range: hsdo_Organization

```
</details>