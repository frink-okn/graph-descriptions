

# Slot: niem50_OrganizationName


_No slot (predicate) description specified_






This slot occurs 17041 times.


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
| scales_Firm | string | scales:/Agent/casd;;3:16-cv-01644_a6 | Federal Defenders of San Diego | 17041 |




## LinkML Source

<details>

```yaml
name: niem50_OrganizationName
annotations:
  count:
    tag: count
    value: 17041
description: No slot (predicate) description specified
examples:
- object:
    example_object: Federal Defenders of San Diego
    example_object_type: string
    example_predicate: niem50:OrganizationName
    example_subject: scales:/Agent/casd;;3:16-cv-01644_a6
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