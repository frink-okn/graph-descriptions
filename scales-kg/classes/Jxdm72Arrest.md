

# Class: Jxdm72Arrest




This class occurs 83347 times.


URI: [jxdm72:Arrest](http://release.niem.gov/niem/domains/jxdm/7.2/Arrest)






```mermaid
 classDiagram
    class Jxdm72Arrest
    click Jxdm72Arrest href "../Jxdm72Arrest"
      Jxdm72Arrest : jxdm72_ArrestOfficial
        
          
    
    
    Jxdm72Arrest --> "0..1" Jxdm72LawEnforcementOfficial : jxdm72_ArrestOfficial
    click Jxdm72LawEnforcementOfficial href "../Jxdm72LawEnforcementOfficial"

        
      Jxdm72Arrest : niem50_ActivityDate
        
          
    
    
    Jxdm72Arrest --> "0..1" Date : niem50_ActivityDate
    click Date href "../Date"

        
      Jxdm72Arrest : niem50_LocaleCensusBlockID
        
          
    
    
    Jxdm72Arrest --> "0..1" String : niem50_LocaleCensusBlockID
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [niem50_ActivityDate](../slots/niem50_ActivityDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 84279 |
| [jxdm72_ArrestOfficial](../slots/jxdm72_ArrestOfficial.md) | 0..1 <br/> [Jxdm72LawEnforcementOfficial](../classes/Jxdm72LawEnforcementOfficial.md) |  <br/>  | direct | 84716 |
| [niem50_LocaleCensusBlockID](../slots/niem50_LocaleCensusBlockID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 71598 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: jxdm72_Arrest
from_schema: okns:scales-kg
rank: 1000
slots:
- niem50_ActivityDate
- jxdm72_ArrestOfficial
- niem50_LocaleCensusBlockID
class_uri: jxdm72:Arrest

```
</details>

### Induced

<details>

```yaml
name: jxdm72_Arrest
from_schema: okns:scales-kg
rank: 1000
attributes:
  niem50_ActivityDate:
    name: niem50_ActivityDate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:ActivityDate
    alias: niem50_ActivityDate
    owner: jxdm72_Arrest
    domain_of:
    - jxdm72_Arrest
    - jxdm72_Booking
    - jxdm72_Release
    range: date
  jxdm72_ArrestOfficial:
    name: jxdm72_ArrestOfficial
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: jxdm72:ArrestOfficial
    alias: jxdm72_ArrestOfficial
    owner: jxdm72_Arrest
    domain_of:
    - jxdm72_Arrest
    range: jxdm72_LawEnforcementOfficial
  niem50_LocaleCensusBlockID:
    name: niem50_LocaleCensusBlockID
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:LocaleCensusBlockID
    alias: niem50_LocaleCensusBlockID
    owner: jxdm72_Arrest
    domain_of:
    - jxdm72_Arrest
    range: string
class_uri: jxdm72:Arrest

```
</details>