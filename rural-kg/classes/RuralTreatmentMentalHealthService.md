

# Class: RuralTreatmentMentalHealthService


_Specific mental health services offered._






This class occurs 176 times.


URI: [rural:treatment/MentalHealthService](http://sail.ua.edu/ruralkg/treatment/MentalHealthService)






```mermaid
 classDiagram
    class RuralTreatmentMentalHealthService
    click RuralTreatmentMentalHealthService href "../RuralTreatmentMentalHealthService"
      RuralTreatmentTreatment <|-- RuralTreatmentMentalHealthService
        click RuralTreatmentTreatment href "../RuralTreatmentTreatment"
      
      RuralTreatmentMentalHealthService : rural_treatment_code
        
          
    
    
    RuralTreatmentMentalHealthService --> "0..1" String : rural_treatment_code
    click String href "../String"

        
      RuralTreatmentMentalHealthService : rural_treatment_description
        
          
    
    
    RuralTreatmentMentalHealthService --> "0..1" String : rural_treatment_description
    click String href "../String"

        
      RuralTreatmentMentalHealthService : rural_treatment_name
        
          
    
    
    RuralTreatmentMentalHealthService --> "0..1" String : rural_treatment_name
    click String href "../String"

        
      RuralTreatmentMentalHealthService : rural_treatment_year
        
          
    
    
    RuralTreatmentMentalHealthService --> "0..1" Integer : rural_treatment_year
    click Integer href "../Integer"

        
      
```





## Inheritance
* [RuralTreatmentTreatment](../classes/RuralTreatmentTreatment.md)
    * **RuralTreatmentMentalHealthService**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [rural_treatment_description](../slots/rural_treatment_description.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 176 |
| [rural_treatment_year](../slots/rural_treatment_year.md) | 0..1 <br/> [xsd:integer](xsd:integer) |  <br/>  | direct | 176 |
| [rural_treatment_code](../slots/rural_treatment_code.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 176 |
| [rural_treatment_name](../slots/rural_treatment_name.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 176 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [RuralTreatmentMentalHealthServiceCategory](../classes/RuralTreatmentMentalHealthServiceCategory.md) | [rural_treatment_containsService](../slots/rural_treatment_containsService.md) | range | [RuralTreatmentMentalHealthService](../classes/RuralTreatmentMentalHealthService.md) |
| [RuralTreatmentTreatmentProvider](../classes/RuralTreatmentTreatmentProvider.md) | [rural_treatment_providesService](../slots/rural_treatment_providesService.md) | range | [RuralTreatmentMentalHealthService](../classes/RuralTreatmentMentalHealthService.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: rural_treatment_MentalHealthService
description: Specific mental health services offered.
from_schema: okns:rural-kg
rank: 1000
is_a: rural_treatment_Treatment
slots:
- rural_treatment_description
- rural_treatment_year
- rural_treatment_code
- rural_treatment_name
class_uri: rural:treatment/MentalHealthService

```
</details>

### Induced

<details>

```yaml
name: rural_treatment_MentalHealthService
description: Specific mental health services offered.
from_schema: okns:rural-kg
rank: 1000
is_a: rural_treatment_Treatment
attributes:
  rural_treatment_description:
    name: rural_treatment_description
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:treatment/description
    alias: rural_treatment_description
    owner: rural_treatment_MentalHealthService
    domain_of:
    - rural_treatment_MentalHealthService
    range: string
  rural_treatment_year:
    name: rural_treatment_year
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:treatment/year
    alias: rural_treatment_year
    owner: rural_treatment_MentalHealthService
    domain_of:
    - rural_treatment_MentalHealthService
    - rural_treatment_MentalHealthServiceCategory
    range: integer
  rural_treatment_code:
    name: rural_treatment_code
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:treatment/code
    alias: rural_treatment_code
    owner: rural_treatment_MentalHealthService
    domain_of:
    - rural_treatment_MentalHealthService
    - rural_treatment_MentalHealthServiceCategory
    range: string
  rural_treatment_name:
    name: rural_treatment_name
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:treatment/name
    alias: rural_treatment_name
    owner: rural_treatment_MentalHealthService
    domain_of:
    - rural_treatment_MentalHealthService
    - rural_treatment_MentalHealthServiceCategory
    - rural_treatment_TreatmentProvider
    range: string
class_uri: rural:treatment/MentalHealthService

```
</details>