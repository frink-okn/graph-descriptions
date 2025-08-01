

# Slot: niem50_OrganizationName


_No slot (predicate) description specified_






This slot occurs 2929547 times.


URI: [niem50:OrganizationName](http://release.niem.gov/niem/niem-core/5.0/OrganizationName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesFirm](../classes/ScalesFirm.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_Firm | string | scales:/Agent/akd;;1:16-cr-00001_a10 | U.S. Attorney's Office (Anch) | 2929547 |




## LinkML Source

<details>

```yaml
name: niem50_OrganizationName
annotations:
  count:
    tag: count
    value: 2929547
description: No slot (predicate) description specified
examples:
- object:
    example_object: U.S. Attorney's Office (Anch)
    example_object_type: string
    example_predicate: niem50:OrganizationName
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a10
    example_subject_type: scales_Firm
from_schema: scales-kg
rank: 1000
slot_uri: niem50:OrganizationName
alias: niem50_OrganizationName
domain_of:
- scales_Firm
range: string

```
</details>