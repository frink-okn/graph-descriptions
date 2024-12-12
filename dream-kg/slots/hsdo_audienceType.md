

# Slot: hsdo_audienceType


_No slot (predicate) description specified_





URI: [hsdo:audienceType](hsdo:audienceType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoAudience](../classes/HsdoAudience.md) | Intended audience for an item, i |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Audience → string | dreamkg:category/audience/HumanTraffickingSurvivors | hsdo:audienceType | human trafficking survivors |


## Comments

* 81 occurrences with subject type hsdo_Audience and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:audienceType |
| native | dream-kg/:hsdo_audienceType |




## LinkML Source

<details>
```yaml
name: hsdo_audienceType
description: No slot (predicate) description specified
comments:
- 81 occurrences with subject type hsdo_Audience and object type string.
examples:
- description: hsdo_Audience → string
  object:
    example_object: human trafficking survivors
    example_predicate: hsdo:audienceType
    example_subject: dreamkg:category/audience/HumanTraffickingSurvivors
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:audienceType
alias: hsdo_audienceType
domain_of:
- hsdo_Audience
range: string

```
</details>