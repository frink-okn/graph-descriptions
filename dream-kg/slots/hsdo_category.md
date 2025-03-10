

# Slot: hsdo_category


_A category for the item. Greater signs or slashes can be used to informally indicate a category hierarchy._






This slot occurs 1345 times.


URI: [schema:category](http://schema.org/category)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoCategoryCode](../classes/HsdoCategoryCode.md)&nbsp;or&nbsp;<br />[HsdoAudience](../classes/HsdoAudience.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | hsdo_Audience | dreamkg:service/4542572480692224 | dreamkg:category/audience/AlcoholDependency | 539 |
| prov_Entity | prov_Entity | dreamkg:service/4542572480692224 | dreamkg:category/audience/AlcoholDependency | 1345 |
| hsdo_Service | hsdo_Audience | dreamkg:service/4542572480692224 | dreamkg:category/audience/AlcoholDependency | 539 |
| hsdo_Service | prov_Entity | dreamkg:service/4542572480692224 | dreamkg:category/audience/AlcoholDependency | 1345 |
| prov_Entity | hsdo_CategoryCode | dreamkg:service/4542572480692224 | dreamkg:category/availability/Available | 806 |
| hsdo_Service | hsdo_CategoryCode | dreamkg:service/4542572480692224 | dreamkg:category/availability/Available | 806 |




## LinkML Source

<details>

```yaml
name: hsdo_category
annotations:
  count:
    tag: count
    value: 1345
description: A category for the item. Greater signs or slashes can be used to informally
  indicate a category hierarchy.
examples:
- object:
    example_object: dreamkg:category/audience/AlcoholDependency
    example_object_type: hsdo_Audience
    example_predicate: schema:category
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:category/audience/AlcoholDependency
    example_object_type: prov_Entity
    example_predicate: schema:category
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:category/audience/AlcoholDependency
    example_object_type: hsdo_Audience
    example_predicate: schema:category
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: dreamkg:category/audience/AlcoholDependency
    example_object_type: prov_Entity
    example_predicate: schema:category
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: dreamkg:category/availability/Available
    example_object_type: hsdo_CategoryCode
    example_predicate: schema:category
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:category/availability/Available
    example_object_type: hsdo_CategoryCode
    example_predicate: schema:category
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: schema:category
alias: hsdo_category
domain_of:
- hsdo_Service
- prov_Entity
range: Any
any_of:
- range: hsdo_CategoryCode
- range: hsdo_Audience
- range: prov_Entity

```
</details>