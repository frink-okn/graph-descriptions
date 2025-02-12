

# Slot: servicePhone (hsdo_servicePhone)


_The phone number to use to access the service._






This slot occurs 87 times.


URI: [hsdo:servicePhone](http://schema.org/servicePhone)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | A means for accessing a service, e |  yes  |







## Properties

* Range: [HsdoContactPoint](../classes/HsdoContactPoint.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_ServiceChannel | hsdo_ContactPoint | dreamkg:service/channel/P-6354456388829184 | dreamkg:service/phone/6354456388829184 | 87 |




## LinkML Source

<details>

```yaml
name: hsdo_servicePhone
annotations:
  count:
    tag: count
    value: 87
description: The phone number to use to access the service.
title: servicePhone
examples:
- description: hsdo_ServiceChannel→hsdo_ContactPoint
  object:
    example_object: dreamkg:service/phone/6354456388829184
    example_object_type: hsdo_ContactPoint
    example_predicate: hsdo:servicePhone
    example_subject: dreamkg:service/channel/P-6354456388829184
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