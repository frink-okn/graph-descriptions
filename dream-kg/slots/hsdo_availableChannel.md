

# Slot: availableChannel (hsdo_availableChannel)


_A means of accessing the service (e.g. a phone bank, a web site, a location, etc.)._






This slot occurs 174 times.


URI: [hsdo:availableChannel](http://schema.org/availableChannel)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |







## Properties

* Range: [HsdoServiceChannel](../classes/HsdoServiceChannel.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Service | hsdo_ServiceChannel | dreamkg:service/6379467169595392 | dreamkg:service/channel/P-6379467169595392 | 174 |




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
title: availableChannel
examples:
- description: hsdo_Service→hsdo_ServiceChannel
  object:
    example_object: dreamkg:service/channel/P-6379467169595392
    example_object_type: hsdo_ServiceChannel
    example_predicate: hsdo:availableChannel
    example_subject: dreamkg:service/6379467169595392
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:availableChannel
alias: hsdo_availableChannel
domain_of:
- hsdo_Service
range: hsdo_ServiceChannel

```
</details>