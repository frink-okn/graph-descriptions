

# Class: CategoryCode (sdoh_CategoryCode)


_A Category Code._





URI: [sdoh:CategoryCode](http://schema.org/CategoryCode)






```mermaid
 classDiagram
    class SdohCategoryCode
    click SdohCategoryCode href "../SdohCategoryCode"
      SdohCategoryCode : sdoh_codeValue
        
          
    
    
    SdohCategoryCode --> "0..1" String : sdoh_codeValue
    click String href "../String"

        
      SdohCategoryCode : sdoh_inCodeSet
        
          
    
    
    SdohCategoryCode --> "0..1" Uri : sdoh_inCodeSet
    click Uri href "../Uri"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sdoh_inCodeSet](../slots/sdoh_inCodeSet.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | A [[CategoryCodeSet]] that contains this category code | direct |
| [sdoh_codeValue](../slots/sdoh_codeValue.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | A short textual code that uniquely identifies the value | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohService](../classes/SdohService.md) | [sdoh_category](../slots/sdoh_category.md) | any_of[range] | [SdohCategoryCode](../classes/SdohCategoryCode.md) |







## Examples

| Value |
| --- |
| dreamkg:category/service/main/UnderstandMentalHealth |

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
| self | sdoh:CategoryCode |
| native | dream-kg/:SdohCategoryCode |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_CategoryCode
description: A Category Code.
title: CategoryCode
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 157 instances of this class.
examples:
- value: dreamkg:category/service/main/UnderstandMentalHealth
from_schema: dream-kg
slots:
- sdoh_inCodeSet
- sdoh_codeValue
class_uri: sdoh:CategoryCode

```
</details>

### Induced

<details>
```yaml
name: sdoh_CategoryCode
description: A Category Code.
title: CategoryCode
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 157 instances of this class.
examples:
- value: dreamkg:category/service/main/UnderstandMentalHealth
from_schema: dream-kg
attributes:
  sdoh_inCodeSet:
    name: sdoh_inCodeSet
    description: A [[CategoryCodeSet]] that contains this category code.
    title: inCodeSet
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 157 occurrences with subject type sdoh_CategoryCode and object type uri.
    examples:
    - value: dreamkg:category/service/main/Treatment sdoh:inCodeSet dreamkg:_CategoryCodeSet_Services_Main
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:inCodeSet
    alias: sdoh_inCodeSet
    owner: sdoh_CategoryCode
    domain_of:
    - sdoh_CategoryCode
    range: uri
  sdoh_codeValue:
    name: sdoh_codeValue
    description: A short textual code that uniquely identifies the value.
    title: codeValue
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 158 occurrences with subject type sdoh_CategoryCode and object type string.
    examples:
    - value: dreamkg:category/service/main/CounselingMedicalCare sdoh:codeValue counseling
        medical care
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:codeValue
    alias: sdoh_codeValue
    owner: sdoh_CategoryCode
    domain_of:
    - sdoh_CategoryCode
    range: string
class_uri: sdoh:CategoryCode

```
</details>