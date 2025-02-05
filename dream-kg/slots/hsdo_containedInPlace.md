

# Slot: hsdo_containedInPlace


_No slot (predicate) description specified_





URI: [hsdo:containedInPlace](http://schema.org/containedInPlace)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Place → hsdo_AdministrativeArea | dreamkg:service/location/6710596967858176 | hsdo:containedInPlace | dreamkg:zip/19104 |


## Comments

* 88 occurrences with subject type hsdo_Place and object type hsdo_AdministrativeArea.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:containedInPlace |
| native | dream-kg/:hsdo_containedInPlace |




## LinkML Source

<details>
```yaml
name: hsdo_containedInPlace
description: No slot (predicate) description specified
comments:
- 88 occurrences with subject type hsdo_Place and object type hsdo_AdministrativeArea.
examples:
- description: hsdo_Place → hsdo_AdministrativeArea
  object:
    example_object: dreamkg:zip/19104
    example_object_type: hsdo_AdministrativeArea
    example_predicate: hsdo:containedInPlace
    example_subject: dreamkg:service/location/6710596967858176
    example_subject_type: hsdo_Place
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:containedInPlace
alias: hsdo_containedInPlace
domain_of:
- hsdo_Place
range: hsdo_AdministrativeArea

```
</details>