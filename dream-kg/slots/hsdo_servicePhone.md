

# Slot: hsdo_servicePhone


_The phone number to use to access the service._






This slot occurs 87 times.


URI: [schema:servicePhone](http://schema.org/servicePhone)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | A means for accessing a service, e |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoContactPoint](../classes/HsdoContactPoint.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_ServiceChannel | prov_Entity | dreamkg:service/channel/P-4542572480692224 | dreamkg:service/phone/4542572480692224 | 87 |
| hsdo_ServiceChannel | hsdo_ContactPoint | dreamkg:service/channel/P-4542572480692224 | dreamkg:service/phone/4542572480692224 | 87 |




## LinkML Source

<details>

```yaml
name: hsdo_servicePhone
annotations:
  count:
    tag: count
    value: 87
description: The phone number to use to access the service.
examples:
- object:
    example_object: dreamkg:service/phone/4542572480692224
    example_object_type: prov_Entity
    example_predicate: schema:servicePhone
    example_subject: dreamkg:service/channel/P-4542572480692224
    example_subject_type: hsdo_ServiceChannel
- object:
    example_object: dreamkg:service/phone/4542572480692224
    example_object_type: hsdo_ContactPoint
    example_predicate: schema:servicePhone
    example_subject: dreamkg:service/channel/P-4542572480692224
    example_subject_type: hsdo_ServiceChannel
from_schema: dream-kg
rank: 1000
slot_uri: schema:servicePhone
alias: hsdo_servicePhone
domain_of:
- hsdo_ServiceChannel
range: Any
any_of:
- range: hsdo_ContactPoint
- range: prov_Entity

```
</details>