

# Slot: hoursAvailable (hsdo_hoursAvailable)


_The hours during which this service or contact is available._






This slot occurs 609 times.


URI: [hsdo:hoursAvailable](http://schema.org/hoursAvailable)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |







## Properties

* Range: [HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Service | hsdo_OpeningHoursSpecification | dreamkg:service/6379467169595392 | dreamkg:service/hours/sunday/6379467169595392 | 609 |




## LinkML Source

<details>

```yaml
name: hsdo_hoursAvailable
annotations:
  count:
    tag: count
    value: 609
description: The hours during which this service or contact is available.
title: hoursAvailable
examples:
- description: hsdo_Service→hsdo_OpeningHoursSpecification
  object:
    example_object: dreamkg:service/hours/sunday/6379467169595392
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: hsdo:hoursAvailable
    example_subject: dreamkg:service/6379467169595392
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:hoursAvailable
alias: hsdo_hoursAvailable
domain_of:
- hsdo_Service
range: hsdo_OpeningHoursSpecification

```
</details>