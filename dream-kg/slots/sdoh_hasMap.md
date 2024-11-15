

# Slot: hasMap (sdoh_hasMap)


_A URL to a map of the place._





URI: [sdoh:hasMap](http://schema.org/hasMap)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohPlace](../classes/SdohPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| dreamkg:service/location/6494806799548416 sdoh:hasMap https://www.google.com/maps/?q=900+West+Jefferson+Street,+Philadelphia,+PA+19122/ |

## Comments

* 88 occurrences with subject type sdoh_Place and object type uri.

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
| self | sdoh:hasMap |
| native | dream-kg/:sdoh_hasMap |




## LinkML Source

<details>
```yaml
name: sdoh_hasMap
description: A URL to a map of the place.
title: hasMap
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 88 occurrences with subject type sdoh_Place and object type uri.
examples:
- value: dreamkg:service/location/6494806799548416 sdoh:hasMap https://www.google.com/maps/?q=900+West+Jefferson+Street,+Philadelphia,+PA+19122/
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:hasMap
alias: sdoh_hasMap
domain_of:
- sdoh_Place
range: uri

```
</details>