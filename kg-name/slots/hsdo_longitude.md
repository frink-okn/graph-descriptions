

# Slot: hsdo_longitude


_No slot (predicate) description specified_





URI: [hsdo:longitude](http://schema.org/longitude)



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
| hsdo_Place → decimal | dreamkg:service/location/4542572480692224 | hsdo:longitude | -75.239064 |


## Comments

* 89 occurrences with subject type hsdo_Place and object type decimal.

## Identifier and Mapping Information







### Schema Source


* from schema: kg-name




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:longitude |
| native | kg-name/:hsdo_longitude |




## LinkML Source

<details>
```yaml
name: hsdo_longitude
description: No slot (predicate) description specified
comments:
- 89 occurrences with subject type hsdo_Place and object type decimal.
examples:
- description: hsdo_Place → decimal
  object:
    example_object: '-75.239064'
    example_object_type: decimal
    example_predicate: hsdo:longitude
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
from_schema: kg-name
rank: 1000
slot_uri: hsdo:longitude
alias: hsdo_longitude
domain_of:
- hsdo_Place
range: decimal

```
</details>