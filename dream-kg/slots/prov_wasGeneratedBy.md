

# Slot: prov_wasGeneratedBy


_No slot (predicate) description specified_





URI: [prov:wasGeneratedBy](http://www.w3.org/ns/prov#wasGeneratedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular gover... |  no  |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |
| [HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place o... |  no  |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [HsdoTextObject](../classes/HsdoTextObject.md) | A text file |  no  |
| [HsdoAudience](../classes/HsdoAudience.md) | Intended audience for an item, i |  no  |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |
| [HsdoContactPoint](../classes/HsdoContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department |  no  |
| [HsdoCategoryCode](../classes/HsdoCategoryCode.md) | A Category Code |  no  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  no  |







## Properties

* Range: [ProvActivity](../classes/ProvActivity.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Audience → prov_Activity | dreamkg:category/audience/YoungAdults | prov:wasGeneratedBy | dreamkg:process/run/ontop-CM |
| hsdo_CategoryCode → prov_Activity | dreamkg:category/service/other/WeatherRelief | prov:wasGeneratedBy | dreamkg:process/run/ontop-CM |
| hsdo_Service → prov_Activity | dreamkg:service/6710596967858176 | prov:wasGeneratedBy | dreamkg:process/run/ontop-CM |
| prov_Entity → prov_Activity | dreamkg:service/channel/P--6710596967858176 | prov:wasGeneratedBy | dreamkg:process/run/ontop-CM |
| hsdo_TextObject → prov_Activity | dreamkg:service/desc/6710596967858176 | prov:wasGeneratedBy | dreamkg:process/run/ontop-CM |
| hsdo_OpeningHoursSpecification → prov_Activity | dreamkg:service/hours/wednesday/6710596967858176 | prov:wasGeneratedBy | dreamkg:process/run/ontop-CM |
| hsdo_Place → prov_Activity | dreamkg:service/location/6710596967858176 | prov:wasGeneratedBy | dreamkg:process/run/ontop-CM |
| hsdo_ContactPoint → prov_Activity | dreamkg:service/phone/6710596967858176 | prov:wasGeneratedBy | dreamkg:process/run/ontop-CM |
| hsdo_Organization → prov_Activity | dreamkg:service/provider/6710596967858176 | prov:wasGeneratedBy | dreamkg:process/run/ontop-CM |
| hsdo_AdministrativeArea → prov_Activity | dreamkg:zip/19320 | prov:wasGeneratedBy | dreamkg:process/run/ontop-CM |


## Comments

* 81 occurrences with subject type hsdo_Audience and object type prov_Activity.
* 157 occurrences with subject type hsdo_CategoryCode and object type prov_Activity.
* 87 occurrences with subject type hsdo_Service and object type prov_Activity.
* 174 occurrences with subject type prov_Entity and object type prov_Activity.
* 87 occurrences with subject type hsdo_TextObject and object type prov_Activity.
* 609 occurrences with subject type hsdo_OpeningHoursSpecification and object type prov_Activity.
* 87 occurrences with subject type hsdo_Place and object type prov_Activity.
* 87 occurrences with subject type hsdo_ContactPoint and object type prov_Activity.
* 87 occurrences with subject type hsdo_Organization and object type prov_Activity.
* 39 occurrences with subject type hsdo_AdministrativeArea and object type prov_Activity.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:wasGeneratedBy |
| native | dream-kg/:prov_wasGeneratedBy |




## LinkML Source

<details>
```yaml
name: prov_wasGeneratedBy
description: No slot (predicate) description specified
comments:
- 81 occurrences with subject type hsdo_Audience and object type prov_Activity.
- 157 occurrences with subject type hsdo_CategoryCode and object type prov_Activity.
- 87 occurrences with subject type hsdo_Service and object type prov_Activity.
- 174 occurrences with subject type prov_Entity and object type prov_Activity.
- 87 occurrences with subject type hsdo_TextObject and object type prov_Activity.
- 609 occurrences with subject type hsdo_OpeningHoursSpecification and object type
  prov_Activity.
- 87 occurrences with subject type hsdo_Place and object type prov_Activity.
- 87 occurrences with subject type hsdo_ContactPoint and object type prov_Activity.
- 87 occurrences with subject type hsdo_Organization and object type prov_Activity.
- 39 occurrences with subject type hsdo_AdministrativeArea and object type prov_Activity.
examples:
- description: hsdo_Audience → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:category/audience/YoungAdults
    example_subject_type: hsdo_Audience
- description: hsdo_CategoryCode → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:category/service/other/WeatherRelief
    example_subject_type: hsdo_CategoryCode
- description: hsdo_Service → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/6710596967858176
    example_subject_type: hsdo_Service
- description: prov_Entity → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/channel/P--6710596967858176
    example_subject_type: prov_Entity
- description: hsdo_TextObject → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/desc/6710596967858176
    example_subject_type: hsdo_TextObject
- description: hsdo_OpeningHoursSpecification → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/hours/wednesday/6710596967858176
    example_subject_type: hsdo_OpeningHoursSpecification
- description: hsdo_Place → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/location/6710596967858176
    example_subject_type: hsdo_Place
- description: hsdo_ContactPoint → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/phone/6710596967858176
    example_subject_type: hsdo_ContactPoint
- description: hsdo_Organization → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:service/provider/6710596967858176
    example_subject_type: hsdo_Organization
- description: hsdo_AdministrativeArea → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasGeneratedBy
    example_subject: dreamkg:zip/19320
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