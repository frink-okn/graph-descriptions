

# Slot: hsdo_address


_No slot (predicate) description specified_





URI: [hsdo:address](http://schema.org/address)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Place → string | dreamkg:service/location/4542572480692224 | hsdo:address | 2901 Island Avenue, Philadelphia, PA 19153 |


## Comments

* 93 occurrences with subject type hsdo_Place and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:address |
| native | dream-kg/:hsdo_address |




## LinkML Source

<details>
```yaml
name: hsdo_address
description: No slot (predicate) description specified
comments:
- 93 occurrences with subject type hsdo_Place and object type string.
examples:
- description: hsdo_Place → string
  object:
    example_object: 2901 Island Avenue, Philadelphia, PA 19153
    example_object_type: string
    example_predicate: hsdo:address
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:address
alias: hsdo_address
domain_of:
- hsdo_Place
range: string

```
</details>