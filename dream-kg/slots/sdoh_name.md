

# Slot: sdoh_name


_TODO -- tell the world what this slot (predicate) describes._





URI: [sdoh:name](http://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohService](../classes/SdohService.md) | A service provided by an organization, e |  no  |
| [SdohOrganization](../classes/SdohOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:service/provider/4666716061171712 sdoh:name Horizon House |
| dreamkg:service/6410727744077824 sdoh:name Opioid Treatment Program |

## Comments

* 89 occurrences with subject type sdoh_Organization and object type string.
* 88 occurrences with subject type sdoh_Service and object type string.

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
- 89 occurrences with subject type sdoh_Organization and object type string.
- 88 occurrences with subject type sdoh_Service and object type string.
examples:
- value: dreamkg:service/provider/4666716061171712 sdoh:name Horizon House
- value: dreamkg:service/6410727744077824 sdoh:name Opioid Treatment Program
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