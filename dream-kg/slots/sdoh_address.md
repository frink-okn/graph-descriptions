

# Slot: sdoh_address


_No slot description provided_





URI: [sdoh:address](http://schema.org/address)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohPlace](../classes/SdohPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Value |
| --- |
| dreamkg:service/location/5477271096786944 sdoh:address 2600 Southampton Rd, Philadelphia, PA 19116 |

## Comments

* 93 occurrences with subject type sdoh_Place and object type string.

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
| self | sdoh:address |
| native | dream-kg/:sdoh_address |




## LinkML Source

<details>
```yaml
name: sdoh_address
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 93 occurrences with subject type sdoh_Place and object type string.
examples:
- value: dreamkg:service/location/5477271096786944 sdoh:address 2600 Southampton Rd,
    Philadelphia, PA 19116
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:address
alias: sdoh_address
domain_of:
- sdoh_Place
range: string

```
</details>