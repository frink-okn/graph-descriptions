

# Slot: hsdo_provider


_No slot (predicate) description specified_





URI: [hsdo:provider](http://schema.org/provider)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [HsdoOrganization](../classes/HsdoOrganization.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Service → hsdo_Organization | dreamkg:service/4689179354857472 | hsdo:provider | dreamkg:service/provider/4689179354857472 |


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
    example_object: dreamkg:service/provider/4689179354857472
    example_predicate: hsdo:provider
    example_subject: dreamkg:service/4689179354857472
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:provider
alias: hsdo_provider
domain_of:
- hsdo_Service
range: hsdo_Organization

```
</details>