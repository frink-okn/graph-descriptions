

# Slot: hsdo_dayOfWeek


_No slot (predicate) description specified_





URI: [hsdo:dayOfWeek](hsdo:dayOfWeek)



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
| hsdo_OpeningHoursSpecification → string | dreamkg:service/hours/wednesday/4964759830003712 | hsdo:dayOfWeek | Wednesday |


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
    example_object: Wednesday
    example_predicate: hsdo:dayOfWeek
    example_subject: dreamkg:service/hours/wednesday/4964759830003712
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:dayOfWeek
alias: hsdo_dayOfWeek
domain_of:
- hsdo_OpeningHoursSpecification
range: string

```
</details>