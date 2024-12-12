

# Slot: hsdo_hasMap


_No slot (predicate) description specified_





URI: [hsdo:hasMap](hsdo:hasMap)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Place → uri | dreamkg:service/location/4542572480692224 | hsdo:hasMap | https://www.google.com/maps/?q=2901+Island+Avenue,+Philadelphia,+PA+19153/ |


## Comments

* 88 occurrences with subject type hsdo_Place and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:hasMap |
| native | dream-kg/:hsdo_hasMap |




## LinkML Source

<details>
```yaml
name: hsdo_hasMap
description: No slot (predicate) description specified
comments:
- 88 occurrences with subject type hsdo_Place and object type uri.
examples:
- description: hsdo_Place → uri
  object:
    example_object: https://www.google.com/maps/?q=2901+Island+Avenue,+Philadelphia,+PA+19153/
    example_predicate: hsdo:hasMap
    example_subject: dreamkg:service/location/4542572480692224
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:hasMap
alias: hsdo_hasMap
domain_of:
- hsdo_Place
range: uri

```
</details>