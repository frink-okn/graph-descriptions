

# Slot: dayOfWeek (hsdo_dayOfWeek)


_The day of the week for which these opening hours are valid._






This slot occurs 609 times.


URI: [hsdo:dayOfWeek](http://schema.org/dayOfWeek)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place o... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_OpeningHoursSpecification | string | dreamkg:service/hours/friday/4689179354857472 | Friday | 609 |




## LinkML Source

<details>

```yaml
name: hsdo_dayOfWeek
annotations:
  count:
    tag: count
    value: 609
description: The day of the week for which these opening hours are valid.
title: dayOfWeek
examples:
- description: hsdo_OpeningHoursSpecification→string
  object:
    example_object: Friday
    example_object_type: string
    example_predicate: hsdo:dayOfWeek
    example_subject: dreamkg:service/hours/friday/4689179354857472
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