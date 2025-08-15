

# Class: Jxdm72CaseDefenseAttorney




This class occurs 2823772 times.


URI: [jxdm72:CaseDefenseAttorney](http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefenseAttorney)






```mermaid
 classDiagram
    class Jxdm72CaseDefenseAttorney
    click Jxdm72CaseDefenseAttorney href "../Jxdm72CaseDefenseAttorney"
      Jxdm72CaseDefenseAttorney : jxdm72_CaseOfficialRoleText
        
          
    
    
    Jxdm72CaseDefenseAttorney --> "0..1" String : jxdm72_CaseOfficialRoleText
    click String href "../String"

        
      Jxdm72CaseDefenseAttorney : niem50_ContactMailingAddress
        
          
    
    
    Jxdm72CaseDefenseAttorney --> "0..1" String : niem50_ContactMailingAddress
    click String href "../String"

        
      Jxdm72CaseDefenseAttorney : niem50_PersonFullName
        
          
    
    
    Jxdm72CaseDefenseAttorney --> "0..1" String : niem50_PersonFullName
    click String href "../String"

        
      Jxdm72CaseDefenseAttorney : scales_Firm
        
          
    
    
    Jxdm72CaseDefenseAttorney --> "0..1" ScalesFirm : scales_Firm
    click ScalesFirm href "../ScalesFirm"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [scales_Firm](../slots/scales_Firm.md) | 0..1 <br/> [ScalesFirm](../classes/ScalesFirm.md) |  <br/>  | direct | 1494159 |
| [jxdm72_CaseOfficialRoleText](../slots/jxdm72_CaseOfficialRoleText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 280534 |
| [niem50_PersonFullName](../slots/niem50_PersonFullName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 2823772 |
| [niem50_ContactMailingAddress](../slots/niem50_ContactMailingAddress.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 1571811 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Jxdm72CaseDefendantParty](../classes/Jxdm72CaseDefendantParty.md) | [Jxdm72CaseDefenseAttorney](../classes/Jxdm72CaseDefenseAttorney.md) | range | [Jxdm72CaseDefenseAttorney](../classes/Jxdm72CaseDefenseAttorney.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: jxdm72_CaseDefenseAttorney
from_schema: okns:scales-kg
rank: 1000
slots:
- scales_Firm
- jxdm72_CaseOfficialRoleText
- niem50_PersonFullName
- niem50_ContactMailingAddress
class_uri: jxdm72:CaseDefenseAttorney

```
</details>

### Induced

<details>

```yaml
name: jxdm72_CaseDefenseAttorney
from_schema: okns:scales-kg
rank: 1000
attributes:
  scales_Firm:
    name: scales_Firm
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:Firm
    alias: scales_Firm
    owner: jxdm72_CaseDefenseAttorney
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
    owner: jxdm72_CaseDefenseAttorney
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
    owner: jxdm72_CaseDefenseAttorney
    domain_of:
    - jxdm72_Attorney
    - jxdm72_CaseDefendantParty
    - jxdm72_CaseDefenseAttorney
    - jxdm72_CaseInitiatingAttorney
    - jxdm72_CaseJudge
    - jxdm72_Judge
    - scales_Party
    range: string
  niem50_ContactMailingAddress:
    name: niem50_ContactMailingAddress
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:ContactMailingAddress
    alias: niem50_ContactMailingAddress
    owner: jxdm72_CaseDefenseAttorney
    domain_of:
    - jxdm72_Attorney
    - jxdm72_CaseDefenseAttorney
    - jxdm72_CaseInitiatingAttorney
    range: string
class_uri: jxdm72:CaseDefenseAttorney

```
</details>