

# Slot: hsdo_telephone


_No slot (predicate) description specified_





URI: [hsdo:telephone](hsdo:telephone)



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
| hsdo_ContactPoint → string | dreamkg:service/phone/5992920927698944 | hsdo:telephone | 215-496-9610 |


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
    example_object: 215-496-9610
    example_predicate: hsdo:telephone
    example_subject: dreamkg:service/phone/5992920927698944
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:telephone
alias: hsdo_telephone
domain_of:
- hsdo_ContactPoint
range: string

```
</details>