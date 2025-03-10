

# Slot: prov_generated


_No slot (predicate) description specified_






This slot occurs 1495 times.


URI: [prov:generated](http://www.w3.org/ns/prov#generated)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvActivity](../classes/ProvActivity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoCategoryCode](../classes/HsdoCategoryCode.md)&nbsp;or&nbsp;<br />[HsdoAudience](../classes/HsdoAudience.md)&nbsp;or&nbsp;<br />[HsdoPlace](../classes/HsdoPlace.md)&nbsp;or&nbsp;<br />[HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md)&nbsp;or&nbsp;<br />[HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md)&nbsp;or&nbsp;<br />[HsdoService](../classes/HsdoService.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)&nbsp;or&nbsp;<br />[HsdoOrganization](../classes/HsdoOrganization.md)&nbsp;or&nbsp;<br />[HsdoContactPoint](../classes/HsdoContactPoint.md)&nbsp;or&nbsp;<br />[HsdoTextObject](../classes/HsdoTextObject.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Activity | hsdo_Audience | dreamkg:process/run/ontop-CM | dreamkg:category/audience/AbuseOrNeglectSurvivors | 81 |
| prov_Activity | prov_Entity | dreamkg:process/run/ontop-CM | dreamkg:category/audience/AbuseOrNeglectSurvivors | 1495 |
| prov_Activity | hsdo_CategoryCode | dreamkg:process/run/ontop-CM | dreamkg:category/availability/Available | 157 |
| prov_Activity | hsdo_Service | dreamkg:process/run/ontop-CM | dreamkg:service/4542572480692224 | 87 |
| prov_Activity | hsdo_TextObject | dreamkg:process/run/ontop-CM | dreamkg:service/desc/4542572480692224 | 87 |
| prov_Activity | hsdo_OpeningHoursSpecification | dreamkg:process/run/ontop-CM | dreamkg:service/hours/friday/4542572480692224 | 609 |
| prov_Activity | hsdo_Place | dreamkg:process/run/ontop-CM | dreamkg:service/location/4542572480692224 | 87 |
| prov_Activity | hsdo_ContactPoint | dreamkg:process/run/ontop-CM | dreamkg:service/phone/4542572480692224 | 87 |
| prov_Activity | hsdo_Organization | dreamkg:process/run/ontop-CM | dreamkg:service/provider/4542572480692224 | 87 |
| prov_Activity | hsdo_AdministrativeArea | dreamkg:process/run/ontop-CM | dreamkg:zip/17602 | 39 |




## LinkML Source

<details>

```yaml
name: prov_generated
annotations:
  count:
    tag: count
    value: 1495
description: No slot (predicate) description specified
examples:
- object:
    example_object: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_object_type: hsdo_Audience
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_object_type: prov_Entity
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:category/availability/Available
    example_object_type: hsdo_CategoryCode
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/4542572480692224
    example_object_type: hsdo_Service
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/desc/4542572480692224
    example_object_type: hsdo_TextObject
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/hours/friday/4542572480692224
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/location/4542572480692224
    example_object_type: hsdo_Place
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/phone/4542572480692224
    example_object_type: hsdo_ContactPoint
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/provider/4542572480692224
    example_object_type: hsdo_Organization
    example_predicate: prov:generated
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:zip/17602
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
- range: hsdo_CategoryCode
- range: hsdo_Audience
- range: hsdo_Place
- range: hsdo_AdministrativeArea
- range: hsdo_OpeningHoursSpecification
- range: hsdo_Service
- range: prov_Entity
- range: hsdo_Organization
- range: hsdo_ContactPoint
- range: hsdo_TextObject

```
</details>