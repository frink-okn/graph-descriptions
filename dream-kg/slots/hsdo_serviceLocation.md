

# Slot: serviceLocation (hsdo_serviceLocation)


_The location (e.g. civic structure, local business, etc.) where a person can go to access the service._






This slot occurs 87 times.


URI: [hsdo:serviceLocation](http://schema.org/serviceLocation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | A means for accessing a service, e |  yes  |







## Properties

* Range: [HsdoPlace](../classes/HsdoPlace.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_ServiceChannel | hsdo_Place | dreamkg:service/channel/P-6354456388829184 | dreamkg:service/location/6354456388829184 | 87 |




## LinkML Source

<details>

```yaml
name: hsdo_serviceLocation
annotations:
  count:
    tag: count
    value: 87
description: The location (e.g. civic structure, local business, etc.) where a person
  can go to access the service.
title: serviceLocation
examples:
- description: hsdo_ServiceChannel→hsdo_Place
  object:
    example_object: dreamkg:service/location/6354456388829184
    example_object_type: hsdo_Place
    example_predicate: hsdo:serviceLocation
    example_subject: dreamkg:service/channel/P-6354456388829184
    example_subject_type: hsdo_ServiceChannel
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:serviceLocation
alias: hsdo_serviceLocation
domain_of:
- hsdo_ServiceChannel
range: hsdo_Place

```
</details>