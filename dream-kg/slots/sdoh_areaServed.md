

# Slot: sdoh_areaServed


_TODO -- tell the world what this slot (predicate) describes._





URI: [sdoh:areaServed](http://schema.org/areaServed)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohService](../classes/SdohService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:service/4670495380209664 sdoh:areaServed This program covers residents of the following counties: Philadelphia County, PA. |

## Comments

* 87 occurrences with subject type sdoh_Service and object type string.

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
| self | sdoh:areaServed |
| native | dream-kg/:sdoh_areaServed |




## LinkML Source

<details>
```yaml
name: sdoh_areaServed
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 87 occurrences with subject type sdoh_Service and object type string.
examples:
- value: 'dreamkg:service/4670495380209664 sdoh:areaServed This program covers residents
    of the following counties: Philadelphia County, PA.'
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:areaServed
alias: sdoh_areaServed
domain_of:
- sdoh_Service
range: string

```
</details>