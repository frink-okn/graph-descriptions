

# Slot: prov_wasDerivedFrom


_No slot (predicate) description specified_





URI: [prov:wasDerivedFrom](http://www.w3.org/ns/prov#wasDerivedFrom)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular gover... |  no  |
| [HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place o... |  no  |
| [HsdoCategoryCode](../classes/HsdoCategoryCode.md) | A Category Code |  no  |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |
| [HsdoContactPoint](../classes/HsdoContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department |  no  |
| [HsdoTextObject](../classes/HsdoTextObject.md) | A text file |  no  |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |
| [HsdoAudience](../classes/HsdoAudience.md) | Intended audience for an item, i |  no  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  no  |







## Properties

* Range: [ProvEntity](../classes/ProvEntity.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Audience → prov_Entity | dreamkg:category/audience/YoungAdults | prov:wasDerivedFrom | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_CategoryCode → prov_Entity | dreamkg:category/service/other/WeatherRelief | prov:wasDerivedFrom | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_Service → prov_Entity | dreamkg:service/6710596967858176 | prov:wasDerivedFrom | dreamkg:file/IJCAI/mappings/ontology.obda |
| prov_Entity → prov_Entity | dreamkg:service/channel/P--6710596967858176 | prov:wasDerivedFrom | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_TextObject → prov_Entity | dreamkg:service/desc/6710596967858176 | prov:wasDerivedFrom | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_OpeningHoursSpecification → prov_Entity | dreamkg:service/hours/wednesday/6710596967858176 | prov:wasDerivedFrom | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_Place → prov_Entity | dreamkg:service/location/6710596967858176 | prov:wasDerivedFrom | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_ContactPoint → prov_Entity | dreamkg:service/phone/6710596967858176 | prov:wasDerivedFrom | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_Organization → prov_Entity | dreamkg:service/provider/6710596967858176 | prov:wasDerivedFrom | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_AdministrativeArea → prov_Entity | dreamkg:zip/19320 | prov:wasDerivedFrom | dreamkg:file/IJCAI/mappings/ontology.obda |


## Comments

* 162 occurrences with subject type hsdo_Audience and object type prov_Entity.
* 314 occurrences with subject type hsdo_CategoryCode and object type prov_Entity.
* 174 occurrences with subject type hsdo_Service and object type prov_Entity.
* 348 occurrences with subject type prov_Entity and object type prov_Entity.
* 174 occurrences with subject type hsdo_TextObject and object type prov_Entity.
* 1218 occurrences with subject type hsdo_OpeningHoursSpecification and object type prov_Entity.
* 174 occurrences with subject type hsdo_Place and object type prov_Entity.
* 174 occurrences with subject type hsdo_ContactPoint and object type prov_Entity.
* 174 occurrences with subject type hsdo_Organization and object type prov_Entity.
* 78 occurrences with subject type hsdo_AdministrativeArea and object type prov_Entity.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:wasDerivedFrom |
| native | dream-kg/:prov_wasDerivedFrom |




## LinkML Source

<details>
```yaml
name: prov_wasDerivedFrom
description: No slot (predicate) description specified
comments:
- 162 occurrences with subject type hsdo_Audience and object type prov_Entity.
- 314 occurrences with subject type hsdo_CategoryCode and object type prov_Entity.
- 174 occurrences with subject type hsdo_Service and object type prov_Entity.
- 348 occurrences with subject type prov_Entity and object type prov_Entity.
- 174 occurrences with subject type hsdo_TextObject and object type prov_Entity.
- 1218 occurrences with subject type hsdo_OpeningHoursSpecification and object type
  prov_Entity.
- 174 occurrences with subject type hsdo_Place and object type prov_Entity.
- 174 occurrences with subject type hsdo_ContactPoint and object type prov_Entity.
- 174 occurrences with subject type hsdo_Organization and object type prov_Entity.
- 78 occurrences with subject type hsdo_AdministrativeArea and object type prov_Entity.
examples:
- description: hsdo_Audience → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasDerivedFrom
    example_subject: dreamkg:category/audience/YoungAdults
    example_subject_type: hsdo_Audience
- description: hsdo_CategoryCode → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasDerivedFrom
    example_subject: dreamkg:category/service/other/WeatherRelief
    example_subject_type: hsdo_CategoryCode
- description: hsdo_Service → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasDerivedFrom
    example_subject: dreamkg:service/6710596967858176
    example_subject_type: hsdo_Service
- description: prov_Entity → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasDerivedFrom
    example_subject: dreamkg:service/channel/P--6710596967858176
    example_subject_type: prov_Entity
- description: hsdo_TextObject → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasDerivedFrom
    example_subject: dreamkg:service/desc/6710596967858176
    example_subject_type: hsdo_TextObject
- description: hsdo_OpeningHoursSpecification → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasDerivedFrom
    example_subject: dreamkg:service/hours/wednesday/6710596967858176
    example_subject_type: hsdo_OpeningHoursSpecification
- description: hsdo_Place → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasDerivedFrom
    example_subject: dreamkg:service/location/6710596967858176
    example_subject_type: hsdo_Place
- description: hsdo_ContactPoint → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasDerivedFrom
    example_subject: dreamkg:service/phone/6710596967858176
    example_subject_type: hsdo_ContactPoint
- description: hsdo_Organization → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasDerivedFrom
    example_subject: dreamkg:service/provider/6710596967858176
    example_subject_type: hsdo_Organization
- description: hsdo_AdministrativeArea → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasDerivedFrom
    example_subject: dreamkg:zip/19320
    example_subject_type: hsdo_AdministrativeArea
from_schema: dream-kg
rank: 1000
slot_uri: prov:wasDerivedFrom
alias: prov_wasDerivedFrom
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
range: prov_Entity

```
</details>