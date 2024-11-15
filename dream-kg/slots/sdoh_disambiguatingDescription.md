

# Slot: disambiguatingDescription (sdoh_disambiguatingDescription)


_A sub property of description. A short description of the item used to disambiguate from other, similar items. Information from other properties (in particular, name) may be necessary for the description to be useful for disambiguation._





URI: [sdoh:disambiguatingDescription](http://schema.org/disambiguatingDescription)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohServiceChannel](../classes/SdohServiceChannel.md) | A means for accessing a service, e |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:service/channel/P-5552002522939392 sdoh:disambiguatingDescription Provider |

## Comments

* 174 occurrences with subject type sdoh_ServiceChannel and object type string.

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
| self | sdoh:disambiguatingDescription |
| native | dream-kg/:sdoh_disambiguatingDescription |




## LinkML Source

<details>
```yaml
name: sdoh_disambiguatingDescription
description: A sub property of description. A short description of the item used to
  disambiguate from other, similar items. Information from other properties (in particular,
  name) may be necessary for the description to be useful for disambiguation.
title: disambiguatingDescription
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 174 occurrences with subject type sdoh_ServiceChannel and object type string.
examples:
- value: dreamkg:service/channel/P-5552002522939392 sdoh:disambiguatingDescription
    Provider
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:disambiguatingDescription
alias: sdoh_disambiguatingDescription
domain_of:
- sdoh_ServiceChannel
range: string

```
</details>