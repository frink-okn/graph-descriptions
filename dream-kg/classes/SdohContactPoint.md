

# Class: TODO -- what's a good name for what this class (type) describes? (sdoh_ContactPoint)


_TODO -- tell the world what this class (type) describes._





URI: [sdoh:ContactPoint](http://schema.org/ContactPoint)






```mermaid
 classDiagram
    class SdohContactPoint
    click SdohContactPoint href "../SdohContactPoint"
      SdohContactPoint : sdoh_telephone
        
          
    
    
    SdohContactPoint --> "0..1" String : sdoh_telephone
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sdoh_telephone](../slots/sdoh_telephone.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohServiceChannel](../classes/SdohServiceChannel.md) | [sdoh_servicePhone](../slots/sdoh_servicePhone.md) | range | [SdohContactPoint](../classes/SdohContactPoint.md) |







## Examples

| Value |
| --- |
| dreamkg:service/phone/5643194546257920 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:ContactPoint |
| native | dream-kg/:SdohContactPoint |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_ContactPoint
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 87 instances of this class.
examples:
- value: dreamkg:service/phone/5643194546257920
from_schema: dream-kg
slots:
- sdoh_telephone
class_uri: sdoh:ContactPoint

```
</details>

### Induced

<details>
```yaml
name: sdoh_ContactPoint
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 87 instances of this class.
examples:
- value: dreamkg:service/phone/5643194546257920
from_schema: dream-kg
attributes:
  sdoh_telephone:
    name: sdoh_telephone
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_ContactPoint and object type string.
    examples:
    - value: dreamkg:service/phone/4921265385242624 sdoh:telephone 215-563-0652
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:telephone
    alias: sdoh_telephone
    owner: sdoh_ContactPoint
    domain_of:
    - sdoh_ContactPoint
    range: string
class_uri: sdoh:ContactPoint

```
</details>