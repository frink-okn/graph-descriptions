

# Class: ContactPoint (hsdo_ContactPoint)


_A contact point&#x2014;for example, a Customer Complaints department._





URI: [hsdo:ContactPoint](hsdo:ContactPoint)






```mermaid
 classDiagram
    class HsdoContactPoint
    click HsdoContactPoint href "../HsdoContactPoint"
      HsdoContactPoint : hsdo_telephone
        
          
    
    
    HsdoContactPoint --> "0..1" String : hsdo_telephone
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [hsdo_telephone](../slots/hsdo_telephone.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | [hsdo_servicePhone](../slots/hsdo_servicePhone.md) | range | [HsdoContactPoint](../classes/HsdoContactPoint.md) |







## Examples

| Value |
| --- |
| dreamkg:service/phone/5518091445075968 |


## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:ContactPoint |
| native | dream-kg/:HsdoContactPoint |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: hsdo_ContactPoint
description: A contact point&#x2014;for example, a Customer Complaints department.
title: ContactPoint
notes:
- Class with 87 occurrences.
examples:
- value: dreamkg:service/phone/5518091445075968
from_schema: dream-kg
rank: 1000
slots:
- hsdo_telephone
class_uri: hsdo:ContactPoint

```
</details>

### Induced

<details>
```yaml
name: hsdo_ContactPoint
description: A contact point&#x2014;for example, a Customer Complaints department.
title: ContactPoint
notes:
- Class with 87 occurrences.
examples:
- value: dreamkg:service/phone/5518091445075968
from_schema: dream-kg
rank: 1000
attributes:
  hsdo_telephone:
    name: hsdo_telephone
    description: No slot (predicate) description specified
    comments:
    - 87 occurrences with subject type hsdo_ContactPoint and object type string.
    examples:
    - description: hsdo_ContactPoint → string
      object:
        example_object: 215-496-9610
        example_predicate: hsdo:telephone
        example_subject: dreamkg:service/phone/5992920927698944
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:telephone
    alias: hsdo_telephone
    owner: hsdo_ContactPoint
    domain_of:
    - hsdo_ContactPoint
    range: string
class_uri: hsdo:ContactPoint

```
</details>