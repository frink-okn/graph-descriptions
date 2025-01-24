

# Slot: schema_supersededBy


_No slot (predicate) description specified_





URI: [schema:supersededBy](https://schema.org/supersededBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[SchemaPlace](../classes/SchemaPlace.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → schema_Place | https://geoconnex.us/ref/mainstems/8769 | schema:supersededBy | https://geoconnex.us/ref/mainstems/147890 |
| schema_Place → uri | https://geoconnex.us/ref/mainstems/1439819 | schema:supersededBy | https://geoconnex.us/ref/mainstems/2547826 |


## Comments

* 214 occurrences with subject type schema_Place and object type schema_Place.
* 18 occurrences with subject type schema_Place and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:supersededBy |
| native | geoconnex/:schema_supersededBy |




## LinkML Source

<details>
```yaml
name: schema_supersededBy
description: No slot (predicate) description specified
comments:
- 214 occurrences with subject type schema_Place and object type schema_Place.
- 18 occurrences with subject type schema_Place and object type uri.
examples:
- description: schema_Place → schema_Place
  object:
    example_object: https://geoconnex.us/ref/mainstems/147890
    example_predicate: schema:supersededBy
    example_subject: https://geoconnex.us/ref/mainstems/8769
- description: schema_Place → uri
  object:
    example_object: https://geoconnex.us/ref/mainstems/2547826
    example_predicate: schema:supersededBy
    example_subject: https://geoconnex.us/ref/mainstems/1439819
from_schema: geoconnex
rank: 1000
slot_uri: schema:supersededBy
alias: schema_supersededBy
domain_of:
- schema_Place
range: Any
any_of:
- range: uri
- range: schema_Place

```
</details>