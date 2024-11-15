

# Slot: sdoh_identifier


_TODO -- tell the world what this slot (predicate) describes._





URI: [sdoh:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohService](../classes/SdohService.md) | A service provided by an organization, e |  no  |
| [SdohAdministrativeArea](../classes/SdohAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular gover... |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:service/4955538569953280 sdoh:identifier 4955538569953280 |
| dreamkg:zip/19134 sdoh:identifier 19134 |

## Comments

* 87 occurrences with subject type sdoh_Service and object type string.
* 39 occurrences with subject type sdoh_AdministrativeArea and object type string.

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
| self | sdoh:identifier |
| native | dream-kg/:sdoh_identifier |




## LinkML Source

<details>
```yaml
name: sdoh_identifier
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 87 occurrences with subject type sdoh_Service and object type string.
- 39 occurrences with subject type sdoh_AdministrativeArea and object type string.
examples:
- value: dreamkg:service/4955538569953280 sdoh:identifier 4955538569953280
- value: dreamkg:zip/19134 sdoh:identifier 19134
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:identifier
alias: sdoh_identifier
domain_of:
- sdoh_AdministrativeArea
- sdoh_Service
range: string

```
</details>