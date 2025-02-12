

# Slot: opens (hsdo_opens)


_The opening hour of the place or service on the given day(s) of the week._






This slot occurs 631 times.


URI: [hsdo:opens](http://schema.org/opens)



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
| hsdo_OpeningHoursSpecification | string | dreamkg:service/hours/friday/4689179354857472 | 08:00 | 631 |




## LinkML Source

<details>

```yaml
name: hsdo_opens
annotations:
  count:
    tag: count
    value: 631
description: The opening hour of the place or service on the given day(s) of the week.
title: opens
examples:
- description: hsdo_OpeningHoursSpecification→string
  object:
    example_object: 08:00
    example_object_type: string
    example_predicate: hsdo:opens
    example_subject: dreamkg:service/hours/friday/4689179354857472
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