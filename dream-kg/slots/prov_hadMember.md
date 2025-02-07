

# Slot: prov_hadMember


_No slot (predicate) description specified_





URI: [prov:hadMember](http://www.w3.org/ns/prov#hadMember)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvCollection](../classes/ProvCollection.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)&nbsp;or&nbsp;<br />[HsdoContactPoint](../classes/HsdoContactPoint.md)&nbsp;or&nbsp;<br />[HsdoService](../classes/HsdoService.md)&nbsp;or&nbsp;<br />[HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md)&nbsp;or&nbsp;<br />[HsdoWebPage](../classes/HsdoWebPage.md)&nbsp;or&nbsp;<br />[HsdoTextObject](../classes/HsdoTextObject.md)&nbsp;or&nbsp;<br />[HsdoPlace](../classes/HsdoPlace.md)&nbsp;or&nbsp;<br />[HsdoOrganization](../classes/HsdoOrganization.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| prov_Collection → hsdo_Service | dreamkg:file/kg.ttl | prov:hadMember | dreamkg:service/6710596967858176 |
| prov_Collection → prov_Entity | dreamkg:file/kg.ttl | prov:hadMember | dreamkg:service/channel/P--6710596967858176 |
| prov_Collection → hsdo_TextObject | dreamkg:file/kg.ttl | prov:hadMember | dreamkg:service/desc/6710596967858176 |
| prov_Collection → hsdo_OpeningHoursSpecification | dreamkg:file/kg.ttl | prov:hadMember | dreamkg:service/hours/wednesday/6710596967858176 |
| prov_Collection → hsdo_Place | dreamkg:file/kg.ttl | prov:hadMember | dreamkg:service/location/6710596967858176 |
| prov_Collection → hsdo_ContactPoint | dreamkg:file/kg.ttl | prov:hadMember | dreamkg:service/phone/6710596967858176 |
| prov_Collection → hsdo_Organization | dreamkg:file/kg.ttl | prov:hadMember | dreamkg:service/provider/6710596967858176 |
| prov_Collection → hsdo_WebPage | dreamkg:outside/ab | prov:hadMember | https://www.auntbertha.com//youth-service%252C-inc--philadelphia-pa--youth-emergency-service-%2528yes%2529/5680777996009472 |


## Comments

* 87 occurrences with subject type prov_Collection and object type hsdo_Service.
* 174 occurrences with subject type prov_Collection and object type prov_Entity.
* 87 occurrences with subject type prov_Collection and object type hsdo_TextObject.
* 609 occurrences with subject type prov_Collection and object type hsdo_OpeningHoursSpecification.
* 87 occurrences with subject type prov_Collection and object type hsdo_Place.
* 87 occurrences with subject type prov_Collection and object type hsdo_ContactPoint.
* 87 occurrences with subject type prov_Collection and object type hsdo_Organization.
* 87 occurrences with subject type prov_Collection and object type hsdo_WebPage.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:hadMember |
| native | dream-kg/:prov_hadMember |




## LinkML Source

<details>
```yaml
name: prov_hadMember
description: No slot (predicate) description specified
comments:
- 87 occurrences with subject type prov_Collection and object type hsdo_Service.
- 174 occurrences with subject type prov_Collection and object type prov_Entity.
- 87 occurrences with subject type prov_Collection and object type hsdo_TextObject.
- 609 occurrences with subject type prov_Collection and object type hsdo_OpeningHoursSpecification.
- 87 occurrences with subject type prov_Collection and object type hsdo_Place.
- 87 occurrences with subject type prov_Collection and object type hsdo_ContactPoint.
- 87 occurrences with subject type prov_Collection and object type hsdo_Organization.
- 87 occurrences with subject type prov_Collection and object type hsdo_WebPage.
examples:
- description: prov_Collection → hsdo_Service
  object:
    example_object: dreamkg:service/6710596967858176
    example_object_type: hsdo_Service
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → prov_Entity
  object:
    example_object: dreamkg:service/channel/P--6710596967858176
    example_object_type: prov_Entity
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_TextObject
  object:
    example_object: dreamkg:service/desc/6710596967858176
    example_object_type: hsdo_TextObject
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_OpeningHoursSpecification
  object:
    example_object: dreamkg:service/hours/wednesday/6710596967858176
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_Place
  object:
    example_object: dreamkg:service/location/6710596967858176
    example_object_type: hsdo_Place
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_ContactPoint
  object:
    example_object: dreamkg:service/phone/6710596967858176
    example_object_type: hsdo_ContactPoint
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_Organization
  object:
    example_object: dreamkg:service/provider/6710596967858176
    example_object_type: hsdo_Organization
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- description: prov_Collection → hsdo_WebPage
  object:
    example_object: https://www.auntbertha.com//youth-service%252C-inc--philadelphia-pa--youth-emergency-service-%2528yes%2529/5680777996009472
    example_object_type: hsdo_WebPage
    example_predicate: prov:hadMember
    example_subject: dreamkg:outside/ab
    example_subject_type: prov_Collection
from_schema: dream-kg
rank: 1000
slot_uri: prov:hadMember
alias: prov_hadMember
domain_of:
- prov_Collection
range: Any
any_of:
- range: prov_Entity
- range: hsdo_ContactPoint
- range: hsdo_Service
- range: hsdo_OpeningHoursSpecification
- range: hsdo_WebPage
- range: hsdo_TextObject
- range: hsdo_Place
- range: hsdo_Organization

```
</details>