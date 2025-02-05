

# Slot: hsdo_latitude


_No slot (predicate) description specified_





URI: [hsdo:latitude](http://schema.org/latitude)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:decimal](xsd:decimal)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Place → decimal | dreamkg:service/location/4542572480692224 | hsdo:latitude | 39.9028317 |


## Comments

* 89 occurrences with subject type hsdo_Place and object type decimal.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:latitude |
| native | dream-kg/:hsdo_latitude |




## LinkML Source

<details>
```yaml
name: hsdo_latitude
description: No slot (predicate) description specified
comments:
- 89 occurrences with subject type hsdo_Place and object type decimal.
examples:
- description: hsdo_Place → decimal
  object:
    example_object: '39.9028317'
    example_object_type: decimal
    example_predicate: hsdo:latitude
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:latitude
alias: hsdo_latitude
domain_of:
- hsdo_Place
range: decimal

```
</details>