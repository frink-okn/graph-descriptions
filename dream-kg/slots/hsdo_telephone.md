

# Slot: hsdo_telephone


_The telephone number._






This slot occurs 87 times.


URI: [schema:telephone](http://schema.org/telephone)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoContactPoint](../classes/HsdoContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_ContactPoint | string | dreamkg:service/phone/4542572480692224 | 484-454-8720 | 87 |
| prov_Entity | string | dreamkg:service/phone/4542572480692224 | 484-454-8720 | 87 |




## LinkML Source

<details>

```yaml
name: hsdo_telephone
annotations:
  count:
    tag: count
    value: 87
description: The telephone number.
examples:
- object:
    example_object: 484-454-8720
    example_object_type: string
    example_predicate: schema:telephone
    example_subject: dreamkg:service/phone/4542572480692224
    example_subject_type: hsdo_ContactPoint
- object:
    example_object: 484-454-8720
    example_object_type: string
    example_predicate: schema:telephone
    example_subject: dreamkg:service/phone/4542572480692224
    example_subject_type: prov_Entity
from_schema: dream-kg
rank: 1000
slot_uri: schema:telephone
alias: hsdo_telephone
domain_of:
- hsdo_ContactPoint
- prov_Entity
range: string

```
</details>