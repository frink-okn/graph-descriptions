

# Slot: hsdo_dayOfWeek


_No slot (predicate) description specified_





URI: [hsdo:dayOfWeek](http://schema.org/dayOfWeek)



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
| hsdo_OpeningHoursSpecification → string | dreamkg:service/hours/friday/4542572480692224 | hsdo:dayOfWeek | Friday |


## Comments

* 609 occurrences with subject type hsdo_OpeningHoursSpecification and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:dayOfWeek |
| native | dream-kg/:hsdo_dayOfWeek |




## LinkML Source

<details>
```yaml
name: hsdo_dayOfWeek
description: No slot (predicate) description specified
comments:
- 609 occurrences with subject type hsdo_OpeningHoursSpecification and object type
  string.
examples:
- description: hsdo_OpeningHoursSpecification → string
  object:
    example_object: Friday
    example_object_type: string
    example_predicate: hsdo:dayOfWeek
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: hsdo_OpeningHoursSpecification
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:dayOfWeek
alias: hsdo_dayOfWeek
domain_of:
- hsdo_OpeningHoursSpecification
range: string

```
</details>