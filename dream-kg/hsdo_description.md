

# Slot: hsdo_description


_No slot (predicate) description specified_





URI: [hsdo:description](http://schema.org/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](HsdoService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [HsdoTextObject](HsdoTextObject.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Service → hsdo_TextObject | dreamkg:service/6710596967858176 | hsdo:description | dreamkg:service/desc/6710596967858176 |


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
    example_object: dreamkg:service/desc/6710596967858176
    example_object_type: hsdo_TextObject
    example_predicate: hsdo:description
    example_subject: dreamkg:service/6710596967858176
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:description
alias: hsdo_description
domain_of:
- hsdo_Service
range: hsdo_TextObject

```
</details>