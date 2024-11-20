

# Slot: sdoh_name


_TODO -- tell the world what this slot (predicate) describes._





URI: [sdoh:name](http://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohOrganization](../classes/SdohOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [SdohService](../classes/SdohService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:service/5175494499368960 sdoh:name Food Baskets |
| dreamkg:service/provider/5680777996009472 sdoh:name Youth Service Inc |

## Comments

* 88 occurrences with subject type sdoh_Service and object type string.
* 89 occurrences with subject type sdoh_Organization and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:name |
| native | dream-kg/:sdoh_name |




## LinkML Source

<details>
```yaml
name: sdoh_name
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 88 occurrences with subject type sdoh_Service and object type string.
- 89 occurrences with subject type sdoh_Organization and object type string.
examples:
- value: dreamkg:service/5175494499368960 sdoh:name Food Baskets
- value: dreamkg:service/provider/5680777996009472 sdoh:name Youth Service Inc
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:name
alias: sdoh_name
domain_of:
- sdoh_Organization
- sdoh_Service
range: string

```
</details>