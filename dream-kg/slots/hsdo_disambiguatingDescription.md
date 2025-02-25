

# Slot: disambiguatingDescription (hsdo_disambiguatingDescription)


_A sub property of description. A short description of the item used to disambiguate from other, similar items. Information from other properties (in particular, name) may be necessary for the description to be useful for disambiguation._






This slot occurs 174 times.


URI: [hsdo:disambiguatingDescription](http://schema.org/disambiguatingDescription)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | A means for accessing a service, e |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_ServiceChannel | string | dreamkg:service/channel/AB-4542572480692224 | Aunt Bertha | 174 |




## LinkML Source

<details>

```yaml
name: hsdo_disambiguatingDescription
annotations:
  count:
    tag: count
    value: 174
description: A sub property of description. A short description of the item used to
  disambiguate from other, similar items. Information from other properties (in particular,
  name) may be necessary for the description to be useful for disambiguation.
title: disambiguatingDescription
examples:
- object:
    example_object: Aunt Bertha
    example_object_type: string
    example_predicate: hsdo:disambiguatingDescription
    example_subject: dreamkg:service/channel/AB-4542572480692224
    example_subject_type: hsdo_ServiceChannel
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:disambiguatingDescription
alias: hsdo_disambiguatingDescription
domain_of:
- hsdo_ServiceChannel
range: string

```
</details>