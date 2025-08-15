

# Class: Jxdm72RegisterOfActions




This class occurs 4160501 times.


URI: [jxdm72:RegisterOfActions](http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions)






```mermaid
 classDiagram
    class Jxdm72RegisterOfActions
    click Jxdm72RegisterOfActions href "../Jxdm72RegisterOfActions"
      Jxdm72RegisterOfActions : scales_DocketEntry
        
          
    
    
    Jxdm72RegisterOfActions --> "0..1" Any : scales_DocketEntry
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [scales_DocketEntry](../slots/scales_DocketEntry.md) | 0..1 <br/> [Jxdm72RegisterAction](../classes/Jxdm72RegisterAction.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) |  <br/>  | direct | 58334996 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [scales_DocketTable](../slots/scales_DocketTable.md) | any_of[range] | [Jxdm72RegisterOfActions](../classes/Jxdm72RegisterOfActions.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [scales_DocketTable](../slots/scales_DocketTable.md) | any_of[range] | [Jxdm72RegisterOfActions](../classes/Jxdm72RegisterOfActions.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: jxdm72_RegisterOfActions
from_schema: okns:scales-kg
rank: 1000
slots:
- scales_DocketEntry
class_uri: jxdm72:RegisterOfActions

```
</details>

### Induced

<details>

```yaml
name: jxdm72_RegisterOfActions
from_schema: okns:scales-kg
rank: 1000
attributes:
  scales_DocketEntry:
    name: scales_DocketEntry
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: scales:DocketEntry
    alias: scales_DocketEntry
    owner: jxdm72_RegisterOfActions
    domain_of:
    - jxdm72_RegisterAction
    - jxdm72_RegisterOfActions
    range: Any
    any_of:
    - range: jxdm72_RegisterAction
    - range: uri
class_uri: jxdm72:RegisterOfActions

```
</details>