

# Slot: hsdo_description


_A description of the item._






This slot occurs 87 times.


URI: [schema:description](http://schema.org/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)&nbsp;or&nbsp;<br />[HsdoTextObject](../classes/HsdoTextObject.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | prov_Entity | dreamkg:service/4542572480692224 | dreamkg:service/desc/4542572480692224 | 87 |
| prov_Entity | hsdo_TextObject | dreamkg:service/4542572480692224 | dreamkg:service/desc/4542572480692224 | 87 |
| hsdo_Service | prov_Entity | dreamkg:service/4542572480692224 | dreamkg:service/desc/4542572480692224 | 87 |
| hsdo_Service | hsdo_TextObject | dreamkg:service/4542572480692224 | dreamkg:service/desc/4542572480692224 | 87 |




## LinkML Source

<details>

```yaml
name: hsdo_description
annotations:
  count:
    tag: count
    value: 87
description: A description of the item.
examples:
- object:
    example_object: dreamkg:service/desc/4542572480692224
    example_object_type: prov_Entity
    example_predicate: schema:description
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/desc/4542572480692224
    example_object_type: hsdo_TextObject
    example_predicate: schema:description
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/desc/4542572480692224
    example_object_type: prov_Entity
    example_predicate: schema:description
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: dreamkg:service/desc/4542572480692224
    example_object_type: hsdo_TextObject
    example_predicate: schema:description
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: schema:description
alias: hsdo_description
domain_of:
- hsdo_Service
- prov_Entity
range: Any
any_of:
- range: prov_Entity
- range: hsdo_TextObject

```
</details>