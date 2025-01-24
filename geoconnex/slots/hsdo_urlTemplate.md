

# Slot: hsdo_urlTemplate


_No slot (predicate) description specified_





URI: [hsdo:urlTemplate](http://schema.org/urlTemplate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoEntryPoint](../classes/HsdoEntryPoint.md) | An entry point, within some Web-based protocol |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_EntryPoint → string | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pk0 | hsdo:urlTemplate | https://internetofwater.org/?s={search_term_string} |


## Comments

* 1 occurrences with subject type hsdo_EntryPoint and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:urlTemplate |
| native | geoconnex/:hsdo_urlTemplate |




## LinkML Source

<details>
```yaml
name: hsdo_urlTemplate
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type hsdo_EntryPoint and object type string.
examples:
- description: hsdo_EntryPoint → string
  object:
    example_object: https://internetofwater.org/?s={search_term_string}
    example_predicate: hsdo:urlTemplate
    example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pk0
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:urlTemplate
alias: hsdo_urlTemplate
domain_of:
- hsdo_EntryPoint
range: string

```
</details>