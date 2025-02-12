

# Slot: telephone (hsdo_telephone)


_The telephone number._






This slot occurs 87 times.


URI: [hsdo:telephone](http://schema.org/telephone)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoContactPoint](../classes/HsdoContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_ContactPoint | string | dreamkg:service/phone/4689179354857472 | 215-276-3922 | 87 |




## LinkML Source

<details>

```yaml
name: hsdo_telephone
annotations:
  count:
    tag: count
    value: 87
description: The telephone number.
title: telephone
examples:
- description: hsdo_ContactPoint→string
  object:
    example_object: 215-276-3922
    example_object_type: string
    example_predicate: hsdo:telephone
    example_subject: dreamkg:service/phone/4689179354857472
    example_subject_type: hsdo_ContactPoint
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:telephone
alias: hsdo_telephone
domain_of:
- hsdo_ContactPoint
range: string

```
</details>