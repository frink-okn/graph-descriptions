

# Slot: jxdm72_StatuteKeywordText


_No slot (predicate) description specified_





URI: [jxdm72:StatuteKeywordText](http://release.niem.gov/niem/domains/jxdm/7.2/#StatuteKeywordText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| scales_Case → string | scales/CaseCivil | jxdm72:StatuteKeywordText |  28:1332sh Diversity-Sexual Harassment |


## Comments

* 2680 occurrences with subject type scales_Case and object type string.



## LinkML Source

<details>

```yaml
name: jxdm72_StatuteKeywordText
description: No slot (predicate) description specified
comments:
- 2680 occurrences with subject type scales_Case and object type string.
examples:
- description: scales_Case → string
  object:
    example_object: ' 28:1332sh Diversity-Sexual Harassment'
    example_object_type: string
    example_predicate: jxdm72:StatuteKeywordText
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:StatuteKeywordText
alias: jxdm72_StatuteKeywordText
domain_of:
- scales_Case
range: string

```
</details>