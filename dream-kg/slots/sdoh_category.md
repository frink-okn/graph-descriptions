

# Slot: sdoh_category


_TODO -- tell the world what this slot (predicate) describes._





URI: [sdoh:category](http://schema.org/category)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohService](../classes/SdohService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdohAudience](../classes/SdohAudience.md)&nbsp;or&nbsp;<br />[SdohCategoryCode](../classes/SdohCategoryCode.md)






## Examples

| Value |
| --- |
| dreamkg:service/6032260047568896 sdoh:category dreamkg:category/audience/BenefitRecipients |
| dreamkg:service/5089660355477504 sdoh:category dreamkg:category/service/main/AdvocacyAndLegalAid |

## Comments

* 539 occurrences with subject type sdoh_Service and object type sdoh_Audience.
* 806 occurrences with subject type sdoh_Service and object type sdoh_CategoryCode.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:category |
| native | dream-kg/:sdoh_category |




## LinkML Source

<details>
```yaml
name: sdoh_category
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 539 occurrences with subject type sdoh_Service and object type sdoh_Audience.
- 806 occurrences with subject type sdoh_Service and object type sdoh_CategoryCode.
examples:
- value: dreamkg:service/6032260047568896 sdoh:category dreamkg:category/audience/BenefitRecipients
- value: dreamkg:service/5089660355477504 sdoh:category dreamkg:category/service/main/AdvocacyAndLegalAid
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:category
alias: sdoh_category
domain_of:
- sdoh_Service
range: Any
any_of:
- range: sdoh_Audience
- range: sdoh_CategoryCode

```
</details>