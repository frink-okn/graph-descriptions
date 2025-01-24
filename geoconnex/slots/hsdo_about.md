

# Slot: hsdo_about


_No slot (predicate) description specified_





URI: [hsdo:about](http://schema.org/about)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoWebPage](../classes/HsdoWebPage.md) | A web page |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_WebPage → string | https://geoconnex.us/epa/hmw/010100020101 | hsdo:about | https://geoconnex.us/nhdplusv2/huc12/010100020101 |


## Comments

* 48672 occurrences with subject type hsdo_WebPage and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:about |
| native | geoconnex/:hsdo_about |




## LinkML Source

<details>
```yaml
name: hsdo_about
description: No slot (predicate) description specified
comments:
- 48672 occurrences with subject type hsdo_WebPage and object type string.
examples:
- description: hsdo_WebPage → string
  object:
    example_object: https://geoconnex.us/nhdplusv2/huc12/010100020101
    example_predicate: hsdo:about
    example_subject: https://geoconnex.us/epa/hmw/010100020101
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:about
alias: hsdo_about
domain_of:
- hsdo_WebPage
range: string

```
</details>