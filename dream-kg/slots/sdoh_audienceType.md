

# Slot: audienceType (sdoh_audienceType)


_The target group associated with a given audience (e.g. veterans, car owners, musicians, etc.)._





URI: [sdoh:audienceType](http://schema.org/audienceType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohAudience](../classes/SdohAudience.md) | Intended audience for an item, i |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:category/audience/Female sdoh:audienceType female |

## Comments

* 81 occurrences with subject type sdoh_Audience and object type string.

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
| self | sdoh:audienceType |
| native | dream-kg/:sdoh_audienceType |




## LinkML Source

<details>
```yaml
name: sdoh_audienceType
description: The target group associated with a given audience (e.g. veterans, car
  owners, musicians, etc.).
title: audienceType
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 81 occurrences with subject type sdoh_Audience and object type string.
examples:
- value: dreamkg:category/audience/Female sdoh:audienceType female
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:audienceType
alias: sdoh_audienceType
domain_of:
- sdoh_Audience
range: string

```
</details>