

# Slot: prov_wasGeneratedBy


_No slot (predicate) description specified_






This slot occurs 1495 times.


URI: [prov:wasGeneratedBy](http://www.w3.org/ns/prov#wasGeneratedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoCategoryCode](../classes/HsdoCategoryCode.md) | A Category Code |  yes  |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  yes  |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |
| [HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular gover... |  yes  |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |
| [HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place o... |  yes  |
| [HsdoContactPoint](../classes/HsdoContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department |  yes  |
| [HsdoAudience](../classes/HsdoAudience.md) | Intended audience for an item, i |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |
| [HsdoTextObject](../classes/HsdoTextObject.md) | A text file |  yes  |







## Properties

* Range: [ProvActivity](../classes/ProvActivity.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | prov_Activity | dreamkg:category/audience/AbuseOrNeglectSurvivors | dreamkg:process/run/ontop-CM | 1495 |
| hsdo_Audience | prov_Activity | dreamkg:category/audience/AbuseOrNeglectSurvivors | dreamkg:process/run/ontop-CM | 81 |
| hsdo_CategoryCode | prov_Activity | dreamkg:category/availability/Available | dreamkg:process/run/ontop-CM | 157 |
| hsdo_Service | prov_Activity | dreamkg:service/4542572480692224 | dreamkg:process/run/ontop-CM | 87 |
| hsdo_TextObject | prov_Activity | dreamkg:service/desc/4542572480692224 | dreamkg:process/run/ontop-CM | 87 |
| hsdo_OpeningHoursSpecification | prov_Activity | dreamkg:service/hours/friday/4542572480692224 | dreamkg:process/run/ontop-CM | 609 |
| hsdo_Place | prov_Activity | dreamkg:service/location/4542572480692224 | dreamkg:process/run/ontop-CM | 87 |
| hsdo_ContactPoint | prov_Activity | dreamkg:service/phone/4542572480692224 | dreamkg:process/run/ontop-CM | 87 |
| hsdo_Organization | prov_Activity | dreamkg:service/provider/4542572480692224 | dreamkg:process/run/ontop-CM | 87 |
| hsdo_AdministrativeArea | prov_Activity | dreamkg:zip/17602 | dreamkg:process/run/ontop-CM | 39 |




## LinkML Source

<details>

```yaml
name: prov_wasGeneratedBy
annotations:
  count:
    tag: count
    value: 1495
description: No slot (predicate) description specified
examples:
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_subject_type: hsdo_Audience
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:category/availability/Available
    example_subject_type: hsdo_CategoryCode
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/desc/4542572480692224
    example_subject_type: hsdo_TextObject
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: hsdo_OpeningHoursSpecification
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/phone/4542572480692224
    example_subject_type: hsdo_ContactPoint
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/provider/4542572480692224
    example_subject_type: hsdo_Organization
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:zip/17602
    example_subject_type: hsdo_AdministrativeArea
from_schema: dream-kg
rank: 1000
slot_uri: prov:wasGeneratedBy
alias: prov_wasGeneratedBy
domain_of:
- hsdo_AdministrativeArea
- hsdo_Audience
- hsdo_CategoryCode
- hsdo_ContactPoint
- hsdo_OpeningHoursSpecification
- hsdo_Organization
- hsdo_Place
- hsdo_Service
- hsdo_TextObject
- prov_Entity
range: prov_Activity

```
</details>