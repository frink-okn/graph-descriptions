

# Slot: sdoh_category


_No slot description provided_





URI: [sdoh:category](http://schema.org/category)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohService](../classes/SdohService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdohCategoryCode](../classes/SdohCategoryCode.md)&nbsp;or&nbsp;<br />[SdohAudience](../classes/SdohAudience.md)






## Examples

| Value |
| --- |
| dreamkg:service/5929367212130304 sdoh:category dreamkg:category/language/English |
| dreamkg:service/5390636500647936 sdoh:category dreamkg:category/audience/Children |

## Comments

* 806 occurrences with subject type sdoh_Service and object type sdoh_CategoryCode.
* 539 occurrences with subject type sdoh_Service and object type sdoh_Audience.

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
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 806 occurrences with subject type sdoh_Service and object type sdoh_CategoryCode.
- 539 occurrences with subject type sdoh_Service and object type sdoh_Audience.
examples:
- value: dreamkg:service/5929367212130304 sdoh:category dreamkg:category/language/English
- value: dreamkg:service/5390636500647936 sdoh:category dreamkg:category/audience/Children
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:category
alias: sdoh_category
domain_of:
- sdoh_Service
range: Any
any_of:
- range: sdoh_CategoryCode
- range: sdoh_Audience

```
</details>