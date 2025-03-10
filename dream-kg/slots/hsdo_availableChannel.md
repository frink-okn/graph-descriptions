

# Slot: hsdo_availableChannel


_A means of accessing the service (e.g. a phone bank, a web site, a location, etc.)._






This slot occurs 174 times.


URI: [schema:availableChannel](http://schema.org/availableChannel)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HsdoServiceChannel](../classes/HsdoServiceChannel.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | hsdo_ServiceChannel | dreamkg:service/4542572480692224 | dreamkg:service/channel/AB-4542572480692224 | 174 |
| hsdo_Service | hsdo_ServiceChannel | dreamkg:service/4542572480692224 | dreamkg:service/channel/AB-4542572480692224 | 174 |




## LinkML Source

<details>

```yaml
name: hsdo_availableChannel
annotations:
  count:
    tag: count
    value: 174
description: A means of accessing the service (e.g. a phone bank, a web site, a location,
  etc.).
examples:
- object:
    example_object: dreamkg:service/channel/AB-4542572480692224
    example_object_type: hsdo_ServiceChannel
    example_predicate: schema:availableChannel
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/channel/AB-4542572480692224
    example_object_type: hsdo_ServiceChannel
    example_predicate: schema:availableChannel
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: schema:availableChannel
alias: hsdo_availableChannel
domain_of:
- hsdo_Service
- prov_Entity
range: hsdo_ServiceChannel

```
</details>