

# Slot: hsdo_servicePhone


_No slot (predicate) description specified_





URI: [hsdo:servicePhone](http://schema.org/servicePhone)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoServiceChannel](HsdoServiceChannel.md) | A means for accessing a service, e |  no  |







## Properties

* Range: [HsdoContactPoint](HsdoContactPoint.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_ServiceChannel → hsdo_ContactPoint | dreamkg:service/channel/P-6710596967858176 | hsdo:servicePhone | dreamkg:service/phone/6710596967858176 |


## Comments

* 87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_ContactPoint.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:servicePhone |
| native | dream-kg/:hsdo_servicePhone |




## LinkML Source

<details>
```yaml
name: hsdo_servicePhone
description: No slot (predicate) description specified
comments:
- 87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_ContactPoint.
examples:
- description: hsdo_ServiceChannel → hsdo_ContactPoint
  object:
    example_object: dreamkg:service/phone/6710596967858176
    example_object_type: hsdo_ContactPoint
    example_predicate: hsdo:servicePhone
    example_subject: dreamkg:service/channel/P-6710596967858176
    example_subject_type: hsdo_ServiceChannel
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:servicePhone
alias: hsdo_servicePhone
domain_of:
- hsdo_ServiceChannel
range: hsdo_ContactPoint

```
</details>