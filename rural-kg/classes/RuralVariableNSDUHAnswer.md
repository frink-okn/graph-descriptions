

# Class: RuralVariableNSDUHAnswer


_Answer options for NSDUH variables._






This class occurs 14923 times.


URI: [rural:variable/NSDUHAnswer](http://sail.ua.edu/ruralkg/variable/NSDUHAnswer)






```mermaid
 classDiagram
    class RuralVariableNSDUHAnswer
    click RuralVariableNSDUHAnswer href "../RuralVariableNSDUHAnswer"
      RuralVariableAnswer <|-- RuralVariableNSDUHAnswer
        click RuralVariableAnswer href "../RuralVariableAnswer"
      
      RuralVariableNSDUHAnswer : rural_variable_answerCode
        
          
    
    
    RuralVariableNSDUHAnswer --> "0..1" String : rural_variable_answerCode
    click String href "../String"

        
      RuralVariableNSDUHAnswer : rural_variable_answerContent
        
          
    
    
    RuralVariableNSDUHAnswer --> "0..1" String : rural_variable_answerContent
    click String href "../String"

        
      
```





## Inheritance
* [RuralVariableVariable](../classes/RuralVariableVariable.md)
    * [RuralVariableAnswer](../classes/RuralVariableAnswer.md)
        * **RuralVariableNSDUHAnswer**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [rural_variable_answerCode](../slots/rural_variable_answerCode.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 14923 |
| [rural_variable_answerContent](../slots/rural_variable_answerContent.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 14923 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [RuralVariableNIBRS](../classes/RuralVariableNIBRS.md) | [rural_variable_hasAnswer](../slots/rural_variable_hasAnswer.md) | any_of[range] | [RuralVariableNSDUHAnswer](../classes/RuralVariableNSDUHAnswer.md) |
| [RuralVariableNSDUH](../classes/RuralVariableNSDUH.md) | [rural_variable_hasAnswer](../slots/rural_variable_hasAnswer.md) | any_of[range] | [RuralVariableNSDUHAnswer](../classes/RuralVariableNSDUHAnswer.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: rural_variable_NSDUHAnswer
description: Answer options for NSDUH variables.
from_schema: okns:rural-kg
rank: 1000
is_a: rural_variable_Answer
slots:
- rural_variable_answerCode
- rural_variable_answerContent
class_uri: rural:variable/NSDUHAnswer

```
</details>

### Induced

<details>

```yaml
name: rural_variable_NSDUHAnswer
description: Answer options for NSDUH variables.
from_schema: okns:rural-kg
rank: 1000
is_a: rural_variable_Answer
attributes:
  rural_variable_answerCode:
    name: rural_variable_answerCode
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:variable/answerCode
    alias: rural_variable_answerCode
    owner: rural_variable_NSDUHAnswer
    domain_of:
    - rural_variable_NIBRSAnswer
    - rural_variable_NSDUHAnswer
    range: string
  rural_variable_answerContent:
    name: rural_variable_answerContent
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:variable/answerContent
    alias: rural_variable_answerContent
    owner: rural_variable_NSDUHAnswer
    domain_of:
    - rural_variable_NIBRSAnswer
    - rural_variable_NSDUHAnswer
    range: string
class_uri: rural:variable/NSDUHAnswer

```
</details>