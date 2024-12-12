

# Slot: hsdo_availableChannel


_No slot (predicate) description specified_





URI: [hsdo:availableChannel](hsdo:availableChannel)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [HsdoServiceChannel](../classes/HsdoServiceChannel.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Service → hsdo_ServiceChannel | dreamkg:service/5715375002484736 | hsdo:availableChannel | dreamkg:service/channel/AB-5715375002484736 |


## Comments

* 174 occurrences with subject type hsdo_Service and object type hsdo_ServiceChannel.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:availableChannel |
| native | dream-kg/:hsdo_availableChannel |




## LinkML Source

<details>
```yaml
name: hsdo_availableChannel
description: No slot (predicate) description specified
comments:
- 174 occurrences with subject type hsdo_Service and object type hsdo_ServiceChannel.
examples:
- description: hsdo_Service → hsdo_ServiceChannel
  object:
    example_object: dreamkg:service/channel/AB-5715375002484736
    example_predicate: hsdo:availableChannel
    example_subject: dreamkg:service/5715375002484736
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:availableChannel
alias: hsdo_availableChannel
domain_of:
- hsdo_Service
range: hsdo_ServiceChannel

```
</details>