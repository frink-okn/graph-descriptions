

# Slot: hsdo_category


_No slot (predicate) description specified_





URI: [hsdo:category](http://schema.org/category)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoAudience](../classes/HsdoAudience.md)&nbsp;or&nbsp;<br />[HsdoCategoryCode](../classes/HsdoCategoryCode.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Service → hsdo_Audience | dreamkg:service/4780892498952192 | hsdo:category | dreamkg:category/audience/WithChildren |
| hsdo_Service → hsdo_CategoryCode | dreamkg:service/5138871176658944 | hsdo:category | dreamkg:category/service/main/MentalHealthCare |


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
    example_object: dreamkg:category/audience/WithChildren
    example_predicate: hsdo:category
    example_subject: dreamkg:service/4780892498952192
- description: hsdo_Service → hsdo_CategoryCode
  object:
    example_object: dreamkg:category/service/main/MentalHealthCare
    example_predicate: hsdo:category
    example_subject: dreamkg:service/5138871176658944
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:category
alias: hsdo_category
domain_of:
- hsdo_Service
range: Any
any_of:
- range: hsdo_Audience
- range: hsdo_CategoryCode

```
</details>