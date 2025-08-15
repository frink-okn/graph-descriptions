

# Class: Jxdm72CaseInitiatingAttorney




This class occurs 2755161 times.


URI: [jxdm72:CaseInitiatingAttorney](http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingAttorney)






```mermaid
 classDiagram
    class Jxdm72CaseInitiatingAttorney
    click Jxdm72CaseInitiatingAttorney href "../Jxdm72CaseInitiatingAttorney"
      Jxdm72CaseInitiatingAttorney : jxdm72_CaseOfficialRoleText
        
          
    
    
    Jxdm72CaseInitiatingAttorney --> "0..1" String : jxdm72_CaseOfficialRoleText
    click String href "../String"

        
      Jxdm72CaseInitiatingAttorney : niem50_ContactMailingAddress
        
          
    
    
    Jxdm72CaseInitiatingAttorney --> "0..1" String : niem50_ContactMailingAddress
    click String href "../String"

        
      Jxdm72CaseInitiatingAttorney : niem50_PersonFullName
        
          
    
    
    Jxdm72CaseInitiatingAttorney --> "0..1" String : niem50_PersonFullName
    click String href "../String"

        
      Jxdm72CaseInitiatingAttorney : scales_Firm
        
          
    
    
    Jxdm72CaseInitiatingAttorney --> "0..1" ScalesFirm : scales_Firm
    click ScalesFirm href "../ScalesFirm"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [scales_Firm](../slots/scales_Firm.md) | 0..1 <br/> [ScalesFirm](../classes/ScalesFirm.md) |  <br/>  | direct | 1365635 |
| [jxdm72_CaseOfficialRoleText](../slots/jxdm72_CaseOfficialRoleText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 204677 |
| [niem50_ContactMailingAddress](../slots/niem50_ContactMailingAddress.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 1432528 |
| [niem50_PersonFullName](../slots/niem50_PersonFullName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 2755161 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Jxdm72CaseInitiatingParty](../classes/Jxdm72CaseInitiatingParty.md) | [Jxdm72CaseInitiatingAttorney](../classes/Jxdm72CaseInitiatingAttorney.md) | range | [Jxdm72CaseInitiatingAttorney](../classes/Jxdm72CaseInitiatingAttorney.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: jxdm72_CaseInitiatingAttorney
from_schema: okns:scales-kg
rank: 1000
slots:
- scales_Firm
- jxdm72_CaseOfficialRoleText
- niem50_ContactMailingAddress
- niem50_PersonFullName
class_uri: jxdm72:CaseInitiatingAttorney

```
</details>

### Induced

<details>

```yaml
name: jxdm72_CaseInitiatingAttorney
from_schema: okns:scales-kg
rank: 1000
attributes:
  scales_Firm:
    name: scales_Firm
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:Firm
    alias: scales_Firm
    owner: jxdm72_CaseInitiatingAttorney
    domain_of:
    - jxdm72_Attorney
    - jxdm72_CaseDefenseAttorney
    - jxdm72_CaseInitiatingAttorney
    range: scales_Firm
  jxdm72_CaseOfficialRoleText:
    name: jxdm72_CaseOfficialRoleText
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: jxdm72:CaseOfficialRoleText
    alias: jxdm72_CaseOfficialRoleText
    owner: jxdm72_CaseInitiatingAttorney
    domain_of:
    - jxdm72_Attorney
    - jxdm72_CaseDefenseAttorney
    - jxdm72_CaseInitiatingAttorney
    range: string
  niem50_ContactMailingAddress:
    name: niem50_ContactMailingAddress
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:ContactMailingAddress
    alias: niem50_ContactMailingAddress
    owner: jxdm72_CaseInitiatingAttorney
    domain_of:
    - jxdm72_Attorney
    - jxdm72_CaseDefenseAttorney
    - jxdm72_CaseInitiatingAttorney
    range: string
  niem50_PersonFullName:
    name: niem50_PersonFullName
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:PersonFullName
    alias: niem50_PersonFullName
    owner: jxdm72_CaseInitiatingAttorney
    domain_of:
    - jxdm72_Attorney
    - jxdm72_CaseDefendantParty
    - jxdm72_CaseDefenseAttorney
    - jxdm72_CaseInitiatingAttorney
    - jxdm72_CaseJudge
    - jxdm72_Judge
    - scales_Party
    range: string
class_uri: jxdm72:CaseInitiatingAttorney

```
</details>