

# Slot: jxdm72_CaseCharge


_No slot (predicate) description specified_





URI: [jxdm72:CaseCharge](http://release.niem.gov/niem/domains/jxdm/7.2/#CaseCharge)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| scales_Case → uri | scales/CaseCriminal | jxdm72:CaseCharge | scales/Charge/almd;;1:16-cr-00020_c0-1 |


## Comments

* 213743 occurrences with subject type scales_Case and object type uri.



## LinkML Source

<details>

```yaml
name: jxdm72_CaseCharge
description: No slot (predicate) description specified
comments:
- 213743 occurrences with subject type scales_Case and object type uri.
examples:
- description: scales_Case → uri
  object:
    example_object: scales/Charge/almd;;1:16-cr-00020_c0-1
    example_object_type: uri
    example_predicate: jxdm72:CaseCharge
    example_subject: scales/CaseCriminal
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:CaseCharge
alias: jxdm72_CaseCharge
domain_of:
- scales_Case
range: uri

```
</details>