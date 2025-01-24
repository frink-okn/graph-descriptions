

# Slot: hyf__containingCatchment


_No slot (predicate) description specified_





URI: [hyf:/containingCatchment](https://www.opengis.net/def/schema/hy_features/hyf/containingCatchment)



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
| schema_Place → schema_Place | https://geoconnex.us/ref/hu10/2203000000 | hyf:/containingCatchment | https://geoconnex.us/ref/hu06/220300 |
| schema_Place → uri | https://geoconnex.us/ref/hu10/2101000601 | hyf:/containingCatchment | https://geoconnex.us/ref/hu08/21010006 |


## Comments

* 83018 occurrences with subject type schema_Place and object type schema_Place.
* 9 occurrences with subject type schema_Place and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hyf:/containingCatchment |
| native | geoconnex/:hyf__containingCatchment |




## LinkML Source

<details>
```yaml
name: hyf__containingCatchment
description: No slot (predicate) description specified
comments:
- 83018 occurrences with subject type schema_Place and object type schema_Place.
- 9 occurrences with subject type schema_Place and object type uri.
examples:
- description: schema_Place → schema_Place
  object:
    example_object: https://geoconnex.us/ref/hu06/220300
    example_predicate: hyf:/containingCatchment
    example_subject: https://geoconnex.us/ref/hu10/2203000000
- description: schema_Place → uri
  object:
    example_object: https://geoconnex.us/ref/hu08/21010006
    example_predicate: hyf:/containingCatchment
    example_subject: https://geoconnex.us/ref/hu10/2101000601
from_schema: geoconnex
rank: 1000
slot_uri: hyf:/containingCatchment
alias: hyf__containingCatchment
domain_of:
- schema_Place
range: Any
any_of:
- range: uri
- range: schema_Place

```
</details>