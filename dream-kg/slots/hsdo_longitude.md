

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
| hsdo_Place → decimal | dreamkg:service/location/5186727883833344 | hsdo:longitude | -75.1647762 |


## Comments

* 89 occurrences with subject type hsdo_Place and object type decimal.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:longitude |
| native | dream-kg/:hsdo_longitude |




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
    example_object: '-75.1647762'
    example_predicate: hsdo:longitude
    example_subject: dreamkg:service/location/5186727883833344
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:longitude
alias: hsdo_longitude
domain_of:
- hsdo_Place
range: decimal

```
</details>