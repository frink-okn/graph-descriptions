

# Slot: hsdo_telephone


_No slot (predicate) description specified_





URI: [hsdo:telephone](http://schema.org/telephone)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoContactPoint](../classes/HsdoContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_ContactPoint → string | dreamkg:service/phone/4692155605712896 | hsdo:telephone | 833-976-4357 |


## Comments

* 87 occurrences with subject type hsdo_ContactPoint and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:telephone |
| native | dream-kg/:hsdo_telephone |




## LinkML Source

<details>
```yaml
name: hsdo_telephone
description: No slot (predicate) description specified
comments:
- 87 occurrences with subject type hsdo_ContactPoint and object type string.
examples:
- description: hsdo_ContactPoint → string
  object:
    example_object: 833-976-4357
    example_predicate: hsdo:telephone
    example_subject: dreamkg:service/phone/4692155605712896
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:telephone
alias: hsdo_telephone
domain_of:
- hsdo_ContactPoint
range: string

```
</details>