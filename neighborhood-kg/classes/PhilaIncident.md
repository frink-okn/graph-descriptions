

# Class: TODO -- what's a good name for this class (type)? (phila_Incident)


_TODO -- tell the world what this class (type) describes._





URI: [phila:Incident](https://metadata.phila.gov/Incident)






```mermaid
 classDiagram
    class PhilaIncident
    click PhilaIncident href "../PhilaIncident"
      PhilaIncident : phila_age_of
        
          
    
    
    PhilaIncident --> "0..1" Integer : phila_age_of
    click Integer href "../Integer"

        
      PhilaIncident : phila_date_of
        
          
    
    
    PhilaIncident --> "0..1" Date : phila_date_of
    click Date href "../Date"

        
      PhilaIncident : phila_happened_at
        
          
    
    
    PhilaIncident --> "0..1" PhilaCensusTract : phila_happened_at
    click PhilaCensusTract href "../PhilaCensusTract"

        
      PhilaIncident : phila_is_fatal
        
          
    
    
    PhilaIncident --> "0..1" Boolean : phila_is_fatal
    click Boolean href "../Boolean"

        
      PhilaIncident : phila_OffenderDeceased
        
          
    
    
    PhilaIncident --> "0..1" Boolean : phila_OffenderDeceased
    click Boolean href "../Boolean"

        
      PhilaIncident : phila_OffenderInjured
        
          
    
    
    PhilaIncident --> "0..1" Boolean : phila_OffenderInjured
    click Boolean href "../Boolean"

        
      PhilaIncident : phila_OffenderRace
        
          
    
    
    PhilaIncident --> "0..1" String : phila_OffenderRace
    click String href "../String"

        
      PhilaIncident : phila_OffenderSex
        
          
    
    
    PhilaIncident --> "0..1" String : phila_OffenderSex
    click String href "../String"

        
      PhilaIncident : phila_OffenderWound
        
          
    
    
    PhilaIncident --> "0..1" String : phila_OffenderWound
    click String href "../String"

        
      PhilaIncident : phila_OfficerInvolved
        
          
    
    
    PhilaIncident --> "0..1" Boolean : phila_OfficerInvolved
    click Boolean href "../Boolean"

        
      PhilaIncident : phila_time_of
        
          
    
    
    PhilaIncident --> "0..1" Time : phila_time_of
    click Time href "../Time"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [phila_OffenderInjured](../slots/phila_OffenderInjured.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) | TODO -- tell the world what this slot (predicate) describes | direct |
| [phila_age_of](../slots/phila_age_of.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | TODO -- tell the world what this slot (predicate) describes | direct |
| [phila_OffenderRace](../slots/phila_OffenderRace.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [phila_OfficerInvolved](../slots/phila_OfficerInvolved.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) | TODO -- tell the world what this slot (predicate) describes | direct |
| [phila_OffenderWound](../slots/phila_OffenderWound.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [phila_date_of](../slots/phila_date_of.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) | TODO -- tell the world what this slot (predicate) describes | direct |
| [phila_time_of](../slots/phila_time_of.md) | 0..1 <br/> [xsd:time](http://www.w3.org/2001/XMLSchema#time) | TODO -- tell the world what this slot (predicate) describes | direct |
| [phila_happened_at](../slots/phila_happened_at.md) | 0..1 <br/> [PhilaCensusTract](../classes/PhilaCensusTract.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [phila_OffenderSex](../slots/phila_OffenderSex.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [phila_OffenderDeceased](../slots/phila_OffenderDeceased.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) | TODO -- tell the world what this slot (predicate) describes | direct |
| [phila_is_fatal](../slots/phila_is_fatal.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) | TODO -- tell the world what this slot (predicate) describes | direct |









## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:Incident |
| native | neighborhood-kg/:PhilaIncident |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: phila_Incident
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 15328 occurences.
from_schema: neighborhood-kg
slots:
- phila_OffenderInjured
- phila_age_of
- phila_OffenderRace
- phila_OfficerInvolved
- phila_OffenderWound
- phila_date_of
- phila_time_of
- phila_happened_at
- phila_OffenderSex
- phila_OffenderDeceased
- phila_is_fatal
class_uri: phila:Incident

```
</details>

### Induced

<details>
```yaml
name: phila_Incident
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 15328 occurences.
from_schema: neighborhood-kg
attributes:
  phila_OffenderInjured:
    name: phila_OffenderInjured
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 15328 occurrences with subject type phila_Incident and object type boolean.
    examples:
    - value: phila:OBJ_11856539 phila:OffenderInjured false
    from_schema: neighborhood-kg
    rank: 1000
    slot_uri: phila:OffenderInjured
    alias: phila_OffenderInjured
    owner: phila_Incident
    domain_of:
    - phila_Incident
    range: boolean
  phila_age_of:
    name: phila_age_of
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 15093 occurrences with subject type phila_Incident and object type integer.
    examples:
    - value: phila:OBJ_11856539 phila:age_of 64
    from_schema: neighborhood-kg
    rank: 1000
    slot_uri: phila:age_of
    alias: phila_age_of
    owner: phila_Incident
    domain_of:
    - phila_Incident
    range: integer
  phila_OffenderRace:
    name: phila_OffenderRace
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 15205 occurrences with subject type phila_Incident and object type string.
    examples:
    - value: phila:OBJ_11856539 phila:OffenderRace B
    from_schema: neighborhood-kg
    rank: 1000
    slot_uri: phila:OffenderRace
    alias: phila_OffenderRace
    owner: phila_Incident
    domain_of:
    - phila_Incident
    range: string
  phila_OfficerInvolved:
    name: phila_OfficerInvolved
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 15328 occurrences with subject type phila_Incident and object type boolean.
    examples:
    - value: phila:OBJ_11856539 phila:OfficerInvolved false
    from_schema: neighborhood-kg
    rank: 1000
    slot_uri: phila:OfficerInvolved
    alias: phila_OfficerInvolved
    owner: phila_Incident
    domain_of:
    - phila_Incident
    range: boolean
  phila_OffenderWound:
    name: phila_OffenderWound
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 15200 occurrences with subject type phila_Incident and object type string.
    examples:
    - value: phila:OBJ_11856539 phila:OffenderWound Multiple
    from_schema: neighborhood-kg
    rank: 1000
    slot_uri: phila:OffenderWound
    alias: phila_OffenderWound
    owner: phila_Incident
    domain_of:
    - phila_Incident
    range: string
  phila_date_of:
    name: phila_date_of
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 15328 occurrences with subject type phila_Incident and object type date.
    examples:
    - value: phila:OBJ_11856539 phila:date_of 2022-12-21
    from_schema: neighborhood-kg
    rank: 1000
    slot_uri: phila:date_of
    alias: phila_date_of
    owner: phila_Incident
    domain_of:
    - phila_Incident
    range: date
  phila_time_of:
    name: phila_time_of
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 15205 occurrences with subject type phila_Incident and object type time.
    examples:
    - value: phila:OBJ_11856539 phila:time_of 00:13:00
    from_schema: neighborhood-kg
    rank: 1000
    slot_uri: phila:time_of
    alias: phila_time_of
    owner: phila_Incident
    domain_of:
    - phila_Incident
    range: time
  phila_happened_at:
    name: phila_happened_at
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 15328 occurrences with subject type phila_Incident and object type phila_CensusTract.
    examples:
    - value: phila:OBJ_11871866 phila:happened_at phila:CT_28902
    from_schema: neighborhood-kg
    rank: 1000
    slot_uri: phila:happened_at
    alias: phila_happened_at
    owner: phila_Incident
    domain_of:
    - phila_Incident
    range: phila_CensusTract
  phila_OffenderSex:
    name: phila_OffenderSex
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 15328 occurrences with subject type phila_Incident and object type string.
    examples:
    - value: phila:OBJ_11856539 phila:OffenderSex F
    from_schema: neighborhood-kg
    rank: 1000
    slot_uri: phila:OffenderSex
    alias: phila_OffenderSex
    owner: phila_Incident
    domain_of:
    - phila_Incident
    range: string
  phila_OffenderDeceased:
    name: phila_OffenderDeceased
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 15328 occurrences with subject type phila_Incident and object type boolean.
    examples:
    - value: phila:OBJ_11856539 phila:OffenderDeceased false
    from_schema: neighborhood-kg
    rank: 1000
    slot_uri: phila:OffenderDeceased
    alias: phila_OffenderDeceased
    owner: phila_Incident
    domain_of:
    - phila_Incident
    range: boolean
  phila_is_fatal:
    name: phila_is_fatal
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 15205 occurrences with subject type phila_Incident and object type boolean.
    examples:
    - value: phila:OBJ_11856539 phila:is_fatal false
    from_schema: neighborhood-kg
    rank: 1000
    slot_uri: phila:is_fatal
    alias: phila_is_fatal
    owner: phila_Incident
    domain_of:
    - phila_Incident
    range: boolean
class_uri: phila:Incident

```
</details>