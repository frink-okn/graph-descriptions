

# Slot: hsdo_opens


_No slot (predicate) description specified_





URI: [hsdo:opens](http://schema.org/opens)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOpeningHoursSpecification](HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place o... |  no  |







## Properties

* Range: [String](String.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_OpeningHoursSpecification → string | dreamkg:service/hours/friday/4542572480692224 | hsdo:opens | 08:00 |


## Comments

* 631 occurrences with subject type hsdo_OpeningHoursSpecification and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:opens |
| native | dream-kg/:hsdo_opens |




## LinkML Source

<details>
```yaml
name: hsdo_opens
description: No slot (predicate) description specified
comments:
- 631 occurrences with subject type hsdo_OpeningHoursSpecification and object type
  string.
examples:
- description: hsdo_OpeningHoursSpecification → string
  object:
    example_object: 08:00
    example_object_type: string
    example_predicate: hsdo:opens
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: hsdo_OpeningHoursSpecification
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:opens
alias: hsdo_opens
domain_of:
- hsdo_OpeningHoursSpecification
range: string

```
</details>