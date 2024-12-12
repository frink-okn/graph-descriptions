

# Slot: hsdo_areaServed


_No slot (predicate) description specified_





URI: [hsdo:areaServed](hsdo:areaServed)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Service → string | dreamkg:service/4542572480692224 | hsdo:areaServed | This program covers residents of the following counties: Chester County, PA, Delaware County, PA, Montgomery County, PA and Philadelphia County, PA. |


## Comments

* 87 occurrences with subject type hsdo_Service and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:areaServed |
| native | dream-kg/:hsdo_areaServed |




## LinkML Source

<details>
```yaml
name: hsdo_areaServed
description: No slot (predicate) description specified
comments:
- 87 occurrences with subject type hsdo_Service and object type string.
examples:
- description: hsdo_Service → string
  object:
    example_object: 'This program covers residents of the following counties: Chester
      County, PA, Delaware County, PA, Montgomery County, PA and Philadelphia County,
      PA.'
    example_predicate: hsdo:areaServed
    example_subject: dreamkg:service/4542572480692224
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:areaServed
alias: hsdo_areaServed
domain_of:
- hsdo_Service
range: string

```
</details>