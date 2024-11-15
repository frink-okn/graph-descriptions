

# Slot: name (sdoh_name)


_The name of the item._





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
| dreamkg:service/provider/4967372504694784 sdoh:name Church World Service Inc |
| dreamkg:service/4873770804707328 sdoh:name Food Assistance and Relief |

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
description: The name of the item.
title: name
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 89 occurrences with subject type sdoh_Organization and object type string.
- 88 occurrences with subject type sdoh_Service and object type string.
examples:
- value: dreamkg:service/provider/4967372504694784 sdoh:name Church World Service
    Inc
- value: dreamkg:service/4873770804707328 sdoh:name Food Assistance and Relief
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