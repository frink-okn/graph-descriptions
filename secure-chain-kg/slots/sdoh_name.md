

# Slot: sdoh_name


_TODO -- tell the world what this slot (predicate) describes._





URI: [sdoh:name](http://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohOrganization](../classes/SdohOrganization.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SdohCreativeWork](../classes/SdohCreativeWork.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SecurechainHardware](../classes/SecurechainHardware.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| securechain:Hardware/field_programmable_gate_array_programmable_acceleration_card_n3000 sdoh:name field_programmable_gate_array_programmable_acceleration_card_n3000 |
| schema:Organization/social_microblogging_pro_project sdoh:name social_microblogging_pro_project |
| securechain:Software/libcupscgi1 sdoh:name libcupscgi1 |
| securechain:License/unlicense sdoh:name This is free and unencumbered software released into the public domain. |

## Comments

* 53378 occurrences with subject type securechain_Hardware and object type string.
* 22002 occurrences with subject type sdoh_Organization and object type string.
* 34469 occurrences with subject type securechain_Software and object type string.
* 20 occurrences with subject type sdoh_CreativeWork and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg/develop




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:name |
| native | secure-chain-kg/develop/:sdoh_name |




## LinkML Source

<details>
```yaml
name: sdoh_name
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 53378 occurrences with subject type securechain_Hardware and object type string.
- 22002 occurrences with subject type sdoh_Organization and object type string.
- 34469 occurrences with subject type securechain_Software and object type string.
- 20 occurrences with subject type sdoh_CreativeWork and object type string.
examples:
- value: securechain:Hardware/field_programmable_gate_array_programmable_acceleration_card_n3000
    sdoh:name field_programmable_gate_array_programmable_acceleration_card_n3000
- value: schema:Organization/social_microblogging_pro_project sdoh:name social_microblogging_pro_project
- value: securechain:Software/libcupscgi1 sdoh:name libcupscgi1
- value: securechain:License/unlicense sdoh:name This is free and unencumbered software
    released into the public domain.
from_schema: secure-chain-kg/develop
rank: 1000
slot_uri: sdoh:name
alias: sdoh_name
domain_of:
- securechain_Hardware
- securechain_Software
- sdoh_CreativeWork
- sdoh_Organization
range: string

```
</details>