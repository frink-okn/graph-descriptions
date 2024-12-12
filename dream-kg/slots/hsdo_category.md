

# Slot: hsdo_category


_No slot (predicate) description specified_





URI: [hsdo:category](hsdo:category)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoCategoryCode](../classes/HsdoCategoryCode.md)&nbsp;or&nbsp;<br />[HsdoAudience](../classes/HsdoAudience.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Service → hsdo_Audience | dreamkg:service/6710596967858176 | hsdo:category | dreamkg:category/audience/Veterans |
| hsdo_Service → hsdo_CategoryCode | dreamkg:service/6710596967858176 | hsdo:category | dreamkg:category/service/other/SkillsAndTraining |


## Comments

* 539 occurrences with subject type hsdo_Service and object type hsdo_Audience.
* 806 occurrences with subject type hsdo_Service and object type hsdo_CategoryCode.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:category |
| native | dream-kg/:hsdo_category |




## LinkML Source

<details>
```yaml
name: hsdo_category
description: No slot (predicate) description specified
comments:
- 539 occurrences with subject type hsdo_Service and object type hsdo_Audience.
- 806 occurrences with subject type hsdo_Service and object type hsdo_CategoryCode.
examples:
- description: hsdo_Service → hsdo_Audience
  object:
    example_object: dreamkg:category/audience/Veterans
    example_predicate: hsdo:category
    example_subject: dreamkg:service/6710596967858176
- description: hsdo_Service → hsdo_CategoryCode
  object:
    example_object: dreamkg:category/service/other/SkillsAndTraining
    example_predicate: hsdo:category
    example_subject: dreamkg:service/6710596967858176
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