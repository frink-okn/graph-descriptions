

# Slot: hsdo_description


_No slot (predicate) description specified_





URI: [hsdo:description](hsdo:description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [HsdoTextObject](../classes/HsdoTextObject.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Service → hsdo_TextObject | dreamkg:service/5128979153944576 | hsdo:description | dreamkg:service/desc/5128979153944576 |


## Comments

* 87 occurrences with subject type hsdo_Service and object type hsdo_TextObject.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:description |
| native | dream-kg/:hsdo_description |




## LinkML Source

<details>
```yaml
name: hsdo_description
description: No slot (predicate) description specified
comments:
- 87 occurrences with subject type hsdo_Service and object type hsdo_TextObject.
examples:
- description: hsdo_Service → hsdo_TextObject
  object:
    example_object: dreamkg:service/desc/5128979153944576
    example_predicate: hsdo:description
    example_subject: dreamkg:service/5128979153944576
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:description
alias: hsdo_description
domain_of:
- hsdo_Service
range: hsdo_TextObject

```
</details>