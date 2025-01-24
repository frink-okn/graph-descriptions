

# Slot: badwdt_P2053


_No slot (predicate) description specified_





URI: [badwdt:P2053](https://www.wikidata.org/wiki/Property:P2053)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](xsd:integer)&nbsp;or&nbsp;<br />[xsd:double](xsd:double)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → double | https://geoconnex.us/ref/mainstems/1 | badwdt:P2053 | 66999.6 |
| schema_Place → integer | https://geoconnex.us/ref/mainstems/101400 | badwdt:P2053 | 112 |


## Comments

* 30375 occurrences with subject type schema_Place and object type double.
* 3476 occurrences with subject type schema_Place and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | badwdt:P2053 |
| native | geoconnex/:badwdt_P2053 |




## LinkML Source

<details>
```yaml
name: badwdt_P2053
description: No slot (predicate) description specified
comments:
- 30375 occurrences with subject type schema_Place and object type double.
- 3476 occurrences with subject type schema_Place and object type integer.
examples:
- description: schema_Place → double
  object:
    example_object: '66999.6'
    example_predicate: badwdt:P2053
    example_subject: https://geoconnex.us/ref/mainstems/1
- description: schema_Place → integer
  object:
    example_object: '112'
    example_predicate: badwdt:P2053
    example_subject: https://geoconnex.us/ref/mainstems/101400
from_schema: geoconnex
rank: 1000
slot_uri: badwdt:P2053
alias: badwdt_P2053
domain_of:
- schema_Place
range: Any
any_of:
- range: integer
- range: double

```
</details>