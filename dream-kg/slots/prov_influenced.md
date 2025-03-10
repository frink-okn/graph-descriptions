

# Slot: prov_influenced


_No slot (predicate) description specified_






This slot occurs 7839 times.


URI: [prov:influenced](http://www.w3.org/ns/prov#influenced)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoContactPoint](../classes/HsdoContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department |  yes  |
| [HsdoTextObject](../classes/HsdoTextObject.md) | No class (type) description specified |  yes  |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |
| [ProvActivity](../classes/ProvActivity.md) | No class (type) description specified |  yes  |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  yes  |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |
| [HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place o... |  yes  |
| [HsdoWebPage](../classes/HsdoWebPage.md) | A web page |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoCategoryCode](../classes/HsdoCategoryCode.md)&nbsp;or&nbsp;<br />[HsdoAudience](../classes/HsdoAudience.md)&nbsp;or&nbsp;<br />[HsdoPlace](../classes/HsdoPlace.md)&nbsp;or&nbsp;<br />[HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md)&nbsp;or&nbsp;<br />[HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md)&nbsp;or&nbsp;<br />[ProvCollection](../classes/ProvCollection.md)&nbsp;or&nbsp;<br />[HsdoService](../classes/HsdoService.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)&nbsp;or&nbsp;<br />[HsdoOrganization](../classes/HsdoOrganization.md)&nbsp;or&nbsp;<br />[HsdoContactPoint](../classes/HsdoContactPoint.md)&nbsp;or&nbsp;<br />[HsdoTextObject](../classes/HsdoTextObject.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | hsdo_Audience | dreamkg:data/sql | dreamkg:category/audience/AbuseOrNeglectSurvivors | 162 |
| prov_Entity | prov_Entity | dreamkg:data/sql | dreamkg:category/audience/AbuseOrNeglectSurvivors | 5513 |
| prov_Entity | hsdo_CategoryCode | dreamkg:data/sql | dreamkg:category/availability/Available | 314 |
| prov_Entity | hsdo_Service | dreamkg:data/sql | dreamkg:service/4542572480692224 | 261 |
| prov_Entity | hsdo_TextObject | dreamkg:data/sql | dreamkg:service/desc/4542572480692224 | 261 |
| prov_Entity | hsdo_OpeningHoursSpecification | dreamkg:data/sql | dreamkg:service/hours/friday/4542572480692224 | 1827 |
| prov_Entity | hsdo_Place | dreamkg:data/sql | dreamkg:service/location/4542572480692224 | 261 |
| prov_Entity | hsdo_ContactPoint | dreamkg:data/sql | dreamkg:service/phone/4542572480692224 | 261 |
| prov_Entity | hsdo_Organization | dreamkg:data/sql | dreamkg:service/provider/4542572480692224 | 261 |
| prov_Entity | hsdo_AdministrativeArea | dreamkg:data/sql | dreamkg:zip/17602 | 78 |
| None | hsdo_Audience | dreamkg:file/AuntBertha/UpToDateVersions/Final_Temporary_Shelter_20240109.csv | dreamkg:category/audience/YoungAdults | 243 |
| None | prov_Entity | dreamkg:file/AuntBertha/UpToDateVersions/Final_Temporary_Shelter_20240109.csv | dreamkg:zip/19320 | 831 |
| None | hsdo_CategoryCode | dreamkg:file/AuntBertha/UpToDateVersions/Final_Temporary_Shelter_20240109.csv | dreamkg:category/service/other/WeatherRelief | 471 |
| None | hsdo_AdministrativeArea | dreamkg:file/AuntBertha/UpToDateVersions/Final_Temporary_Shelter_20240109.csv | dreamkg:zip/19320 | 117 |
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
| prov_Entity | prov_Collection | dreamkg:service/4542572480692224 | dreamkg:file/kg.ttl | 1305 |
| hsdo_Service | prov_Entity | dreamkg:service/4542572480692224 | dreamkg:file/kg.ttl | 87 |
| hsdo_Service | prov_Collection | dreamkg:service/4542572480692224 | dreamkg:file/kg.ttl | 87 |
| hsdo_TextObject | prov_Entity | dreamkg:service/desc/4542572480692224 | dreamkg:file/kg.ttl | 87 |
| hsdo_TextObject | prov_Collection | dreamkg:service/desc/4542572480692224 | dreamkg:file/kg.ttl | 87 |
| hsdo_OpeningHoursSpecification | prov_Entity | dreamkg:service/hours/friday/4542572480692224 | dreamkg:file/kg.ttl | 609 |
| hsdo_OpeningHoursSpecification | prov_Collection | dreamkg:service/hours/friday/4542572480692224 | dreamkg:file/kg.ttl | 609 |
| hsdo_Place | prov_Entity | dreamkg:service/location/4542572480692224 | dreamkg:file/kg.ttl | 87 |
| hsdo_Place | prov_Collection | dreamkg:service/location/4542572480692224 | dreamkg:file/kg.ttl | 87 |
| hsdo_ContactPoint | prov_Entity | dreamkg:service/phone/4542572480692224 | dreamkg:file/kg.ttl | 87 |
| hsdo_ContactPoint | prov_Collection | dreamkg:service/phone/4542572480692224 | dreamkg:file/kg.ttl | 87 |
| hsdo_Organization | prov_Entity | dreamkg:service/provider/4542572480692224 | dreamkg:file/kg.ttl | 87 |
| hsdo_Organization | prov_Collection | dreamkg:service/provider/4542572480692224 | dreamkg:file/kg.ttl | 87 |
| hsdo_WebPage | prov_Entity | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | dreamkg:outside/ab | 1305 |
| hsdo_WebPage | prov_Collection | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | dreamkg:outside/ab | 87 |
| hsdo_WebPage | hsdo_Service | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | dreamkg:service/5792020391002112 | 87 |
| hsdo_WebPage | hsdo_TextObject | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | dreamkg:service/desc/5792020391002112 | 87 |
| hsdo_WebPage | hsdo_OpeningHoursSpecification | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | dreamkg:service/hours/friday/5792020391002112 | 609 |
| hsdo_WebPage | hsdo_Place | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | dreamkg:service/location/5792020391002112 | 87 |
| hsdo_WebPage | hsdo_ContactPoint | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | dreamkg:service/phone/5792020391002112 | 87 |
| hsdo_WebPage | hsdo_Organization | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | dreamkg:service/provider/5792020391002112 | 87 |




## LinkML Source

<details>

```yaml
name: prov_influenced
annotations:
  count:
    tag: count
    value: 7839
  hsdo_AdministrativeArea:
    tag: hsdo_AdministrativeArea
    value: 117
  hsdo_Audience:
    tag: hsdo_Audience
    value: 243
  hsdo_CategoryCode:
    tag: hsdo_CategoryCode
    value: 471
  prov_Entity:
    tag: prov_Entity
    value: 831
description: No slot (predicate) description specified
examples:
- object:
    example_object: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_object_type: hsdo_Audience
    example_predicate: prov:influenced
    example_subject: dreamkg:data/sql
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_object_type: prov_Entity
    example_predicate: prov:influenced
    example_subject: dreamkg:data/sql
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:category/availability/Available
    example_object_type: hsdo_CategoryCode
    example_predicate: prov:influenced
    example_subject: dreamkg:data/sql
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/4542572480692224
    example_object_type: hsdo_Service
    example_predicate: prov:influenced
    example_subject: dreamkg:data/sql
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/desc/4542572480692224
    example_object_type: hsdo_TextObject
    example_predicate: prov:influenced
    example_subject: dreamkg:data/sql
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/hours/friday/4542572480692224
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: prov:influenced
    example_subject: dreamkg:data/sql
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/location/4542572480692224
    example_object_type: hsdo_Place
    example_predicate: prov:influenced
    example_subject: dreamkg:data/sql
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/phone/4542572480692224
    example_object_type: hsdo_ContactPoint
    example_predicate: prov:influenced
    example_subject: dreamkg:data/sql
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/provider/4542572480692224
    example_object_type: hsdo_Organization
    example_predicate: prov:influenced
    example_subject: dreamkg:data/sql
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:zip/17602
    example_object_type: hsdo_AdministrativeArea
    example_predicate: prov:influenced
    example_subject: dreamkg:data/sql
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:category/audience/YoungAdults
    example_object_type: hsdo_Audience
    example_predicate: prov:influenced
    example_subject: dreamkg:file/AuntBertha/UpToDateVersions/Final_Temporary_Shelter_20240109.csv
    example_subject_type: None
- object:
    example_object: dreamkg:zip/19320
    example_object_type: prov_Entity
    example_predicate: prov:influenced
    example_subject: dreamkg:file/AuntBertha/UpToDateVersions/Final_Temporary_Shelter_20240109.csv
    example_subject_type: None
- object:
    example_object: dreamkg:category/service/other/WeatherRelief
    example_object_type: hsdo_CategoryCode
    example_predicate: prov:influenced
    example_subject: dreamkg:file/AuntBertha/UpToDateVersions/Final_Temporary_Shelter_20240109.csv
    example_subject_type: None
- object:
    example_object: dreamkg:zip/19320
    example_object_type: hsdo_AdministrativeArea
    example_predicate: prov:influenced
    example_subject: dreamkg:file/AuntBertha/UpToDateVersions/Final_Temporary_Shelter_20240109.csv
    example_subject_type: None
- object:
    example_object: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_object_type: hsdo_Audience
    example_predicate: prov:influenced
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_object_type: prov_Entity
    example_predicate: prov:influenced
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:category/availability/Available
    example_object_type: hsdo_CategoryCode
    example_predicate: prov:influenced
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/4542572480692224
    example_object_type: hsdo_Service
    example_predicate: prov:influenced
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/desc/4542572480692224
    example_object_type: hsdo_TextObject
    example_predicate: prov:influenced
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/hours/friday/4542572480692224
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: prov:influenced
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/location/4542572480692224
    example_object_type: hsdo_Place
    example_predicate: prov:influenced
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/phone/4542572480692224
    example_object_type: hsdo_ContactPoint
    example_predicate: prov:influenced
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:service/provider/4542572480692224
    example_object_type: hsdo_Organization
    example_predicate: prov:influenced
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:zip/17602
    example_object_type: hsdo_AdministrativeArea
    example_predicate: prov:influenced
    example_subject: dreamkg:process/run/ontop-CM
    example_subject_type: prov_Activity
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Collection
    example_predicate: prov:influenced
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Entity
    example_predicate: prov:influenced
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Collection
    example_predicate: prov:influenced
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Entity
    example_predicate: prov:influenced
    example_subject: dreamkg:service/desc/4542572480692224
    example_subject_type: hsdo_TextObject
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Collection
    example_predicate: prov:influenced
    example_subject: dreamkg:service/desc/4542572480692224
    example_subject_type: hsdo_TextObject
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Entity
    example_predicate: prov:influenced
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: hsdo_OpeningHoursSpecification
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Collection
    example_predicate: prov:influenced
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: hsdo_OpeningHoursSpecification
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Entity
    example_predicate: prov:influenced
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Collection
    example_predicate: prov:influenced
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Entity
    example_predicate: prov:influenced
    example_subject: dreamkg:service/phone/4542572480692224
    example_subject_type: hsdo_ContactPoint
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Collection
    example_predicate: prov:influenced
    example_subject: dreamkg:service/phone/4542572480692224
    example_subject_type: hsdo_ContactPoint
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Entity
    example_predicate: prov:influenced
    example_subject: dreamkg:service/provider/4542572480692224
    example_subject_type: hsdo_Organization
- object:
    example_object: dreamkg:file/kg.ttl
    example_object_type: prov_Collection
    example_predicate: prov:influenced
    example_subject: dreamkg:service/provider/4542572480692224
    example_subject_type: hsdo_Organization
- object:
    example_object: dreamkg:outside/ab
    example_object_type: prov_Entity
    example_predicate: prov:influenced
    example_subject: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
    example_subject_type: hsdo_WebPage
- object:
    example_object: dreamkg:outside/ab
    example_object_type: prov_Collection
    example_predicate: prov:influenced
    example_subject: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
    example_subject_type: hsdo_WebPage
- object:
    example_object: dreamkg:service/5792020391002112
    example_object_type: hsdo_Service
    example_predicate: prov:influenced
    example_subject: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
    example_subject_type: hsdo_WebPage
- object:
    example_object: dreamkg:service/desc/5792020391002112
    example_object_type: hsdo_TextObject
    example_predicate: prov:influenced
    example_subject: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
    example_subject_type: hsdo_WebPage
- object:
    example_object: dreamkg:service/hours/friday/5792020391002112
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: prov:influenced
    example_subject: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
    example_subject_type: hsdo_WebPage
- object:
    example_object: dreamkg:service/location/5792020391002112
    example_object_type: hsdo_Place
    example_predicate: prov:influenced
    example_subject: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
    example_subject_type: hsdo_WebPage
- object:
    example_object: dreamkg:service/phone/5792020391002112
    example_object_type: hsdo_ContactPoint
    example_predicate: prov:influenced
    example_subject: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
    example_subject_type: hsdo_WebPage
- object:
    example_object: dreamkg:service/provider/5792020391002112
    example_object_type: hsdo_Organization
    example_predicate: prov:influenced
    example_subject: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
    example_subject_type: hsdo_WebPage
from_schema: dream-kg
rank: 1000
slot_uri: prov:influenced
alias: prov_influenced
domain_of:
- hsdo_ContactPoint
- hsdo_OpeningHoursSpecification
- hsdo_Organization
- hsdo_Place
- hsdo_Service
- hsdo_TextObject
- hsdo_WebPage
- prov_Activity
- prov_Entity
range: Any
any_of:
- range: hsdo_CategoryCode
- range: hsdo_Audience
- range: hsdo_Place
- range: hsdo_AdministrativeArea
- range: hsdo_OpeningHoursSpecification
- range: prov_Collection
- range: hsdo_Service
- range: prov_Entity
- range: hsdo_Organization
- range: hsdo_ContactPoint
- range: hsdo_TextObject

```
</details>