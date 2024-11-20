

# Slot: sdoh_telephone


_TODO -- tell the world what this slot (predicate) describes._





URI: [sdoh:telephone](http://schema.org/telephone)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohContactPoint](../classes/SdohContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:service/phone/5385341432496128 sdoh:telephone 610-497-1082 |

## Comments

* 87 occurrences with subject type sdoh_ContactPoint and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:telephone |
| native | dream-kg/:sdoh_telephone |




## LinkML Source

<details>
```yaml
name: sdoh_telephone
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 87 occurrences with subject type sdoh_ContactPoint and object type string.
examples:
- value: dreamkg:service/phone/5385341432496128 sdoh:telephone 610-497-1082
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:telephone
alias: sdoh_telephone
domain_of:
- sdoh_ContactPoint
range: string

```
</details>