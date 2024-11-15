

# Slot: availableChannel (sdoh_availableChannel)


_A means of accessing the service (e.g. a phone bank, a web site, a location, etc.)._





URI: [sdoh:availableChannel](http://schema.org/availableChannel)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohService](../classes/SdohService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [SdohServiceChannel](../classes/SdohServiceChannel.md)






## Examples

| Value |
| --- |
| dreamkg:service/5671175268335616 sdoh:availableChannel dreamkg:service/channel/AB-5671175268335616 |

## Comments

* 174 occurrences with subject type sdoh_Service and object type sdoh_ServiceChannel.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:availableChannel |
| native | dream-kg/:sdoh_availableChannel |




## LinkML Source

<details>
```yaml
name: sdoh_availableChannel
description: A means of accessing the service (e.g. a phone bank, a web site, a location,
  etc.).
title: availableChannel
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 174 occurrences with subject type sdoh_Service and object type sdoh_ServiceChannel.
examples:
- value: dreamkg:service/5671175268335616 sdoh:availableChannel dreamkg:service/channel/AB-5671175268335616
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:availableChannel
alias: sdoh_availableChannel
domain_of:
- sdoh_Service
range: sdoh_ServiceChannel

```
</details>