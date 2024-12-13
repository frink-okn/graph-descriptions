

# Class: TODO -- what's a good name for what this class (type) describes? (rural_substanceabuse_Substance)


_Types of substances that can be abused._





URI: [rural:substanceabuse/Substance](http://sail.ua.edu/ruralkg/substanceabuse/Substance)






```mermaid
 classDiagram
    class RuralSubstanceabuseSubstance
    click RuralSubstanceabuseSubstance href "../RuralSubstanceabuseSubstance"
      RuralSubstanceabuseSubstanceAbuse <|-- RuralSubstanceabuseSubstance
        click RuralSubstanceabuseSubstanceAbuse href "../RuralSubstanceabuseSubstanceAbuse"
      
      RuralSubstanceabuseSubstance : rural_substanceabuse_code
        
          
    
    
    RuralSubstanceabuseSubstance --> "0..1" String : rural_substanceabuse_code
    click String href "../String"

        
      RuralSubstanceabuseSubstance : rural_substanceabuse_name
        
          
    
    
    RuralSubstanceabuseSubstance --> "0..1" String : rural_substanceabuse_name
    click String href "../String"

        
      RuralSubstanceabuseSubstance : rural_substanceabuse_sourceDataset
        
          
    
    
    RuralSubstanceabuseSubstance --> "0..1" String : rural_substanceabuse_sourceDataset
    click String href "../String"

        
      RuralSubstanceabuseSubstance : rural_substanceabuse_year
        
          
    
    
    RuralSubstanceabuseSubstance --> "0..1" Integer : rural_substanceabuse_year
    click Integer href "../Integer"

        
      
```





## Inheritance
* [RuralSubstanceabuseSubstanceAbuse](../classes/RuralSubstanceabuseSubstanceAbuse.md)
    * **RuralSubstanceabuseSubstance**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [rural_substanceabuse_name](../slots/rural_substanceabuse_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided <br/> 25 occurrences with subject type rural_substanceabuse_Substance and object type string.<br/>17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and object type string. | direct |
| [rural_substanceabuse_year](../slots/rural_substanceabuse_year.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot description provided <br/> 25 occurrences with subject type rural_substanceabuse_Substance and object type integer.<br/>17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and object type integer. | direct |
| [rural_substanceabuse_sourceDataset](../slots/rural_substanceabuse_sourceDataset.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided <br/> 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and object type string.<br/>25 occurrences with subject type rural_substanceabuse_Substance and object type string. | direct |
| [rural_substanceabuse_code](../slots/rural_substanceabuse_code.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided <br/> 25 occurrences with subject type rural_substanceabuse_Substance and object type string. | direct |










## Examples

| Value |
| --- |
| rural:substanceabuse/Substance_16 |


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
| self | rural:substanceabuse/Substance |
| native | rural-kg/:RuralSubstanceabuseSubstance |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: rural_substanceabuse_Substance
description: Types of substances that can be abused.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 25 instances of this class.
examples:
- value: rural:substanceabuse/Substance_16
from_schema: rural-kg
rank: 1000
is_a: rural_substanceabuse_SubstanceAbuse
slots:
- rural_substanceabuse_name
- rural_substanceabuse_year
- rural_substanceabuse_sourceDataset
- rural_substanceabuse_code
class_uri: rural:substanceabuse/Substance

```
</details>

### Induced

<details>
```yaml
name: rural_substanceabuse_Substance
description: Types of substances that can be abused.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 25 instances of this class.
examples:
- value: rural:substanceabuse/Substance_16
from_schema: rural-kg
rank: 1000
is_a: rural_substanceabuse_SubstanceAbuse
attributes:
  rural_substanceabuse_name:
    name: rural_substanceabuse_name
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 25 occurrences with subject type rural_substanceabuse_Substance and object type
      string.
    - 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident
      and object type string.
    examples:
    - value: rural:substanceabuse/Substance_16 rural:substanceabuse/name pcp
    - value: rural:substanceabuse/SIT_13 rural:substanceabuse/name On Parole
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:substanceabuse/name
    alias: rural_substanceabuse_name
    owner: rural_substanceabuse_Substance
    domain_of:
    - rural_substanceabuse_Substance
    - rural_substanceabuse_SubstanceRelatedIncident
    range: string
  rural_substanceabuse_year:
    name: rural_substanceabuse_year
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 25 occurrences with subject type rural_substanceabuse_Substance and object type
      integer.
    - 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident
      and object type integer.
    examples:
    - value: rural:substanceabuse/Substance_13 rural:substanceabuse/year 2022
    - value: rural:substanceabuse/SIT_4 rural:substanceabuse/year 2022
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:substanceabuse/year
    alias: rural_substanceabuse_year
    owner: rural_substanceabuse_Substance
    domain_of:
    - rural_substanceabuse_Substance
    - rural_substanceabuse_SubstanceRelatedIncident
    range: integer
  rural_substanceabuse_sourceDataset:
    name: rural_substanceabuse_sourceDataset
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident
      and object type string.
    - 25 occurrences with subject type rural_substanceabuse_Substance and object type
      string.
    examples:
    - value: rural:substanceabuse/SIT_4 rural:substanceabuse/sourceDataset NSDUH
    - value: rural:substanceabuse/Substance_2 rural:substanceabuse/sourceDataset NSDUH
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:substanceabuse/sourceDataset
    alias: rural_substanceabuse_sourceDataset
    owner: rural_substanceabuse_Substance
    domain_of:
    - rural_substanceabuse_Substance
    - rural_substanceabuse_SubstanceRelatedIncident
    range: string
  rural_substanceabuse_code:
    name: rural_substanceabuse_code
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 25 occurrences with subject type rural_substanceabuse_Substance and object type
      string.
    examples:
    - value: rural:substanceabuse/Substance_17 rural:substanceabuse/code 7405
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:substanceabuse/code
    alias: rural_substanceabuse_code
    owner: rural_substanceabuse_Substance
    domain_of:
    - rural_substanceabuse_Substance
    range: string
class_uri: rural:substanceabuse/Substance

```
</details>