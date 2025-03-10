

# Slot: prov_hadMember


_No slot (predicate) description specified_






This slot occurs 1305 times.


URI: [prov:hadMember](http://www.w3.org/ns/prov#hadMember)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |
| [ProvCollection](../classes/ProvCollection.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HsdoWebPage](../classes/HsdoWebPage.md)&nbsp;or&nbsp;<br />[HsdoPlace](../classes/HsdoPlace.md)&nbsp;or&nbsp;<br />[HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md)&nbsp;or&nbsp;<br />[HsdoService](../classes/HsdoService.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)&nbsp;or&nbsp;<br />[HsdoOrganization](../classes/HsdoOrganization.md)&nbsp;or&nbsp;<br />[HsdoContactPoint](../classes/HsdoContactPoint.md)&nbsp;or&nbsp;<br />[HsdoTextObject](../classes/HsdoTextObject.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | prov_Entity | dreamkg:file/kg.ttl | dreamkg:service/4542572480692224 | 1305 |
| prov_Entity | hsdo_Service | dreamkg:file/kg.ttl | dreamkg:service/4542572480692224 | 87 |
| prov_Collection | prov_Entity | dreamkg:file/kg.ttl | dreamkg:service/4542572480692224 | 1305 |
| prov_Collection | hsdo_Service | dreamkg:file/kg.ttl | dreamkg:service/4542572480692224 | 87 |
| prov_Entity | hsdo_TextObject | dreamkg:file/kg.ttl | dreamkg:service/desc/4542572480692224 | 87 |
| prov_Collection | hsdo_TextObject | dreamkg:file/kg.ttl | dreamkg:service/desc/4542572480692224 | 87 |
| prov_Entity | hsdo_OpeningHoursSpecification | dreamkg:file/kg.ttl | dreamkg:service/hours/friday/4542572480692224 | 609 |
| prov_Collection | hsdo_OpeningHoursSpecification | dreamkg:file/kg.ttl | dreamkg:service/hours/friday/4542572480692224 | 609 |
| prov_Entity | hsdo_Place | dreamkg:file/kg.ttl | dreamkg:service/location/4542572480692224 | 87 |
| prov_Collection | hsdo_Place | dreamkg:file/kg.ttl | dreamkg:service/location/4542572480692224 | 87 |
| prov_Entity | hsdo_ContactPoint | dreamkg:file/kg.ttl | dreamkg:service/phone/4542572480692224 | 87 |
| prov_Collection | hsdo_ContactPoint | dreamkg:file/kg.ttl | dreamkg:service/phone/4542572480692224 | 87 |
| prov_Entity | hsdo_Organization | dreamkg:file/kg.ttl | dreamkg:service/provider/4542572480692224 | 87 |
| prov_Collection | hsdo_Organization | dreamkg:file/kg.ttl | dreamkg:service/provider/4542572480692224 | 87 |
| prov_Entity | hsdo_WebPage | dreamkg:outside/ab | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | 87 |
| prov_Collection | hsdo_WebPage | dreamkg:outside/ab | https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112 | 87 |




## LinkML Source

<details>

```yaml
name: prov_hadMember
annotations:
  count:
    tag: count
    value: 1305
description: No slot (predicate) description specified
examples:
- object:
    example_object: dreamkg:service/4542572480692224
    example_object_type: prov_Entity
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/4542572480692224
    example_object_type: hsdo_Service
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/4542572480692224
    example_object_type: prov_Entity
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/4542572480692224
    example_object_type: hsdo_Service
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/desc/4542572480692224
    example_object_type: hsdo_TextObject
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/desc/4542572480692224
    example_object_type: hsdo_TextObject
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/hours/friday/4542572480692224
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/hours/friday/4542572480692224
    example_object_type: hsdo_OpeningHoursSpecification
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/location/4542572480692224
    example_object_type: hsdo_Place
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/location/4542572480692224
    example_object_type: hsdo_Place
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/phone/4542572480692224
    example_object_type: hsdo_ContactPoint
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/phone/4542572480692224
    example_object_type: hsdo_ContactPoint
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: dreamkg:service/provider/4542572480692224
    example_object_type: hsdo_Organization
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/provider/4542572480692224
    example_object_type: hsdo_Organization
    example_predicate: prov:hadMember
    example_subject: dreamkg:file/kg.ttl
    example_subject_type: prov_Collection
- object:
    example_object: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
    example_object_type: hsdo_WebPage
    example_predicate: prov:hadMember
    example_subject: dreamkg:outside/ab
    example_subject_type: prov_Entity
- object:
    example_object: https://www.auntbertha.com//achievement-through-counseling-and-treatment-%2528act-1%2529--philadelphia-pa--opioid-treatment-program-%2528otp%2529/5792020391002112
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
- prov_Entity
range: Any
any_of:
- range: hsdo_WebPage
- range: hsdo_Place
- range: hsdo_OpeningHoursSpecification
- range: hsdo_Service
- range: prov_Entity
- range: hsdo_Organization
- range: hsdo_ContactPoint
- range: hsdo_TextObject

```
</details>