

# Slot: hsdo_closes


_No slot (predicate) description specified_





URI: [hsdo:closes](hsdo:closes)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place o... |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_OpeningHoursSpecification → string | dreamkg:service/hours/friday/4542572480692224 | hsdo:closes | 17:00 |


## Comments

* 623 occurrences with subject type hsdo_OpeningHoursSpecification and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:closes |
| native | dream-kg/:hsdo_closes |




## LinkML Source

<details>
```yaml
name: hsdo_closes
description: No slot (predicate) description specified
comments:
- 623 occurrences with subject type hsdo_OpeningHoursSpecification and object type
  string.
examples:
- description: hsdo_OpeningHoursSpecification → string
  object:
    example_object: '17:00'
    example_predicate: hsdo:closes
    example_subject: dreamkg:service/hours/friday/4542572480692224
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:closes
alias: hsdo_closes
domain_of:
- hsdo_OpeningHoursSpecification
range: string

```
</details>