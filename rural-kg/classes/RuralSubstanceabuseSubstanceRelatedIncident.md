

# Class: RuralSubstanceabuseSubstanceRelatedIncident


_Types of incidents related to substance abuse._






This class occurs 17 times.


URI: [rural:substanceabuse/SubstanceRelatedIncident](http://sail.ua.edu/ruralkg/substanceabuse/SubstanceRelatedIncident)






```mermaid
 classDiagram
    class RuralSubstanceabuseSubstanceRelatedIncident
    click RuralSubstanceabuseSubstanceRelatedIncident href "../RuralSubstanceabuseSubstanceRelatedIncident"
      RuralSubstanceabuseSubstanceAbuse <|-- RuralSubstanceabuseSubstanceRelatedIncident
        click RuralSubstanceabuseSubstanceAbuse href "../RuralSubstanceabuseSubstanceAbuse"
      
      RuralSubstanceabuseSubstanceRelatedIncident : rural_substanceabuse_fromDataset
        
          
    
    
    RuralSubstanceabuseSubstanceRelatedIncident --> "0..1" String : rural_substanceabuse_fromDataset
    click String href "../String"

        
      RuralSubstanceabuseSubstanceRelatedIncident : rural_substanceabuse_name
        
          
    
    
    RuralSubstanceabuseSubstanceRelatedIncident --> "0..1" String : rural_substanceabuse_name
    click String href "../String"

        
      RuralSubstanceabuseSubstanceRelatedIncident : rural_substanceabuse_year
        
          
    
    
    RuralSubstanceabuseSubstanceRelatedIncident --> "0..1" Integer : rural_substanceabuse_year
    click Integer href "../Integer"

        
      
```





## Inheritance
* [RuralSubstanceabuseSubstanceAbuse](../classes/RuralSubstanceabuseSubstanceAbuse.md)
    * **RuralSubstanceabuseSubstanceRelatedIncident**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [rural_substanceabuse_year](../slots/rural_substanceabuse_year.md) | 0..1 <br/> [xsd:integer](xsd:integer) |  <br/>  | direct | 17 |
| [rural_substanceabuse_name](../slots/rural_substanceabuse_name.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 17 |
| [rural_substanceabuse_fromDataset](../slots/rural_substanceabuse_fromDataset.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 17 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: rural_substanceabuse_SubstanceRelatedIncident
description: Types of incidents related to substance abuse.
from_schema: okns:rural-kg
rank: 1000
is_a: rural_substanceabuse_SubstanceAbuse
slots:
- rural_substanceabuse_year
- rural_substanceabuse_name
- rural_substanceabuse_fromDataset
class_uri: rural:substanceabuse/SubstanceRelatedIncident

```
</details>

### Induced

<details>

```yaml
name: rural_substanceabuse_SubstanceRelatedIncident
description: Types of incidents related to substance abuse.
from_schema: okns:rural-kg
rank: 1000
is_a: rural_substanceabuse_SubstanceAbuse
attributes:
  rural_substanceabuse_year:
    name: rural_substanceabuse_year
    from_schema: okns:rural-kg
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
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:substanceabuse/name
    alias: rural_substanceabuse_name
    owner: rural_substanceabuse_SubstanceRelatedIncident
    domain_of:
    - rural_substanceabuse_Substance
    - rural_substanceabuse_SubstanceRelatedIncident
    range: string
  rural_substanceabuse_fromDataset:
    name: rural_substanceabuse_fromDataset
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:substanceabuse/fromDataset
    alias: rural_substanceabuse_fromDataset
    owner: rural_substanceabuse_SubstanceRelatedIncident
    domain_of:
    - rural_substanceabuse_Substance
    - rural_substanceabuse_SubstanceRelatedIncident
    range: string
class_uri: rural:substanceabuse/SubstanceRelatedIncident

```
</details>