

# Slot: scales_isInstanceOfEntity


_No slot (predicate) description specified_





URI: [scales:isInstanceOfEntity](http://schemas.scales-okn.org/rdf/scales#isInstanceOfEntity)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Jxdm72Judge](../classes/Jxdm72Judge.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None → uri | scales/Agent/almd;;1:16-cr-00020_a1 | scales:isInstanceOfEntity | scales/PartyEntity/SPID-GOVERNMENT-ST-025-000001969 |
| None → jxdm72_Judge | scales/Agent/wyd;;6:17-cr-00033_a2 | scales:isInstanceOfEntity | scales/JudgeEntity/SJ001755 |


## Comments

* 939873 occurrences with untyped subjects and object type uri.
* 715622 occurrences with untyped subjects and object type jxdm72_Judge.



## LinkML Source

<details>

```yaml
name: scales_isInstanceOfEntity
description: No slot (predicate) description specified
comments:
- 939873 occurrences with untyped subjects and object type uri.
- 715622 occurrences with untyped subjects and object type jxdm72_Judge.
examples:
- description: None → uri
  object:
    example_object: scales/PartyEntity/SPID-GOVERNMENT-ST-025-000001969
    example_object_type: uri
    example_predicate: scales:isInstanceOfEntity
    example_subject: scales/Agent/almd;;1:16-cr-00020_a1
    example_subject_type: None
- description: None → jxdm72_Judge
  object:
    example_object: scales/JudgeEntity/SJ001755
    example_object_type: jxdm72_Judge
    example_predicate: scales:isInstanceOfEntity
    example_subject: scales/Agent/wyd;;6:17-cr-00033_a2
    example_subject_type: None
from_schema: scales-kg-new
rank: 1000
slot_uri: scales:isInstanceOfEntity
alias: scales_isInstanceOfEntity
range: Any
any_of:
- range: jxdm72_Judge
- range: uri

```
</details>