

# Slot: sdoh_identifier


_TODO -- tell the world what this slot (predicate) describes._





URI: [sdoh:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohAdministrativeArea](../classes/SdohAdministrativeArea.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SdohService](../classes/SdohService.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:service/6139716755783680 sdoh:identifier 6139716755783680 |
| dreamkg:zip/19154 sdoh:identifier 19154 |

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
- value: dreamkg:service/6139716755783680 sdoh:identifier 6139716755783680
- value: dreamkg:zip/19154 sdoh:identifier 19154
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