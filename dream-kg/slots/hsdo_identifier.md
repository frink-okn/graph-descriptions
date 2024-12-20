

# Slot: hsdo_identifier


_No slot (predicate) description specified_





URI: [hsdo:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular gover... |  no  |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_AdministrativeArea → string | dreamkg:zip/19320 | hsdo:identifier | 19320 |
| hsdo_Service → string | dreamkg:service/6213025361821696 | hsdo:identifier | 6213025361821696 |


## Comments

* 39 occurrences with subject type hsdo_AdministrativeArea and object type string.
* 87 occurrences with subject type hsdo_Service and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:identifier |
| native | dream-kg/:hsdo_identifier |




## LinkML Source

<details>
```yaml
name: hsdo_identifier
description: No slot (predicate) description specified
comments:
- 39 occurrences with subject type hsdo_AdministrativeArea and object type string.
- 87 occurrences with subject type hsdo_Service and object type string.
examples:
- description: hsdo_AdministrativeArea → string
  object:
    example_object: '19320'
    example_predicate: hsdo:identifier
    example_subject: dreamkg:zip/19320
- description: hsdo_Service → string
  object:
    example_object: '6213025361821696'
    example_predicate: hsdo:identifier
    example_subject: dreamkg:service/6213025361821696
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:identifier
alias: hsdo_identifier
domain_of:
- hsdo_AdministrativeArea
- hsdo_Service
range: string

```
</details>