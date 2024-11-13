

# Class: TODO -- what's a good name for what this class (type) describes? (rural_mentalhealthservice_MentalHealthServiceCategory)


_TODO -- tell the world what this class (type) describes._





URI: [rural:mentalhealthservice/MentalHealthServiceCategory](http://sail.ua.edu/ruralkg/mentalhealthservice/MentalHealthServiceCategory)






```mermaid
 classDiagram
    class RuralMentalhealthserviceMentalHealthServiceCategory
    click RuralMentalhealthserviceMentalHealthServiceCategory href "../RuralMentalhealthserviceMentalHealthServiceCategory"
      RuralMentalhealthserviceMentalHealthServiceCategory : rural_mentalhealthservice_code
        
          
    
    
    RuralMentalhealthserviceMentalHealthServiceCategory --> "0..1" String : rural_mentalhealthservice_code
    click String href "../String"

        
      RuralMentalhealthserviceMentalHealthServiceCategory : rural_mentalhealthservice_containsService
        
          
    
    
    RuralMentalhealthserviceMentalHealthServiceCategory --> "0..1" RuralMentalhealthserviceMentalHealthService : rural_mentalhealthservice_containsService
    click RuralMentalhealthserviceMentalHealthService href "../RuralMentalhealthserviceMentalHealthService"

        
      RuralMentalhealthserviceMentalHealthServiceCategory : rural_mentalhealthservice_name
        
          
    
    
    RuralMentalhealthserviceMentalHealthServiceCategory --> "0..1" String : rural_mentalhealthservice_name
    click String href "../String"

        
      RuralMentalhealthserviceMentalHealthServiceCategory : rural_mentalhealthservice_year
        
          
    
    
    RuralMentalhealthserviceMentalHealthServiceCategory --> "0..1" Integer : rural_mentalhealthservice_year
    click Integer href "../Integer"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [rural_mentalhealthservice_containsService](../slots/rural_mentalhealthservice_containsService.md) | 0..1 <br/> [RuralMentalhealthserviceMentalHealthService](../classes/RuralMentalhealthserviceMentalHealthService.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_mentalhealthservice_code](../slots/rural_mentalhealthservice_code.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_mentalhealthservice_year](../slots/rural_mentalhealthservice_year.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_mentalhealthservice_name](../slots/rural_mentalhealthservice_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |










## Examples

| Value |
| --- |
| rural:mentalhealthservice/MHSC_RSS |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:mentalhealthservice/MentalHealthServiceCategory |
| native | rural-kg/:RuralMentalhealthserviceMentalHealthServiceCategory |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: rural_mentalhealthservice_MentalHealthServiceCategory
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 21 instances of this class.
examples:
- value: rural:mentalhealthservice/MHSC_RSS
from_schema: rural-kg
slots:
- rural_mentalhealthservice_containsService
- rural_mentalhealthservice_code
- rural_mentalhealthservice_year
- rural_mentalhealthservice_name
class_uri: rural:mentalhealthservice/MentalHealthServiceCategory

```
</details>

### Induced

<details>
```yaml
name: rural_mentalhealthservice_MentalHealthServiceCategory
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 21 instances of this class.
examples:
- value: rural:mentalhealthservice/MHSC_RSS
from_schema: rural-kg
attributes:
  rural_mentalhealthservice_containsService:
    name: rural_mentalhealthservice_containsService
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 176 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory
      and object type rural_mentalhealthservice_MentalHealthService.
    examples:
    - value: rural:mentalhealthservice/MHSC_AS rural:mentalhealthservice/containsService
        rural:mentalhealthservice/MHS_COOT
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:mentalhealthservice/containsService
    alias: rural_mentalhealthservice_containsService
    owner: rural_mentalhealthservice_MentalHealthServiceCategory
    domain_of:
    - rural_mentalhealthservice_MentalHealthServiceCategory
    range: rural_mentalhealthservice_MentalHealthService
  rural_mentalhealthservice_code:
    name: rural_mentalhealthservice_code
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory
      and object type string.
    - 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService
      and object type string.
    examples:
    - value: rural:mentalhealthservice/MHSC_AGE rural:mentalhealthservice/code AGE
    - value: rural:mentalhealthservice/MHS_FED rural:mentalhealthservice/code FED
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:mentalhealthservice/code
    alias: rural_mentalhealthservice_code
    owner: rural_mentalhealthservice_MentalHealthServiceCategory
    domain_of:
    - rural_mentalhealthservice_MentalHealthService
    - rural_mentalhealthservice_MentalHealthServiceCategory
    range: string
  rural_mentalhealthservice_year:
    name: rural_mentalhealthservice_year
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService
      and object type integer.
    - 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory
      and object type integer.
    examples:
    - value: rural:mentalhealthservice/MHS_F19 rural:mentalhealthservice/year 2022
    - value: rural:mentalhealthservice/MHSC_SCR rural:mentalhealthservice/year 2022
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:mentalhealthservice/year
    alias: rural_mentalhealthservice_year
    owner: rural_mentalhealthservice_MentalHealthServiceCategory
    domain_of:
    - rural_mentalhealthservice_MentalHealthService
    - rural_mentalhealthservice_MentalHealthServiceCategory
    range: integer
  rural_mentalhealthservice_name:
    name: rural_mentalhealthservice_name
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService
      and object type string.
    - 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory
      and object type string.
    examples:
    - value: rural:mentalhealthservice/MHS_DV rural:mentalhealthservice/name Clients
        who have experienced intimate partner violence, domestic violence
    - value: rural:mentalhealthservice/MHSC_ECS rural:mentalhealthservice/name Education
        and Counseling Services
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:mentalhealthservice/name
    alias: rural_mentalhealthservice_name
    owner: rural_mentalhealthservice_MentalHealthServiceCategory
    domain_of:
    - rural_mentalhealthservice_MentalHealthService
    - rural_mentalhealthservice_MentalHealthServiceCategory
    range: string
class_uri: rural:mentalhealthservice/MentalHealthServiceCategory

```
</details>