

# Slot: category (hsdo_category)


_A category for the item. Greater signs or slashes can be used to informally indicate a category hierarchy._






This slot occurs 1345 times.


URI: [hsdo:category](http://schema.org/category)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoCategoryCode](../classes/HsdoCategoryCode.md)&nbsp;or&nbsp;<br />[HsdoAudience](../classes/HsdoAudience.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Service | hsdo_CategoryCode | dreamkg:service/6379467169595392 | dreamkg:category/service/main/AddictionAndRecovery | 806 |
| hsdo_Service | hsdo_Audience | dreamkg:service/6379467169595392 | dreamkg:category/audience/SubstanceDependency | 539 |




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
title: category
examples:
- description: hsdo_Service→hsdo_CategoryCode
  object:
    example_object: dreamkg:category/service/main/AddictionAndRecovery
    example_object_type: hsdo_CategoryCode
    example_predicate: hsdo:category
    example_subject: dreamkg:service/6379467169595392
    example_subject_type: hsdo_Service
- description: hsdo_Service→hsdo_Audience
  object:
    example_object: dreamkg:category/audience/SubstanceDependency
    example_object_type: hsdo_Audience
    example_predicate: hsdo:category
    example_subject: dreamkg:service/6379467169595392
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:category
alias: hsdo_category
domain_of:
- hsdo_Service
range: Any
any_of:
- range: hsdo_CategoryCode
- range: hsdo_Audience

```
</details>