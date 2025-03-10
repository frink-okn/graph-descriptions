

# Slot: hsdo_dayOfWeek


_The day of the week for which these opening hours are valid._






This slot occurs 609 times.


URI: [schema:dayOfWeek](http://schema.org/dayOfWeek)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place o... |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | string | dreamkg:service/hours/friday/4542572480692224 | Friday | 609 |
| hsdo_OpeningHoursSpecification | string | dreamkg:service/hours/friday/4542572480692224 | Friday | 609 |




## LinkML Source

<details>

```yaml
name: hsdo_dayOfWeek
annotations:
  count:
    tag: count
    value: 609
description: The day of the week for which these opening hours are valid.
examples:
- object:
    example_object: Friday
    example_object_type: string
    example_predicate: schema:dayOfWeek
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: Friday
    example_object_type: string
    example_predicate: schema:dayOfWeek
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: hsdo_OpeningHoursSpecification
from_schema: dream-kg
rank: 1000
slot_uri: schema:dayOfWeek
alias: hsdo_dayOfWeek
domain_of:
- hsdo_OpeningHoursSpecification
- prov_Entity
range: string

```
</details>