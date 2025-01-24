

# Slot: badwdt_P2043


_No slot (predicate) description specified_





URI: [badwdt:P2043](https://www.wikidata.org/wiki/Property:P2043)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](xsd:integer)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)&nbsp;or&nbsp;<br />[xsd:double](xsd:double)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → string | https://geoconnex.us/ref/mainstems/1 | badwdt:P2043 | 877.7 |
| schema_Place → integer | https://geoconnex.us/ref/mainstems/1 | badwdt:P2043 | 878 |
| schema_Place → double | https://geoconnex.us/ref/mainstems/10035 | badwdt:P2043 | 19.3 |


## Comments

* 34082 occurrences with subject type schema_Place and object type string.
* 3458 occurrences with subject type schema_Place and object type integer.
* 30393 occurrences with subject type schema_Place and object type double.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | badwdt:P2043 |
| native | geoconnex/:badwdt_P2043 |




## LinkML Source

<details>
```yaml
name: badwdt_P2043
description: No slot (predicate) description specified
comments:
- 34082 occurrences with subject type schema_Place and object type string.
- 3458 occurrences with subject type schema_Place and object type integer.
- 30393 occurrences with subject type schema_Place and object type double.
examples:
- description: schema_Place → string
  object:
    example_object: '877.7'
    example_predicate: badwdt:P2043
    example_subject: https://geoconnex.us/ref/mainstems/1
- description: schema_Place → integer
  object:
    example_object: '878'
    example_predicate: badwdt:P2043
    example_subject: https://geoconnex.us/ref/mainstems/1
- description: schema_Place → double
  object:
    example_object: '19.3'
    example_predicate: badwdt:P2043
    example_subject: https://geoconnex.us/ref/mainstems/10035
from_schema: geoconnex
rank: 1000
slot_uri: badwdt:P2043
alias: badwdt_P2043
domain_of:
- schema_Place
range: Any
any_of:
- range: integer
- range: string
- range: double

```
</details>