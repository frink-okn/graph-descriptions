

# Class: TODO -- what's a good name for what this class (type) describes? (rural_substanceabuse_SubstanceRelatedIncident)


_TODO -- tell the world what this class (type) describes._





URI: [rural:substanceabuse/SubstanceRelatedIncident](http://sail.ua.edu/ruralkg/substanceabuse/SubstanceRelatedIncident)






```mermaid
 classDiagram
    class RuralSubstanceabuseSubstanceRelatedIncident
    click RuralSubstanceabuseSubstanceRelatedIncident href "../RuralSubstanceabuseSubstanceRelatedIncident"
      RuralSubstanceabuseSubstanceRelatedIncident : rural_substanceabuse_name
        
          
    
    
    RuralSubstanceabuseSubstanceRelatedIncident --> "0..1" String : rural_substanceabuse_name
    click String href "../String"

        
      RuralSubstanceabuseSubstanceRelatedIncident : rural_substanceabuse_sourceDataset
        
          
    
    
    RuralSubstanceabuseSubstanceRelatedIncident --> "0..1" String : rural_substanceabuse_sourceDataset
    click String href "../String"

        
      RuralSubstanceabuseSubstanceRelatedIncident : rural_substanceabuse_year
        
          
    
    
    RuralSubstanceabuseSubstanceRelatedIncident --> "0..1" Integer : rural_substanceabuse_year
    click Integer href "../Integer"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [rural_substanceabuse_year](../slots/rural_substanceabuse_year.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_substanceabuse_name](../slots/rural_substanceabuse_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_substanceabuse_sourceDataset](../slots/rural_substanceabuse_sourceDataset.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |










## Examples

| Value |
| --- |
| rural:substanceabuse/SIT_9 |

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
| self | rural:substanceabuse/SubstanceRelatedIncident |
| native | rural-kg/:RuralSubstanceabuseSubstanceRelatedIncident |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: rural_substanceabuse_SubstanceRelatedIncident
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 17 instances of this class.
examples:
- value: rural:substanceabuse/SIT_9
from_schema: rural-kg
slots:
- rural_substanceabuse_year
- rural_substanceabuse_name
- rural_substanceabuse_sourceDataset
class_uri: rural:substanceabuse/SubstanceRelatedIncident

```
</details>

### Induced

<details>
```yaml
name: rural_substanceabuse_SubstanceRelatedIncident
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 17 instances of this class.
examples:
- value: rural:substanceabuse/SIT_9
from_schema: rural-kg
attributes:
  rural_substanceabuse_year:
    name: rural_substanceabuse_year
    description: TODO -- tell the world what this slot (predicate) describes.
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
    - value: rural:substanceabuse/Substance_8 rural:substanceabuse/year 2022
    - value: rural:substanceabuse/SIT_8 rural:substanceabuse/year 2022
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:substanceabuse/year
    alias: rural_substanceabuse_year
    owner: rural_substanceabuse_SubstanceRelatedIncident
    domain_of:
    - rural_substanceabuse_Substance
    - rural_substanceabuse_SubstanceRelatedIncident
    range: integer
  rural_substanceabuse_name:
    name: rural_substanceabuse_name
    description: TODO -- tell the world what this slot (predicate) describes.
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
    - value: rural:substanceabuse/SIT_10 rural:substanceabuse/name Used an Illicit
        Drug
    - value: rural:substanceabuse/Substance_12 rural:substanceabuse/name tranquilizer
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:substanceabuse/name
    alias: rural_substanceabuse_name
    owner: rural_substanceabuse_SubstanceRelatedIncident
    domain_of:
    - rural_substanceabuse_Substance
    - rural_substanceabuse_SubstanceRelatedIncident
    range: string
  rural_substanceabuse_sourceDataset:
    name: rural_substanceabuse_sourceDataset
    description: TODO -- tell the world what this slot (predicate) describes.
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
    - value: rural:substanceabuse/Substance_9 rural:substanceabuse/sourceDataset NSDUH
    - value: rural:substanceabuse/SIT_8 rural:substanceabuse/sourceDataset NSDUH
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:substanceabuse/sourceDataset
    alias: rural_substanceabuse_sourceDataset
    owner: rural_substanceabuse_SubstanceRelatedIncident
    domain_of:
    - rural_substanceabuse_Substance
    - rural_substanceabuse_SubstanceRelatedIncident
    range: string
class_uri: rural:substanceabuse/SubstanceRelatedIncident

```
</details>