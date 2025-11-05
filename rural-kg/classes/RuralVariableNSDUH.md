

# Class: RuralVariableNSDUH


_Variables from the National Survey on Drug Use and Health dataset._






This class occurs 2464 times.


URI: [rural:variable/NSDUH](http://sail.ua.edu/ruralkg/variable/NSDUH)






```mermaid
 classDiagram
    class RuralVariableNSDUH
    click RuralVariableNSDUH href "../RuralVariableNSDUH"
      RuralVariableVariable <|-- RuralVariableNSDUH
        click RuralVariableVariable href "../RuralVariableVariable"
      
      RuralVariableNSDUH : rural_variable_code
        
          
    
    
    RuralVariableNSDUH --> "0..1" String : rural_variable_code
    click String href "../String"

        
      RuralVariableNSDUH : rural_variable_content
        
          
    
    
    RuralVariableNSDUH --> "0..1" String : rural_variable_content
    click String href "../String"

        
      RuralVariableNSDUH : rural_variable_description
        
          
    
    
    RuralVariableNSDUH --> "0..1" String : rural_variable_description
    click String href "../String"

        
      RuralVariableNSDUH : rural_variable_fromDataset
        
          
    
    
    RuralVariableNSDUH --> "0..1" String : rural_variable_fromDataset
    click String href "../String"

        
      RuralVariableNSDUH : rural_variable_generatedDescription
        
          
    
    
    RuralVariableNSDUH --> "0..1" String : rural_variable_generatedDescription
    click String href "../String"

        
      RuralVariableNSDUH : rural_variable_hasAnswer
        
          
    
    
    RuralVariableNSDUH --> "0..1" Any : rural_variable_hasAnswer
    click Any href "../Any"

        
      RuralVariableNSDUH : rural_variable_year
        
          
    
    
    RuralVariableNSDUH --> "0..1" Integer : rural_variable_year
    click Integer href "../Integer"

        
      
```





## Inheritance
* [RuralVariableVariable](../classes/RuralVariableVariable.md)
    * **RuralVariableNSDUH**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [rural_variable_description](../slots/rural_variable_description.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 2464 |
| [rural_variable_year](../slots/rural_variable_year.md) | 0..1 <br/> [xsd:integer](xsd:integer) |  <br/>  | direct | 2464 |
| [rural_variable_hasAnswer](../slots/rural_variable_hasAnswer.md) | 0..1 <br/> [RuralVariableNIBRSAnswer](../classes/RuralVariableNIBRSAnswer.md)&nbsp;or&nbsp;<br />[RuralVariableNSDUHAnswer](../classes/RuralVariableNSDUHAnswer.md) |  <br/>  | direct | 14923 |
| [rural_variable_content](../slots/rural_variable_content.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 2465 |
| [rural_variable_fromDataset](../slots/rural_variable_fromDataset.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 2464 |
| [rural_variable_generatedDescription](../slots/rural_variable_generatedDescription.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 2465 |
| [rural_variable_code](../slots/rural_variable_code.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 2464 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: rural_variable_NSDUH
description: Variables from the National Survey on Drug Use and Health dataset.
from_schema: okns:rural-kg
rank: 1000
is_a: rural_variable_Variable
slots:
- rural_variable_description
- rural_variable_year
- rural_variable_hasAnswer
- rural_variable_content
- rural_variable_fromDataset
- rural_variable_generatedDescription
- rural_variable_code
class_uri: rural:variable/NSDUH

```
</details>

### Induced

<details>

```yaml
name: rural_variable_NSDUH
description: Variables from the National Survey on Drug Use and Health dataset.
from_schema: okns:rural-kg
rank: 1000
is_a: rural_variable_Variable
attributes:
  rural_variable_description:
    name: rural_variable_description
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:variable/description
    alias: rural_variable_description
    owner: rural_variable_NSDUH
    domain_of:
    - rural_variable_NIBRS
    - rural_variable_NSDUH
    range: string
  rural_variable_year:
    name: rural_variable_year
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:variable/year
    alias: rural_variable_year
    owner: rural_variable_NSDUH
    domain_of:
    - rural_variable_NIBRS
    - rural_variable_NSDUH
    range: integer
  rural_variable_hasAnswer:
    name: rural_variable_hasAnswer
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:variable/hasAnswer
    alias: rural_variable_hasAnswer
    owner: rural_variable_NSDUH
    domain_of:
    - rural_variable_NIBRS
    - rural_variable_NSDUH
    range: Any
    any_of:
    - range: rural_variable_NIBRSAnswer
    - range: rural_variable_NSDUHAnswer
  rural_variable_content:
    name: rural_variable_content
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:variable/content
    alias: rural_variable_content
    owner: rural_variable_NSDUH
    domain_of:
    - rural_variable_NIBRS
    - rural_variable_NSDUH
    range: string
  rural_variable_fromDataset:
    name: rural_variable_fromDataset
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:variable/fromDataset
    alias: rural_variable_fromDataset
    owner: rural_variable_NSDUH
    domain_of:
    - rural_variable_NIBRS
    - rural_variable_NSDUH
    range: string
  rural_variable_generatedDescription:
    name: rural_variable_generatedDescription
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:variable/generatedDescription
    alias: rural_variable_generatedDescription
    owner: rural_variable_NSDUH
    domain_of:
    - rural_variable_NIBRS
    - rural_variable_NSDUH
    range: string
  rural_variable_code:
    name: rural_variable_code
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:variable/code
    alias: rural_variable_code
    owner: rural_variable_NSDUH
    domain_of:
    - rural_variable_NIBRS
    - rural_variable_NSDUH
    range: string
class_uri: rural:variable/NSDUH

```
</details>