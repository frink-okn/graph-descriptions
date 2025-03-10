

# Slot: hsdo_opens


_The opening hour of the place or service on the given day(s) of the week._






This slot occurs 631 times.


URI: [schema:opens](http://schema.org/opens)



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
| prov_Entity | string | dreamkg:service/hours/friday/4542572480692224 | 08:00 | 631 |
| hsdo_OpeningHoursSpecification | string | dreamkg:service/hours/friday/4542572480692224 | 08:00 | 631 |




## LinkML Source

<details>

```yaml
name: hsdo_opens
annotations:
  count:
    tag: count
    value: 631
description: The opening hour of the place or service on the given day(s) of the week.
examples:
- object:
    example_object: 08:00
    example_object_type: string
    example_predicate: schema:opens
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: 08:00
    example_object_type: string
    example_predicate: schema:opens
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: hsdo_OpeningHoursSpecification
from_schema: dream-kg
rank: 1000
slot_uri: schema:opens
alias: hsdo_opens
domain_of:
- hsdo_OpeningHoursSpecification
- prov_Entity
range: string

```
</details>