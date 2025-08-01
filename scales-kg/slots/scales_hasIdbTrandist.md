

# Slot: scales_hasIdbTrandist


_No slot (predicate) description specified_






This slot occurs 121785 times.


URI: [scales:hasIdbTrandist](http://schemas.scales-okn.org/rdf/scales#hasIdbTrandist)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CriminalCase | string | scales:/CriminalCase/akd;;1:16-cr-00001 | -8 | 19075 |
| scales_CriminalCase | integer | scales:/CriminalCase/almd;;1:16-cr-00441 | -8 | 102710 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbTrandist
annotations:
  count:
    tag: count
    value: 121785
description: No slot (predicate) description specified
examples:
- object:
    example_object: '-8'
    example_object_type: string
    example_predicate: scales:hasIdbTrandist
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
- object:
    example_object: '-8'
    example_object_type: integer
    example_predicate: scales:hasIdbTrandist
    example_subject: scales:/CriminalCase/almd;;1:16-cr-00441
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTrandist
alias: scales_hasIdbTrandist
domain_of:
- scales_CriminalCase
range: Any
any_of:
- range: string
- range: integer

```
</details>