

# Slot: hsdo_hoursAvailable


_The hours during which this service or contact is available._






This slot occurs 609 times.


URI: [schema:hoursAvailable](http://schema.org/hoursAvailable)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | prov_Entity | dreamkg:service/4542572480692224 | dreamkg:service/hours/friday/4542572480692224 | 609 |
| prov_Entity | hsdo_OpeningHoursSpecification | dreamkg:service/4542572480692224 | dreamkg:service/hours/friday/4542572480692224 | 609 |
| hsdo_Service | prov_Entity | dreamkg:service/4542572480692224 | dreamkg:service/hours/friday/4542572480692224 | 609 |
| hsdo_Service | hsdo_OpeningHoursSpecification | dreamkg:service/4542572480692224 | dreamkg:service/hours/friday/4542572480692224 | 609 |




## LinkML Source

<details>

```yaml
name: hsdo_hoursAvailable
annotations:
  count:
    tag: count
    value: 609
description: The hours during which this service or contact is available.
examples:
- object:
    example_object: dreamkg:service/hours/friday/4542572480692224
    example_object_type: prov_Entity
    example_predicate: schema:hoursAvailable
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/hours/friday/4542572480692224
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: schema:hoursAvailable
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/hours/friday/4542572480692224
    example_object_type: prov_Entity
    example_predicate: schema:hoursAvailable
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: dreamkg:service/hours/friday/4542572480692224
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: schema:hoursAvailable
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: schema:hoursAvailable
alias: hsdo_hoursAvailable
domain_of:
- hsdo_Service
- prov_Entity
range: Any
any_of:
- range: hsdo_OpeningHoursSpecification
- range: prov_Entity

```
</details>