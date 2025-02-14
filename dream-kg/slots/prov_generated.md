

# Slot: prov_generated


_No slot (predicate) description specified_





URI: [prov:generated](http://www.w3.org/ns/prov#generated)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvActivity](../classes/ProvActivity.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)&nbsp;or&nbsp;<br />[HsdoContactPoint](../classes/HsdoContactPoint.md)&nbsp;or&nbsp;<br />[HsdoPlace](../classes/HsdoPlace.md)&nbsp;or&nbsp;<br />[HsdoAudience](../classes/HsdoAudience.md)&nbsp;or&nbsp;<br />[HsdoTextObject](../classes/HsdoTextObject.md)&nbsp;or&nbsp;<br />[HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md)&nbsp;or&nbsp;<br />[HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md)&nbsp;or&nbsp;<br />[HsdoService](../classes/HsdoService.md)&nbsp;or&nbsp;<br />[HsdoOrganization](../classes/HsdoOrganization.md)&nbsp;or&nbsp;<br />[HsdoCategoryCode](../classes/HsdoCategoryCode.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| prov_Activity → hsdo_Audience | dreamkg:process/run/ontop-CM | prov:generated | dreamkg:category/audience/YoungAdults |
| prov_Activity → hsdo_CategoryCode | dreamkg:process/run/ontop-CM | prov:generated | dreamkg:category/service/other/WeatherRelief |
| prov_Activity → hsdo_Service | dreamkg:process/run/ontop-CM | prov:generated | dreamkg:service/6710596967858176 |
| prov_Activity → prov_Entity | dreamkg:process/run/ontop-CM | prov:generated | dreamkg:service/channel/P--6710596967858176 |
| prov_Activity → hsdo_TextObject | dreamkg:process/run/ontop-CM | prov:generated | dreamkg:service/desc/6710596967858176 |
| prov_Activity → hsdo_OpeningHoursSpecification | dreamkg:process/run/ontop-CM | prov:generated | dreamkg:service/hours/wednesday/6710596967858176 |
| prov_Activity → hsdo_Place | dreamkg:process/run/ontop-CM | prov:generated | dreamkg:service/location/6710596967858176 |
| prov_Activity → hsdo_ContactPoint | dreamkg:process/run/ontop-CM | prov:generated | dreamkg:service/phone/6710596967858176 |
| prov_Activity → hsdo_Organization | dreamkg:process/run/ontop-CM | prov:generated | dreamkg:service/provider/6710596967858176 |
| prov_Activity → hsdo_AdministrativeArea | dreamkg:process/run/ontop-CM | prov:generated | dreamkg:zip/19320 |


## Comments

* 81 occurrences with subject type prov_Activity and object type hsdo_Audience.
* 157 occurrences with subject type prov_Activity and object type hsdo_CategoryCode.
* 87 occurrences with subject type prov_Activity and object type hsdo_Service.
* 174 occurrences with subject type prov_Activity and object type prov_Entity.
* 87 occurrences with subject type prov_Activity and object type hsdo_TextObject.
* 609 occurrences with subject type prov_Activity and object type hsdo_OpeningHoursSpecification.
* 87 occurrences with subject type prov_Activity and object type hsdo_Place.
* 87 occurrences with subject type prov_Activity and object type hsdo_ContactPoint.
* 87 occurrences with subject type prov_Activity and object type hsdo_Organization.
* 39 occurrences with subject type prov_Activity and object type hsdo_AdministrativeArea.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:generated |
| native | dream-kg/:prov_generated |




## LinkML Source

<details>
```yaml
name: prov_generated
description: No slot (predicate) description specified
comments:
- 81 occurrences with subject type prov_Activity and object type hsdo_Audience.
- 157 occurrences with subject type prov_Activity and object type hsdo_CategoryCode.
- 87 occurrences with subject type prov_Activity and object type hsdo_Service.
- 174 occurrences with subject type prov_Activity and object type prov_Entity.
- 87 occurrences with subject type prov_Activity and object type hsdo_TextObject.
- 609 occurrences with subject type prov_Activity and object type hsdo_OpeningHoursSpecification.
- 87 occurrences with subject type prov_Activity and object type hsdo_Place.
- 87 occurrences with subject type prov_Activity and object type hsdo_ContactPoint.
- 87 occurrences with subject type prov_Activity and object type hsdo_Organization.
- 39 occurrences with subject type prov_Activity and object type hsdo_AdministrativeArea.
examples:
- description: prov_Activity → hsdo_Audience
  object:
    example_object: dreamkg:category/audience/YoungAdults
    example_object_type: hsdo_Audience
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- description: prov_Activity → hsdo_CategoryCode
  object:
    example_object: dreamkg:category/service/other/WeatherRelief
    example_object_type: hsdo_CategoryCode
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- description: prov_Activity → hsdo_Service
  object:
    example_object: dreamkg:service/6710596967858176
    example_object_type: hsdo_Service
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- description: prov_Activity → prov_Entity
  object:
    example_object: dreamkg:service/channel/P--6710596967858176
    example_object_type: prov_Entity
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- description: prov_Activity → hsdo_TextObject
  object:
    example_object: dreamkg:service/desc/6710596967858176
    example_object_type: hsdo_TextObject
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- description: prov_Activity → hsdo_OpeningHoursSpecification
  object:
    example_object: dreamkg:service/hours/wednesday/6710596967858176
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- description: prov_Activity → hsdo_Place
  object:
    example_object: dreamkg:service/location/6710596967858176
    example_object_type: hsdo_Place
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- description: prov_Activity → hsdo_ContactPoint
  object:
    example_object: dreamkg:service/phone/6710596967858176
    example_object_type: hsdo_ContactPoint
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- description: prov_Activity → hsdo_Organization
  object:
    example_object: dreamkg:service/provider/6710596967858176
    example_object_type: hsdo_Organization
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- description: prov_Activity → hsdo_AdministrativeArea
  object:
    example_object: dreamkg:zip/19320
    example_object_type: hsdo_AdministrativeArea
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
from_schema: dream-kg
rank: 1000
slot_uri: prov:generated
alias: prov_generated
domain_of:
- prov_Activity
range: Any
any_of:
- range: prov_Entity
- range: hsdo_ContactPoint
- range: hsdo_Place
- range: hsdo_Audience
- range: hsdo_TextObject
- range: hsdo_OpeningHoursSpecification
- range: hsdo_AdministrativeArea
- range: hsdo_Service
- range: hsdo_Organization
- range: hsdo_CategoryCode

```
</details>