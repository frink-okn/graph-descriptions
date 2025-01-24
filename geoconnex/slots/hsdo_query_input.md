

# Slot: hsdo_query_input


_No slot (predicate) description specified_





URI: [hsdo:query-input](http://schema.org/query-input)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoSearchAction](../classes/HsdoSearchAction.md) | The act of searching for an object |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_SearchAction → string | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pjg | hsdo:query-input | required name=search_term_string |


## Comments

* 1 occurrences with subject type hsdo_SearchAction and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:query-input |
| native | geoconnex/:hsdo_query_input |




## LinkML Source

<details>
```yaml
name: hsdo_query-input
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type hsdo_SearchAction and object type string.
examples:
- description: hsdo_SearchAction → string
  object:
    example_object: required name=search_term_string
    example_predicate: hsdo:query-input
    example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pjg
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:query-input
alias: hsdo_query_input
domain_of:
- hsdo_SearchAction
range: string

```
</details>