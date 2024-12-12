

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
| hsdo_Service → hsdo_CategoryCode | dreamkg:service/5181712996761600 | hsdo:category | dreamkg:category/service/main/OneOnOneSupport |
| hsdo_Service → hsdo_Audience | dreamkg:service/6272068172382208 | hsdo:category | dreamkg:category/audience/YoungAdults |


## Comments

* 806 occurrences with subject type hsdo_Service and object type hsdo_CategoryCode.
* 539 occurrences with subject type hsdo_Service and object type hsdo_Audience.

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
- 806 occurrences with subject type hsdo_Service and object type hsdo_CategoryCode.
- 539 occurrences with subject type hsdo_Service and object type hsdo_Audience.
examples:
- description: hsdo_Service → hsdo_CategoryCode
  object:
    example_object: dreamkg:category/service/main/OneOnOneSupport
    example_predicate: hsdo:category
    example_subject: dreamkg:service/5181712996761600
- description: hsdo_Service → hsdo_Audience
  object:
    example_object: dreamkg:category/audience/YoungAdults
    example_predicate: hsdo:category
    example_subject: dreamkg:service/6272068172382208
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