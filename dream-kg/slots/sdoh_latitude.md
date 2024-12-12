

# Slot: sdoh_latitude


_No slot description provided_





URI: [sdoh:latitude](http://schema.org/latitude)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohPlace](../classes/SdohPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:decimal](xsd:decimal)






## Examples

| Value |
| --- |
| dreamkg:service/location/6004150434004992 sdoh:latitude 39.9676669 |

## Comments

* 89 occurrences with subject type sdoh_Place and object type decimal.

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
| self | sdoh:latitude |
| native | dream-kg/:sdoh_latitude |




## LinkML Source

<details>
```yaml
name: sdoh_latitude
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 89 occurrences with subject type sdoh_Place and object type decimal.
examples:
- value: dreamkg:service/location/6004150434004992 sdoh:latitude 39.9676669
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:latitude
alias: sdoh_latitude
domain_of:
- sdoh_Place
range: decimal

```
</details>