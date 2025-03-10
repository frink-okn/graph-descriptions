

# Slot: hsdo_serviceLocation


_The location (e.g. civic structure, local business, etc.) where a person can go to access the service._






This slot occurs 87 times.


URI: [schema:serviceLocation](http://schema.org/serviceLocation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | A means for accessing a service, e |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)&nbsp;or&nbsp;<br />[HsdoPlace](../classes/HsdoPlace.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_ServiceChannel | hsdo_Place | dreamkg:service/channel/P-4542572480692224 | dreamkg:service/location/4542572480692224 | 87 |
| hsdo_ServiceChannel | prov_Entity | dreamkg:service/channel/P-4542572480692224 | dreamkg:service/location/4542572480692224 | 87 |




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
examples:
- object:
    example_object: dreamkg:service/location/4542572480692224
    example_object_type: hsdo_Place
    example_predicate: schema:serviceLocation
    example_subject: dreamkg:service/channel/P-4542572480692224
    example_subject_type: hsdo_ServiceChannel
- object:
    example_object: dreamkg:service/location/4542572480692224
    example_object_type: prov_Entity
    example_predicate: schema:serviceLocation
    example_subject: dreamkg:service/channel/P-4542572480692224
    example_subject_type: hsdo_ServiceChannel
from_schema: dream-kg
rank: 1000
slot_uri: schema:serviceLocation
alias: hsdo_serviceLocation
domain_of:
- hsdo_ServiceChannel
range: Any
any_of:
- range: prov_Entity
- range: hsdo_Place

```
</details>