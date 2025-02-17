

# Slot: prov_wasInfluencedBy


_No slot (predicate) description specified_





URI: [prov:wasInfluencedBy](http://www.w3.org/ns/prov#wasInfluencedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  no  |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular gover... |  no  |
| [ProvCollection](../classes/ProvCollection.md) | No class (type) description specified |  no  |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  no  |
| [HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place o... |  no  |
| [HsdoCategoryCode](../classes/HsdoCategoryCode.md) | A Category Code |  no  |
| [HsdoTextObject](../classes/HsdoTextObject.md) | A text file |  no  |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |
| [HsdoAudience](../classes/HsdoAudience.md) | Intended audience for an item, i |  no  |
| [HsdoContactPoint](../classes/HsdoContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoWebPage](../classes/HsdoWebPage.md)&nbsp;or&nbsp;<br />[HsdoPlace](../classes/HsdoPlace.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[HsdoService](../classes/HsdoService.md)&nbsp;or&nbsp;<br />[HsdoTextObject](../classes/HsdoTextObject.md)&nbsp;or&nbsp;<br />[HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md)&nbsp;or&nbsp;<br />[HsdoOrganization](../classes/HsdoOrganization.md)&nbsp;or&nbsp;<br />[ProvActivity](../classes/ProvActivity.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)&nbsp;or&nbsp;<br />[HsdoContactPoint](../classes/HsdoContactPoint.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_Audience → prov_Entity | dreamkg:category/audience/YoungAdults | prov:wasInfluencedBy | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_Audience → uri | dreamkg:category/audience/AbuseOrNeglectSurvivors | prov:wasInfluencedBy | dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv |
| hsdo_Audience → prov_Activity | dreamkg:category/audience/YoungAdults | prov:wasInfluencedBy | dreamkg:process/run/ontop-CM |
| hsdo_CategoryCode → prov_Entity | dreamkg:category/service/other/WeatherRelief | prov:wasInfluencedBy | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_CategoryCode → uri | dreamkg:category/availability/Available | prov:wasInfluencedBy | dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv |
| hsdo_CategoryCode → prov_Activity | dreamkg:category/service/other/WeatherRelief | prov:wasInfluencedBy | dreamkg:process/run/ontop-CM |
| prov_Collection → hsdo_Service | dreamkg:file/kg.ttl | prov:wasInfluencedBy | dreamkg:service/6710596967858176 |
| prov_Collection → prov_Entity | dreamkg:file/kg.ttl | prov:wasInfluencedBy | dreamkg:service/channel/P--6710596967858176 |
| prov_Collection → hsdo_TextObject | dreamkg:file/kg.ttl | prov:wasInfluencedBy | dreamkg:service/desc/6710596967858176 |
| prov_Collection → hsdo_OpeningHoursSpecification | dreamkg:file/kg.ttl | prov:wasInfluencedBy | dreamkg:service/hours/wednesday/6710596967858176 |
| prov_Collection → hsdo_Place | dreamkg:file/kg.ttl | prov:wasInfluencedBy | dreamkg:service/location/6710596967858176 |
| prov_Collection → hsdo_ContactPoint | dreamkg:file/kg.ttl | prov:wasInfluencedBy | dreamkg:service/phone/6710596967858176 |
| prov_Collection → hsdo_Organization | dreamkg:file/kg.ttl | prov:wasInfluencedBy | dreamkg:service/provider/6710596967858176 |
| prov_Collection → hsdo_WebPage | dreamkg:outside/ab | prov:wasInfluencedBy | https://www.auntbertha.com//youth-service%252C-inc--philadelphia-pa--youth-emergency-service-%2528yes%2529/5680777996009472 |
| hsdo_Service → prov_Entity | dreamkg:service/6710596967858176 | prov:wasInfluencedBy | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_Service → prov_Activity | dreamkg:service/6710596967858176 | prov:wasInfluencedBy | dreamkg:process/run/ontop-CM |
| hsdo_Service → hsdo_WebPage | dreamkg:service/6710596967858176 | prov:wasInfluencedBy | https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176 |
| prov_Entity → prov_Entity | dreamkg:service/channel/P--6710596967858176 | prov:wasInfluencedBy | dreamkg:file/IJCAI/mappings/ontology.obda |
| prov_Entity → prov_Activity | dreamkg:service/channel/P--6710596967858176 | prov:wasInfluencedBy | dreamkg:process/run/ontop-CM |
| prov_Entity → hsdo_WebPage | dreamkg:service/channel/P--6710596967858176 | prov:wasInfluencedBy | https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176 |
| hsdo_TextObject → prov_Entity | dreamkg:service/desc/6710596967858176 | prov:wasInfluencedBy | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_TextObject → prov_Activity | dreamkg:service/desc/6710596967858176 | prov:wasInfluencedBy | dreamkg:process/run/ontop-CM |
| hsdo_TextObject → hsdo_WebPage | dreamkg:service/desc/6710596967858176 | prov:wasInfluencedBy | https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176 |
| hsdo_OpeningHoursSpecification → prov_Entity | dreamkg:service/hours/wednesday/6710596967858176 | prov:wasInfluencedBy | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_OpeningHoursSpecification → prov_Activity | dreamkg:service/hours/wednesday/6710596967858176 | prov:wasInfluencedBy | dreamkg:process/run/ontop-CM |
| hsdo_OpeningHoursSpecification → hsdo_WebPage | dreamkg:service/hours/wednesday/6710596967858176 | prov:wasInfluencedBy | https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176 |
| hsdo_Place → prov_Entity | dreamkg:service/location/6710596967858176 | prov:wasInfluencedBy | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_Place → prov_Activity | dreamkg:service/location/6710596967858176 | prov:wasInfluencedBy | dreamkg:process/run/ontop-CM |
| hsdo_Place → hsdo_WebPage | dreamkg:service/location/6710596967858176 | prov:wasInfluencedBy | https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176 |
| hsdo_ContactPoint → prov_Entity | dreamkg:service/phone/6710596967858176 | prov:wasInfluencedBy | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_ContactPoint → prov_Activity | dreamkg:service/phone/6710596967858176 | prov:wasInfluencedBy | dreamkg:process/run/ontop-CM |
| hsdo_ContactPoint → hsdo_WebPage | dreamkg:service/phone/6710596967858176 | prov:wasInfluencedBy | https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176 |
| hsdo_Organization → prov_Entity | dreamkg:service/provider/6710596967858176 | prov:wasInfluencedBy | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_Organization → prov_Activity | dreamkg:service/provider/6710596967858176 | prov:wasInfluencedBy | dreamkg:process/run/ontop-CM |
| hsdo_Organization → hsdo_WebPage | dreamkg:service/provider/6710596967858176 | prov:wasInfluencedBy | https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176 |
| hsdo_AdministrativeArea → prov_Entity | dreamkg:zip/19320 | prov:wasInfluencedBy | dreamkg:file/IJCAI/mappings/ontology.obda |
| hsdo_AdministrativeArea → uri | dreamkg:zip/17602 | prov:wasInfluencedBy | dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv |
| hsdo_AdministrativeArea → prov_Activity | dreamkg:zip/19320 | prov:wasInfluencedBy | dreamkg:process/run/ontop-CM |


## Comments

* 162 occurrences with subject type hsdo_Audience and object type prov_Entity.
* 243 occurrences with subject type hsdo_Audience and object type uri.
* 81 occurrences with subject type hsdo_Audience and object type prov_Activity.
* 314 occurrences with subject type hsdo_CategoryCode and object type prov_Entity.
* 471 occurrences with subject type hsdo_CategoryCode and object type uri.
* 157 occurrences with subject type hsdo_CategoryCode and object type prov_Activity.
* 87 occurrences with subject type prov_Collection and object type hsdo_Service.
* 174 occurrences with subject type prov_Collection and object type prov_Entity.
* 87 occurrences with subject type prov_Collection and object type hsdo_TextObject.
* 609 occurrences with subject type prov_Collection and object type hsdo_OpeningHoursSpecification.
* 87 occurrences with subject type prov_Collection and object type hsdo_Place.
* 87 occurrences with subject type prov_Collection and object type hsdo_ContactPoint.
* 87 occurrences with subject type prov_Collection and object type hsdo_Organization.
* 87 occurrences with subject type prov_Collection and object type hsdo_WebPage.
* 174 occurrences with subject type hsdo_Service and object type prov_Entity.
* 87 occurrences with subject type hsdo_Service and object type prov_Activity.
* 87 occurrences with subject type hsdo_Service and object type hsdo_WebPage.
* 348 occurrences with subject type prov_Entity and object type prov_Entity.
* 174 occurrences with subject type prov_Entity and object type prov_Activity.
* 174 occurrences with subject type prov_Entity and object type hsdo_WebPage.
* 174 occurrences with subject type hsdo_TextObject and object type prov_Entity.
* 87 occurrences with subject type hsdo_TextObject and object type prov_Activity.
* 87 occurrences with subject type hsdo_TextObject and object type hsdo_WebPage.
* 1218 occurrences with subject type hsdo_OpeningHoursSpecification and object type prov_Entity.
* 609 occurrences with subject type hsdo_OpeningHoursSpecification and object type prov_Activity.
* 609 occurrences with subject type hsdo_OpeningHoursSpecification and object type hsdo_WebPage.
* 174 occurrences with subject type hsdo_Place and object type prov_Entity.
* 87 occurrences with subject type hsdo_Place and object type prov_Activity.
* 87 occurrences with subject type hsdo_Place and object type hsdo_WebPage.
* 174 occurrences with subject type hsdo_ContactPoint and object type prov_Entity.
* 87 occurrences with subject type hsdo_ContactPoint and object type prov_Activity.
* 87 occurrences with subject type hsdo_ContactPoint and object type hsdo_WebPage.
* 174 occurrences with subject type hsdo_Organization and object type prov_Entity.
* 87 occurrences with subject type hsdo_Organization and object type prov_Activity.
* 87 occurrences with subject type hsdo_Organization and object type hsdo_WebPage.
* 78 occurrences with subject type hsdo_AdministrativeArea and object type prov_Entity.
* 117 occurrences with subject type hsdo_AdministrativeArea and object type uri.
* 39 occurrences with subject type hsdo_AdministrativeArea and object type prov_Activity.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:wasInfluencedBy |
| native | dream-kg/:prov_wasInfluencedBy |




## LinkML Source

<details>
```yaml
name: prov_wasInfluencedBy
description: No slot (predicate) description specified
comments:
- 162 occurrences with subject type hsdo_Audience and object type prov_Entity.
- 243 occurrences with subject type hsdo_Audience and object type uri.
- 81 occurrences with subject type hsdo_Audience and object type prov_Activity.
- 314 occurrences with subject type hsdo_CategoryCode and object type prov_Entity.
- 471 occurrences with subject type hsdo_CategoryCode and object type uri.
- 157 occurrences with subject type hsdo_CategoryCode and object type prov_Activity.
- 87 occurrences with subject type prov_Collection and object type hsdo_Service.
- 174 occurrences with subject type prov_Collection and object type prov_Entity.
- 87 occurrences with subject type prov_Collection and object type hsdo_TextObject.
- 609 occurrences with subject type prov_Collection and object type hsdo_OpeningHoursSpecification.
- 87 occurrences with subject type prov_Collection and object type hsdo_Place.
- 87 occurrences with subject type prov_Collection and object type hsdo_ContactPoint.
- 87 occurrences with subject type prov_Collection and object type hsdo_Organization.
- 87 occurrences with subject type prov_Collection and object type hsdo_WebPage.
- 174 occurrences with subject type hsdo_Service and object type prov_Entity.
- 87 occurrences with subject type hsdo_Service and object type prov_Activity.
- 87 occurrences with subject type hsdo_Service and object type hsdo_WebPage.
- 348 occurrences with subject type prov_Entity and object type prov_Entity.
- 174 occurrences with subject type prov_Entity and object type prov_Activity.
- 174 occurrences with subject type prov_Entity and object type hsdo_WebPage.
- 174 occurrences with subject type hsdo_TextObject and object type prov_Entity.
- 87 occurrences with subject type hsdo_TextObject and object type prov_Activity.
- 87 occurrences with subject type hsdo_TextObject and object type hsdo_WebPage.
- 1218 occurrences with subject type hsdo_OpeningHoursSpecification and object type
  prov_Entity.
- 609 occurrences with subject type hsdo_OpeningHoursSpecification and object type
  prov_Activity.
- 609 occurrences with subject type hsdo_OpeningHoursSpecification and object type
  hsdo_WebPage.
- 174 occurrences with subject type hsdo_Place and object type prov_Entity.
- 87 occurrences with subject type hsdo_Place and object type prov_Activity.
- 87 occurrences with subject type hsdo_Place and object type hsdo_WebPage.
- 174 occurrences with subject type hsdo_ContactPoint and object type prov_Entity.
- 87 occurrences with subject type hsdo_ContactPoint and object type prov_Activity.
- 87 occurrences with subject type hsdo_ContactPoint and object type hsdo_WebPage.
- 174 occurrences with subject type hsdo_Organization and object type prov_Entity.
- 87 occurrences with subject type hsdo_Organization and object type prov_Activity.
- 87 occurrences with subject type hsdo_Organization and object type hsdo_WebPage.
- 78 occurrences with subject type hsdo_AdministrativeArea and object type prov_Entity.
- 117 occurrences with subject type hsdo_AdministrativeArea and object type uri.
- 39 occurrences with subject type hsdo_AdministrativeArea and object type prov_Activity.
examples:
- description: hsdo_Audience → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/audience/YoungAdults
    example_subject_type: hsdo_Audience
- description: hsdo_Audience → uri
  object:
    example_object: dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv
    example_object_type: uri
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_subject_type: hsdo_Audience
- description: hsdo_Audience → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/audience/YoungAdults
    example_subject_type: hsdo_Audience
- description: hsdo_CategoryCode → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/service/other/WeatherRelief
    example_subject_type: hsdo_CategoryCode
- description: hsdo_CategoryCode → uri
  object:
    example_object: dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv
    example_object_type: uri
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/availability/Available
    example_subject_type: hsdo_CategoryCode
- description: hsdo_CategoryCode → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/service/other/WeatherRelief
    example_subject_type: hsdo_CategoryCode
- description: prov_Collection → hsdo_Service
  object:
    example_object: dreamkg:service/6710596967858176
    example_object_type: hsdo_Service
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → prov_Entity
  object:
    example_object: dreamkg:service/channel/P--6710596967858176
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_TextObject
  object:
    example_object: dreamkg:service/desc/6710596967858176
    example_object_type: hsdo_TextObject
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_OpeningHoursSpecification
  object:
    example_object: dreamkg:service/hours/wednesday/6710596967858176
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_Place
  object:
    example_object: dreamkg:service/location/6710596967858176
    example_object_type: hsdo_Place
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_ContactPoint
  object:
    example_object: dreamkg:service/phone/6710596967858176
    example_object_type: hsdo_ContactPoint
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_Organization
  object:
    example_object: dreamkg:service/provider/6710596967858176
    example_object_type: hsdo_Organization
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_WebPage
  object:
    example_object: https://www.auntbertha.com//youth-service%252C-inc--philadelphia-pa--youth-emergency-service-%2528yes%2529/5680777996009472
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:outside/ab
    example_subject_type: prov_Collection
- description: hsdo_Service → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/6710596967858176
    example_subject_type: hsdo_Service
- description: hsdo_Service → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/6710596967858176
    example_subject_type: hsdo_Service
- description: hsdo_Service → hsdo_WebPage
  object:
    example_object: https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/6710596967858176
    example_subject_type: hsdo_Service
- description: prov_Entity → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/channel/P--6710596967858176
    example_subject_type: prov_Entity
- description: prov_Entity → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/channel/P--6710596967858176
    example_subject_type: prov_Entity
- description: prov_Entity → hsdo_WebPage
  object:
    example_object: https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/channel/P--6710596967858176
    example_subject_type: prov_Entity
- description: hsdo_TextObject → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/desc/6710596967858176
    example_subject_type: hsdo_TextObject
- description: hsdo_TextObject → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/desc/6710596967858176
    example_subject_type: hsdo_TextObject
- description: hsdo_TextObject → hsdo_WebPage
  object:
    example_object: https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/desc/6710596967858176
    example_subject_type: hsdo_TextObject
- description: hsdo_OpeningHoursSpecification → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/hours/wednesday/6710596967858176
    example_subject_type: hsdo_OpeningHoursSpecification
- description: hsdo_OpeningHoursSpecification → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/hours/wednesday/6710596967858176
    example_subject_type: hsdo_OpeningHoursSpecification
- description: hsdo_OpeningHoursSpecification → hsdo_WebPage
  object:
    example_object: https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/hours/wednesday/6710596967858176
    example_subject_type: hsdo_OpeningHoursSpecification
- description: hsdo_Place → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/location/6710596967858176
    example_subject_type: hsdo_Place
- description: hsdo_Place → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/location/6710596967858176
    example_subject_type: hsdo_Place
- description: hsdo_Place → hsdo_WebPage
  object:
    example_object: https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/location/6710596967858176
    example_subject_type: hsdo_Place
- description: hsdo_ContactPoint → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/phone/6710596967858176
    example_subject_type: hsdo_ContactPoint
- description: hsdo_ContactPoint → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/phone/6710596967858176
    example_subject_type: hsdo_ContactPoint
- description: hsdo_ContactPoint → hsdo_WebPage
  object:
    example_object: https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/phone/6710596967858176
    example_subject_type: hsdo_ContactPoint
- description: hsdo_Organization → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/provider/6710596967858176
    example_subject_type: hsdo_Organization
- description: hsdo_Organization → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/provider/6710596967858176
    example_subject_type: hsdo_Organization
- description: hsdo_Organization → hsdo_WebPage
  object:
    example_object: https://www.auntbertha.com//the-veterans-group--philadelphia-pa--men%2527s-shelter/6710596967858176
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/provider/6710596967858176
    example_subject_type: hsdo_Organization
- description: hsdo_AdministrativeArea → prov_Entity
  object:
    example_object: dreamkg:file/IJCAI/mappings/ontology.obda
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:zip/19320
    example_subject_type: hsdo_AdministrativeArea
- description: hsdo_AdministrativeArea → uri
  object:
    example_object: dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv
    example_object_type: uri
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:zip/17602
    example_subject_type: hsdo_AdministrativeArea
- description: hsdo_AdministrativeArea → prov_Activity
  object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:zip/19320
    example_subject_type: hsdo_AdministrativeArea
from_schema: dream-kg
rank: 1000
slot_uri: prov:wasInfluencedBy
alias: prov_wasInfluencedBy
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
- prov_Collection
- prov_Entity
range: Any
any_of:
- range: hsdo_WebPage
- range: hsdo_Place
- range: uri
- range: hsdo_Service
- range: hsdo_TextObject
- range: hsdo_OpeningHoursSpecification
- range: hsdo_Organization
- range: prov_Activity
- range: prov_Entity
- range: hsdo_ContactPoint

```
</details>