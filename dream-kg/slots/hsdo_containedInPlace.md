

# Slot: hsdo_containedInPlace


_The basic containment relation between a place and one that contains it._






This slot occurs 88 times.


URI: [schema:containedInPlace](http://schema.org/containedInPlace)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)&nbsp;or&nbsp;<br />[HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Place | prov_Entity | dreamkg:service/location/4542572480692224 | dreamkg:zip/19153 | 88 |
| hsdo_Place | hsdo_AdministrativeArea | dreamkg:service/location/4542572480692224 | dreamkg:zip/19153 | 88 |
| prov_Entity | prov_Entity | dreamkg:service/location/4542572480692224 | dreamkg:zip/19153 | 88 |
| prov_Entity | hsdo_AdministrativeArea | dreamkg:service/location/4542572480692224 | dreamkg:zip/19153 | 88 |




## LinkML Source

<details>

```yaml
name: hsdo_containedInPlace
annotations:
  count:
    tag: count
    value: 88
description: The basic containment relation between a place and one that contains
  it.
examples:
- object:
    example_object: dreamkg:zip/19153
    example_object_type: prov_Entity
    example_predicate: schema:containedInPlace
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
- object:
    example_object: dreamkg:zip/19153
    example_object_type: hsdo_AdministrativeArea
    example_predicate: schema:containedInPlace
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
- object:
    example_object: dreamkg:zip/19153
    example_object_type: prov_Entity
    example_predicate: schema:containedInPlace
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:zip/19153
    example_object_type: hsdo_AdministrativeArea
    example_predicate: schema:containedInPlace
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: prov_Entity
from_schema: dream-kg
rank: 1000
slot_uri: schema:containedInPlace
alias: hsdo_containedInPlace
domain_of:
- hsdo_Place
- prov_Entity
range: Any
any_of:
- range: prov_Entity
- range: hsdo_AdministrativeArea

```
</details>