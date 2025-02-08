

# Slot: scales_hasJudgeReference


_No slot (predicate) description specified_





URI: [scales:hasJudgeReference](http://schemas.scales-okn.org/rdf/scales#hasJudgeReference)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Jxdm72Judge](../classes/Jxdm72Judge.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None → jxdm72_Judge | scales/DocketEntry/wyd;;6:17-cr-00033_de6 | scales:hasJudgeReference | scales/JudgeEntity/SJ001755 |
| None → uri | scales/DocketEntry/almd;;1:16-cr-00434_de4 | scales:hasJudgeReference | scales/JudgeEntity/Inconclusive |


## Comments

* 6256896 occurrences with untyped subjects and object type jxdm72_Judge.
* 23177 occurrences with untyped subjects and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:hasJudgeReference |
| native | scales-kg-new/:scales_hasJudgeReference |




## LinkML Source

<details>

```yaml
name: scales_hasJudgeReference
description: No slot (predicate) description specified
comments:
- 6256896 occurrences with untyped subjects and object type jxdm72_Judge.
- 23177 occurrences with untyped subjects and object type uri.
examples:
- description: None → jxdm72_Judge
  object:
    example_object: scales/JudgeEntity/SJ001755
    example_object_type: jxdm72_Judge
    example_predicate: scales:hasJudgeReference
    example_subject: scales/DocketEntry/wyd;;6:17-cr-00033_de6
    example_subject_type: None
- description: None → uri
  object:
    example_object: scales/JudgeEntity/Inconclusive
    example_object_type: uri
    example_predicate: scales:hasJudgeReference
    example_subject: scales/DocketEntry/almd;;1:16-cr-00434_de4
    example_subject_type: None
from_schema: scales-kg-new
rank: 1000
slot_uri: scales:hasJudgeReference
alias: scales_hasJudgeReference
range: Any
any_of:
- range: jxdm72_Judge
- range: uri

```
</details>