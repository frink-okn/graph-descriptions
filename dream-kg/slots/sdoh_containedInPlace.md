

# Slot: containedInPlace (sdoh_containedInPlace)


_The basic containment relation between a place and one that contains it._





URI: [sdoh:containedInPlace](http://schema.org/containedInPlace)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohPlace](../classes/SdohPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [SdohAdministrativeArea](../classes/SdohAdministrativeArea.md)






## Examples

| Value |
| --- |
| dreamkg:service/location/5922109384294400 sdoh:containedInPlace dreamkg:zip/19103 |

## Comments

* 88 occurrences with subject type sdoh_Place and object type sdoh_AdministrativeArea.

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
| self | sdoh:containedInPlace |
| native | dream-kg/:sdoh_containedInPlace |




## LinkML Source

<details>
```yaml
name: sdoh_containedInPlace
description: The basic containment relation between a place and one that contains
  it.
title: containedInPlace
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 88 occurrences with subject type sdoh_Place and object type sdoh_AdministrativeArea.
examples:
- value: dreamkg:service/location/5922109384294400 sdoh:containedInPlace dreamkg:zip/19103
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:containedInPlace
alias: sdoh_containedInPlace
domain_of:
- sdoh_Place
range: sdoh_AdministrativeArea

```
</details>