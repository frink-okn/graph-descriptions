

# Class: TODO -- what's a good name for what this class (type) describes? (sdoh_Audience)


_TODO -- tell the world what this class (type) describes._





URI: [sdoh:Audience](http://schema.org/Audience)






```mermaid
 classDiagram
    class SdohAudience
    click SdohAudience href "../SdohAudience"
      SdohAudience : sdoh_audienceType
        
          
    
    
    SdohAudience --> "0..1" String : sdoh_audienceType
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sdoh_audienceType](../slots/sdoh_audienceType.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohService](../classes/SdohService.md) | [sdoh_category](../slots/sdoh_category.md) | any_of[range] | [SdohAudience](../classes/SdohAudience.md) |







## Examples

| Value |
| --- |
| dreamkg:category/audience/AlcoholDependency |

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
| self | sdoh:Audience |
| native | dream-kg/:SdohAudience |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_Audience
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 81 instances of this class.
examples:
- value: dreamkg:category/audience/AlcoholDependency
from_schema: dream-kg
slots:
- sdoh_audienceType
class_uri: sdoh:Audience

```
</details>

### Induced

<details>
```yaml
name: sdoh_Audience
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 81 instances of this class.
examples:
- value: dreamkg:category/audience/AlcoholDependency
from_schema: dream-kg
attributes:
  sdoh_audienceType:
    name: sdoh_audienceType
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 81 occurrences with subject type sdoh_Audience and object type string.
    examples:
    - value: dreamkg:category/audience/Underinsured sdoh:audienceType underinsured
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:audienceType
    alias: sdoh_audienceType
    owner: sdoh_Audience
    domain_of:
    - sdoh_Audience
    range: string
class_uri: sdoh:Audience

```
</details>