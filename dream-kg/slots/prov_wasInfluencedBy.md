

# Slot: prov_wasInfluencedBy


_No slot (predicate) description specified_






This slot occurs 7839 times.


URI: [prov:wasInfluencedBy](http://www.w3.org/ns/prov#wasInfluencedBy)



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
| [ProvCollection](../classes/ProvCollection.md) | No class (type) description specified |  yes  |
| [HsdoAudience](../classes/HsdoAudience.md) | Intended audience for an item, i |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |
| [HsdoTextObject](../classes/HsdoTextObject.md) | A text file |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoWebPage](../classes/HsdoWebPage.md)&nbsp;or&nbsp;<br />[HsdoTextObject](../classes/HsdoTextObject.md)&nbsp;or&nbsp;<br />[HsdoService](../classes/HsdoService.md)&nbsp;or&nbsp;<br />[HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md)&nbsp;or&nbsp;<br />[HsdoOrganization](../classes/HsdoOrganization.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)&nbsp;or&nbsp;<br />[ProvActivity](../classes/ProvActivity.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HsdoPlace](../classes/HsdoPlace.md)&nbsp;or&nbsp;<br />[HsdoContactPoint](../classes/HsdoContactPoint.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | prov_Entity | dreamkg:category/audience/AbuseOrNeglectSurvivors | dreamkg:data/sql | 5513 |
| hsdo_Audience | prov_Entity | dreamkg:category/audience/AbuseOrNeglectSurvivors | dreamkg:data/sql | 162 |
| prov_Entity | uri | dreamkg:category/audience/AbuseOrNeglectSurvivors | dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv | 831 |
| hsdo_Audience | uri | dreamkg:category/audience/AbuseOrNeglectSurvivors | dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv | 243 |
| prov_Entity | prov_Activity | dreamkg:category/audience/AbuseOrNeglectSurvivors | dreamkg:process/run/ontop-CM | 1495 |
| hsdo_Audience | prov_Activity | dreamkg:category/audience/AbuseOrNeglectSurvivors | dreamkg:process/run/ontop-CM | 81 |
| hsdo_CategoryCode | prov_Entity | dreamkg:category/availability/Available | dreamkg:data/sql | 314 |
| hsdo_CategoryCode | uri | dreamkg:category/availability/Available | dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv | 471 |
| hsdo_CategoryCode | prov_Activity | dreamkg:category/availability/Available | dreamkg:process/run/ontop-CM | 157 |
| prov_Collection | hsdo_Service | dreamkg:file/kg.ttl | dreamkg:service/4542572480692224 | 87 |
| prov_Collection | prov_Entity | dreamkg:file/kg.ttl | dreamkg:service/4542572480692224 | 1305 |
| prov_Entity | hsdo_Service | dreamkg:file/kg.ttl | dreamkg:service/4542572480692224 | 87 |
| prov_Collection | hsdo_TextObject | dreamkg:file/kg.ttl | dreamkg:service/desc/4542572480692224 | 87 |
| prov_Entity | hsdo_TextObject | dreamkg:file/kg.ttl | dreamkg:service/desc/4542572480692224 | 87 |
| prov_Collection | hsdo_OpeningHoursSpecification | dreamkg:file/kg.ttl | dreamkg:service/hours/friday/4542572480692224 | 609 |
| prov_Entity | hsdo_OpeningHoursSpecification | dreamkg:file/kg.ttl | dreamkg:service/hours/friday/4542572480692224 | 609 |
| prov_Collection | hsdo_Place | dreamkg:file/kg.ttl | dreamkg:service/location/4542572480692224 | 87 |
| prov_Entity | hsdo_Place | dreamkg:file/kg.ttl | dreamkg:service/location/4542572480692224 | 87 |
| prov_Collection | hsdo_ContactPoint | dreamkg:file/kg.ttl | dreamkg:service/phone/4542572480692224 | 87 |
| prov_Entity | hsdo_ContactPoint | dreamkg:file/kg.ttl | dreamkg:service/phone/4542572480692224 | 87 |
| prov_Collection | hsdo_Organization | dreamkg:file/kg.ttl | dreamkg:service/provider/4542572480692224 | 87 |
| prov_Entity | hsdo_Organization | dreamkg:file/kg.ttl | dreamkg:service/provider/4542572480692224 | 87 |
| prov_Collection | hsdo_WebPage | dreamkg:outside/ab | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | 87 |
| prov_Entity | hsdo_WebPage | dreamkg:outside/ab | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | 1305 |
| hsdo_Service | prov_Entity | dreamkg:service/4542572480692224 | dreamkg:data/sql | 261 |
| hsdo_Service | prov_Activity | dreamkg:service/4542572480692224 | dreamkg:process/run/ontop-CM | 87 |
| hsdo_Service | hsdo_WebPage | dreamkg:service/4542572480692224 | https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224 | 87 |
| hsdo_TextObject | prov_Entity | dreamkg:service/desc/4542572480692224 | dreamkg:data/sql | 261 |
| hsdo_TextObject | prov_Activity | dreamkg:service/desc/4542572480692224 | dreamkg:process/run/ontop-CM | 87 |
| hsdo_TextObject | hsdo_WebPage | dreamkg:service/desc/4542572480692224 | https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224 | 87 |
| hsdo_OpeningHoursSpecification | prov_Entity | dreamkg:service/hours/friday/4542572480692224 | dreamkg:data/sql | 1827 |
| hsdo_OpeningHoursSpecification | prov_Activity | dreamkg:service/hours/friday/4542572480692224 | dreamkg:process/run/ontop-CM | 609 |
| hsdo_OpeningHoursSpecification | hsdo_WebPage | dreamkg:service/hours/friday/4542572480692224 | https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224 | 609 |
| hsdo_Place | prov_Entity | dreamkg:service/location/4542572480692224 | dreamkg:data/sql | 261 |
| hsdo_Place | prov_Activity | dreamkg:service/location/4542572480692224 | dreamkg:process/run/ontop-CM | 87 |
| hsdo_Place | hsdo_WebPage | dreamkg:service/location/4542572480692224 | https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224 | 87 |
| hsdo_ContactPoint | prov_Entity | dreamkg:service/phone/4542572480692224 | dreamkg:data/sql | 261 |
| hsdo_ContactPoint | prov_Activity | dreamkg:service/phone/4542572480692224 | dreamkg:process/run/ontop-CM | 87 |
| hsdo_ContactPoint | hsdo_WebPage | dreamkg:service/phone/4542572480692224 | https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224 | 87 |
| hsdo_Organization | prov_Entity | dreamkg:service/provider/4542572480692224 | dreamkg:data/sql | 261 |
| hsdo_Organization | prov_Activity | dreamkg:service/provider/4542572480692224 | dreamkg:process/run/ontop-CM | 87 |
| hsdo_Organization | hsdo_WebPage | dreamkg:service/provider/4542572480692224 | https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224 | 87 |
| hsdo_AdministrativeArea | prov_Entity | dreamkg:zip/17602 | dreamkg:data/sql | 78 |
| hsdo_AdministrativeArea | uri | dreamkg:zip/17602 | dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv | 117 |
| hsdo_AdministrativeArea | prov_Activity | dreamkg:zip/17602 | dreamkg:process/run/ontop-CM | 39 |




## LinkML Source

<details>

```yaml
name: prov_wasInfluencedBy
annotations:
  count:
    tag: count
    value: 7839
description: No slot (predicate) description specified
examples:
- object:
    example_object: dreamkg:data/sql
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:data/sql
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_subject_type: hsdo_Audience
- object:
    example_object: dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv
    example_object_type: uri
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv
    example_object_type: uri
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_subject_type: hsdo_Audience
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/audience/AbuseOrNeglectSurvivors
    example_subject_type: hsdo_Audience
- object:
    example_object: dreamkg:data/sql
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/availability/Available
    example_subject_type: hsdo_CategoryCode
- object:
    example_object: dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv
    example_object_type: uri
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/availability/Available
    example_subject_type: hsdo_CategoryCode
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:category/availability/Available
    example_subject_type: hsdo_CategoryCode
- object:
    example_object: dreamkg:service/4542572480692224
    example_object_type: hsdo_Service
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/4542572480692224
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/4542572480692224
    example_object_type: hsdo_Service
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/desc/4542572480692224
    example_object_type: hsdo_TextObject
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/desc/4542572480692224
    example_object_type: hsdo_TextObject
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/hours/friday/4542572480692224
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/hours/friday/4542572480692224
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/location/4542572480692224
    example_object_type: hsdo_Place
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/location/4542572480692224
    example_object_type: hsdo_Place
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/phone/4542572480692224
    example_object_type: hsdo_ContactPoint
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/phone/4542572480692224
    example_object_type: hsdo_ContactPoint
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/provider/4542572480692224
    example_object_type: hsdo_Organization
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/provider/4542572480692224
    example_object_type: hsdo_Organization
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:outside/ab
    example_subject_type: prov_Collection
- object:
    example_object: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:outside/ab
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:data/sql
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: dreamkg:data/sql
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/desc/4542572480692224
    example_subject_type: hsdo_TextObject
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/desc/4542572480692224
    example_subject_type: hsdo_TextObject
- object:
    example_object: https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/desc/4542572480692224
    example_subject_type: hsdo_TextObject
- object:
    example_object: dreamkg:data/sql
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: hsdo_OpeningHoursSpecification
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: hsdo_OpeningHoursSpecification
- object:
    example_object: https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/hours/friday/4542572480692224
    example_subject_type: hsdo_OpeningHoursSpecification
- object:
    example_object: dreamkg:data/sql
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
- object:
    example_object: https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/location/4542572480692224
    example_subject_type: hsdo_Place
- object:
    example_object: dreamkg:data/sql
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/phone/4542572480692224
    example_subject_type: hsdo_ContactPoint
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/phone/4542572480692224
    example_subject_type: hsdo_ContactPoint
- object:
    example_object: https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/phone/4542572480692224
    example_subject_type: hsdo_ContactPoint
- object:
    example_object: dreamkg:data/sql
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/provider/4542572480692224
    example_subject_type: hsdo_Organization
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/provider/4542572480692224
    example_subject_type: hsdo_Organization
- object:
    example_object: https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224
    example_object_type: hsdo_WebPage
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:service/provider/4542572480692224
    example_subject_type: hsdo_Organization
- object:
    example_object: dreamkg:data/sql
    example_object_type: prov_Entity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:zip/17602
    example_subject_type: hsdo_AdministrativeArea
- object:
    example_object: dreamkg:file/AuntBertha/UpToDate/Versions/Final_Emergency_Food_20240109.csv
    example_object_type: uri
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:zip/17602
    example_subject_type: hsdo_AdministrativeArea
- object:
    example_object: dreamkg:process/run/ontop-CM
    example_object_type: prov_Activity
    example_predicate: prov:wasInfluencedBy
    example_subject: dreamkg:zip/17602
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
- range: hsdo_TextObject
- range: hsdo_Service
- range: hsdo_OpeningHoursSpecification
- range: hsdo_Organization
- range: prov_Entity
- range: prov_Activity
- range: uri
- range: hsdo_Place
- range: hsdo_ContactPoint

```
</details>