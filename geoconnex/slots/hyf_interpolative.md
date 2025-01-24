

# Slot: hyf_interpolative


_No slot (predicate) description specified_





URI: [hyf:interpolative](https://www.opengis.net/def/schema/hy_features/hyfinterpolative)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](xsd:integer)&nbsp;or&nbsp;<br />[xsd:double](xsd:double)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None → integer | _:b1064778 | hyf:interpolative | 0 |
| None → double | _:b1064780 | hyf:interpolative | 3.6898 |


## Comments

* 2 occurrences with untyped subjects and object type integer.
* 4 occurrences with untyped subjects and object type double.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hyf:interpolative |
| native | geoconnex/:hyf_interpolative |




## LinkML Source

<details>
```yaml
name: hyf_interpolative
description: No slot (predicate) description specified
comments:
- 2 occurrences with untyped subjects and object type integer.
- 4 occurrences with untyped subjects and object type double.
examples:
- description: None → integer
  object:
    example_object: '0'
    example_predicate: hyf:interpolative
    example_subject: _:b1064778
- description: None → double
  object:
    example_object: '3.6898'
    example_predicate: hyf:interpolative
    example_subject: _:b1064780
from_schema: geoconnex
rank: 1000
slot_uri: hyf:interpolative
alias: hyf_interpolative
range: Any
any_of:
- range: integer
- range: double

```
</details>