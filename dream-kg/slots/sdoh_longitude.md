

# Slot: longitude (sdoh_longitude)


_The longitude of a location. For example ```-122.08585``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System))._





URI: [sdoh:longitude](http://schema.org/longitude)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohPlace](../classes/SdohPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal)






## Examples

| Value |
| --- |
| dreamkg:service/location/5552002522939392 sdoh:longitude -75.1637779 |

## Comments

* 89 occurrences with subject type sdoh_Place and object type decimal.

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
| self | sdoh:longitude |
| native | dream-kg/:sdoh_longitude |




## LinkML Source

<details>
```yaml
name: sdoh_longitude
description: The longitude of a location. For example ```-122.08585``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System)).
title: longitude
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 89 occurrences with subject type sdoh_Place and object type decimal.
examples:
- value: dreamkg:service/location/5552002522939392 sdoh:longitude -75.1637779
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:longitude
alias: sdoh_longitude
domain_of:
- sdoh_Place
range: decimal

```
</details>