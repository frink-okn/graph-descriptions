

# Slot: sdoh_hasMap


_TODO -- tell the world what this slot (predicate) describes._





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
| dreamkg:service/location/6004150434004992 sdoh:hasMap https://www.google.com/maps/?q=715+North+Broad+Street,+Philadelphia,+PA+19123/ |

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
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 88 occurrences with subject type sdoh_Place and object type uri.
examples:
- value: dreamkg:service/location/6004150434004992 sdoh:hasMap https://www.google.com/maps/?q=715+North+Broad+Street,+Philadelphia,+PA+19123/
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:hasMap
alias: sdoh_hasMap
domain_of:
- sdoh_Place
range: uri

```
</details>