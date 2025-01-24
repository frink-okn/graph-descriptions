

# Slot: hsdo_width


_No slot (predicate) description specified_





URI: [hsdo:width](http://schema.org/width)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoImageObject](../classes/HsdoImageObject.md) | An image file |  no  |







## Properties

* Range: [xsd:integer](xsd:integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_ImageObject → integer | https://internetofwater.org/#organizationLogo | hsdo:width | 380 |


## Comments

* 3 occurrences with subject type hsdo_ImageObject and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:width |
| native | geoconnex/:hsdo_width |




## LinkML Source

<details>
```yaml
name: hsdo_width
description: No slot (predicate) description specified
comments:
- 3 occurrences with subject type hsdo_ImageObject and object type integer.
examples:
- description: hsdo_ImageObject → integer
  object:
    example_object: '380'
    example_predicate: hsdo:width
    example_subject: https://internetofwater.org/#organizationLogo
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:width
alias: hsdo_width
domain_of:
- hsdo_ImageObject
range: integer

```
</details>