

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
| hsdo_Service → string | dreamkg:service/4909220273061888 | hsdo:name | Youth Services |
| hsdo_Organization → string | dreamkg:service/provider/4692155605712896 | hsdo:name | Gaudenzia |


## Comments

* 88 occurrences with subject type hsdo_Service and object type string.
* 89 occurrences with subject type hsdo_Organization and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:name |
| native | dream-kg/:hsdo_name |




## LinkML Source

<details>
```yaml
name: hsdo_name
description: No slot (predicate) description specified
comments:
- 88 occurrences with subject type hsdo_Service and object type string.
- 89 occurrences with subject type hsdo_Organization and object type string.
examples:
- description: hsdo_Service → string
  object:
    example_object: Youth Services
    example_predicate: hsdo:name
    example_subject: dreamkg:service/4909220273061888
- description: hsdo_Organization → string
  object:
    example_object: Gaudenzia
    example_predicate: hsdo:name
    example_subject: dreamkg:service/provider/4692155605712896
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:name
alias: hsdo_name
domain_of:
- hsdo_Organization
- hsdo_Service
range: string

```
</details>