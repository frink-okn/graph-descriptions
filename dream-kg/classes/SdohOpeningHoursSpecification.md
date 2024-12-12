

# Class: OpeningHoursSpecification (sdoh_OpeningHoursSpecification)


_A structured value providing information about the opening hours of a place or a certain service inside a place.\n\n_

_The place is __open__ if the [[opens]] property is specified, and __closed__ otherwise.\n\nIf the value for the [[closes]] property is less than the value for the [[opens]] property then the hour range is assumed to span over the next day._

_      _





URI: [sdoh:OpeningHoursSpecification](http://schema.org/OpeningHoursSpecification)






```mermaid
 classDiagram
    class SdohOpeningHoursSpecification
    click SdohOpeningHoursSpecification href "../SdohOpeningHoursSpecification"
      SdohOpeningHoursSpecification : sdoh_closes
        
          
    
    
    SdohOpeningHoursSpecification --> "0..1" String : sdoh_closes
    click String href "../String"

        
      SdohOpeningHoursSpecification : sdoh_dayOfWeek
        
          
    
    
    SdohOpeningHoursSpecification --> "0..1" String : sdoh_dayOfWeek
    click String href "../String"

        
      SdohOpeningHoursSpecification : sdoh_opens
        
          
    
    
    SdohOpeningHoursSpecification --> "0..1" String : sdoh_opens
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sdoh_closes](../slots/sdoh_closes.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [sdoh_opens](../slots/sdoh_opens.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [sdoh_dayOfWeek](../slots/sdoh_dayOfWeek.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohService](../classes/SdohService.md) | [sdoh_hoursAvailable](../slots/sdoh_hoursAvailable.md) | range | [SdohOpeningHoursSpecification](../classes/SdohOpeningHoursSpecification.md) |







## Examples

| Value |
| --- |
| dreamkg:service/hours/tuesday/5480325573640192 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:OpeningHoursSpecification |
| native | dream-kg/:SdohOpeningHoursSpecification |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_OpeningHoursSpecification
description: "A structured value providing information about the opening hours of\
  \ a place or a certain service inside a place.\\n\\n\nThe place is __open__ if the\
  \ [[opens]] property is specified, and __closed__ otherwise.\\n\\nIf the value for\
  \ the [[closes]] property is less than the value for the [[opens]] property then\
  \ the hour range is assumed to span over the next day.\n      "
title: OpeningHoursSpecification
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 609 occurences.
examples:
- value: dreamkg:service/hours/tuesday/5480325573640192
from_schema: dream-kg
rank: 1000
slots:
- sdoh_closes
- sdoh_opens
- sdoh_dayOfWeek
class_uri: sdoh:OpeningHoursSpecification

```
</details>

### Induced

<details>
```yaml
name: sdoh_OpeningHoursSpecification
description: "A structured value providing information about the opening hours of\
  \ a place or a certain service inside a place.\\n\\n\nThe place is __open__ if the\
  \ [[opens]] property is specified, and __closed__ otherwise.\\n\\nIf the value for\
  \ the [[closes]] property is less than the value for the [[opens]] property then\
  \ the hour range is assumed to span over the next day.\n      "
title: OpeningHoursSpecification
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 609 occurences.
examples:
- value: dreamkg:service/hours/tuesday/5480325573640192
from_schema: dream-kg
rank: 1000
attributes:
  sdoh_closes:
    name: sdoh_closes
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 623 occurrences with subject type sdoh_OpeningHoursSpecification and object
      type string.
    examples:
    - value: dreamkg:service/hours/tuesday/4666716061171712 sdoh:closes 17:00
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:closes
    alias: sdoh_closes
    owner: sdoh_OpeningHoursSpecification
    domain_of:
    - sdoh_OpeningHoursSpecification
    range: string
  sdoh_opens:
    name: sdoh_opens
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 631 occurrences with subject type sdoh_OpeningHoursSpecification and object
      type string.
    examples:
    - value: dreamkg:service/hours/wednesday/6101823548030976 sdoh:opens 07:00
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:opens
    alias: sdoh_opens
    owner: sdoh_OpeningHoursSpecification
    domain_of:
    - sdoh_OpeningHoursSpecification
    range: string
  sdoh_dayOfWeek:
    name: sdoh_dayOfWeek
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 609 occurrences with subject type sdoh_OpeningHoursSpecification and object
      type string.
    examples:
    - value: dreamkg:service/hours/saturday/5186727883833344 sdoh:dayOfWeek Saturday
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:dayOfWeek
    alias: sdoh_dayOfWeek
    owner: sdoh_OpeningHoursSpecification
    domain_of:
    - sdoh_OpeningHoursSpecification
    range: string
class_uri: sdoh:OpeningHoursSpecification

```
</details>