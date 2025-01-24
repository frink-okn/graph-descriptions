

# Slot: hsdo_height


_No slot (predicate) description specified_





URI: [hsdo:height](http://schema.org/height)



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
| hsdo_ImageObject → integer | https://internetofwater.org/#organizationLogo | hsdo:height | 144 |


## Comments

* 3 occurrences with subject type hsdo_ImageObject and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:height |
| native | geoconnex/:hsdo_height |




## LinkML Source

<details>
```yaml
name: hsdo_height
description: No slot (predicate) description specified
comments:
- 3 occurrences with subject type hsdo_ImageObject and object type integer.
examples:
- description: hsdo_ImageObject → integer
  object:
    example_object: '144'
    example_predicate: hsdo:height
    example_subject: https://internetofwater.org/#organizationLogo
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:height
alias: hsdo_height
domain_of:
- hsdo_ImageObject
range: integer

```
</details>