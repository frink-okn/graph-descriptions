

# Slot: hsdo_caption


_No slot (predicate) description specified_





URI: [hsdo:caption](http://schema.org/caption)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoImageObject](../classes/HsdoImageObject.md) | An image file |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_ImageObject → string | https://internetofwater.org/#organizationLogo | hsdo:caption | Internet of Water Logo |


## Comments

* 3 occurrences with subject type hsdo_ImageObject and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:caption |
| native | geoconnex/:hsdo_caption |




## LinkML Source

<details>
```yaml
name: hsdo_caption
description: No slot (predicate) description specified
comments:
- 3 occurrences with subject type hsdo_ImageObject and object type string.
examples:
- description: hsdo_ImageObject → string
  object:
    example_object: Internet of Water Logo
    example_predicate: hsdo:caption
    example_subject: https://internetofwater.org/#organizationLogo
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:caption
alias: hsdo_caption
domain_of:
- hsdo_ImageObject
range: string

```
</details>