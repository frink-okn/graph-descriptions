

# Class: Jxdm72Release




This class occurs 347084 times.


URI: [jxdm72:Release](http://release.niem.gov/niem/domains/jxdm/7.2/Release)






```mermaid
 classDiagram
    class Jxdm72Release
    click Jxdm72Release href "../Jxdm72Release"
      Jxdm72Release : niem50_ActivityDate
        
          
    
    
    Jxdm72Release --> "0..1" Date : niem50_ActivityDate
    click Date href "../Date"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [niem50_ActivityDate](../slots/niem50_ActivityDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 400567 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Jxdm72Booking](../classes/Jxdm72Booking.md) | [jxdm72_BookingRelease](../slots/jxdm72_BookingRelease.md) | range | [Jxdm72Release](../classes/Jxdm72Release.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: jxdm72_Release
from_schema: okns:scales-kg
rank: 1000
slots:
- niem50_ActivityDate
class_uri: jxdm72:Release

```
</details>

### Induced

<details>

```yaml
name: jxdm72_Release
from_schema: okns:scales-kg
rank: 1000
attributes:
  niem50_ActivityDate:
    name: niem50_ActivityDate
    from_schema: okns:scales-kg
    rank: 1000
    slot_uri: niem50:ActivityDate
    alias: niem50_ActivityDate
    owner: jxdm72_Release
    domain_of:
    - jxdm72_Arrest
    - jxdm72_Booking
    - jxdm72_Release
    range: date
class_uri: jxdm72:Release

```
</details>