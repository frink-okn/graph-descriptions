

# Slot: hsdo_hoursAvailable


_No slot (predicate) description specified_





URI: [hsdo:hoursAvailable](http://schema.org/hoursAvailable)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Service → hsdo_OpeningHoursSpecification | dreamkg:service/4666716061171712 | hsdo:hoursAvailable | dreamkg:service/hours/friday/4666716061171712 |


## Comments

* 609 occurrences with subject type hsdo_Service and object type hsdo_OpeningHoursSpecification.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:hoursAvailable |
| native | dream-kg/:hsdo_hoursAvailable |




## LinkML Source

<details>
```yaml
name: hsdo_hoursAvailable
description: No slot (predicate) description specified
comments:
- 609 occurrences with subject type hsdo_Service and object type hsdo_OpeningHoursSpecification.
examples:
- description: hsdo_Service → hsdo_OpeningHoursSpecification
  object:
    example_object: dreamkg:service/hours/friday/4666716061171712
    example_predicate: hsdo:hoursAvailable
    example_subject: dreamkg:service/4666716061171712
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:hoursAvailable
alias: hsdo_hoursAvailable
domain_of:
- hsdo_Service
range: hsdo_OpeningHoursSpecification

```
</details>