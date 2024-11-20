

# Class: AdministrativeArea (sdoh_AdministrativeArea)


_A geographical region, typically under the jurisdiction of a particular government._





URI: [sdoh:AdministrativeArea](http://schema.org/AdministrativeArea)






```mermaid
 classDiagram
    class SdohAdministrativeArea
    click SdohAdministrativeArea href "../SdohAdministrativeArea"
      SdohAdministrativeArea : sdoh_identifier
        
          
    
    
    SdohAdministrativeArea --> "0..1" String : sdoh_identifier
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sdoh_identifier](../slots/sdoh_identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohPlace](../classes/SdohPlace.md) | [sdoh_containedInPlace](../slots/sdoh_containedInPlace.md) | range | [SdohAdministrativeArea](../classes/SdohAdministrativeArea.md) |







## Examples

| Value |
| --- |
| dreamkg:zip/19013 |

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
| self | sdoh:AdministrativeArea |
| native | dream-kg/:SdohAdministrativeArea |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_AdministrativeArea
description: A geographical region, typically under the jurisdiction of a particular
  government.
title: AdministrativeArea
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 39 occurences.
examples:
- value: dreamkg:zip/19013
from_schema: dream-kg
slots:
- sdoh_identifier
class_uri: sdoh:AdministrativeArea

```
</details>

### Induced

<details>
```yaml
name: sdoh_AdministrativeArea
description: A geographical region, typically under the jurisdiction of a particular
  government.
title: AdministrativeArea
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 39 occurences.
examples:
- value: dreamkg:zip/19013
from_schema: dream-kg
attributes:
  sdoh_identifier:
    name: sdoh_identifier
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 39 occurrences with subject type sdoh_AdministrativeArea and object type string.
    - 87 occurrences with subject type sdoh_Service and object type string.
    examples:
    - value: dreamkg:zip/19120 sdoh:identifier 19120
    - value: dreamkg:service/5398794886447104 sdoh:identifier 5398794886447104
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:identifier
    alias: sdoh_identifier
    owner: sdoh_AdministrativeArea
    domain_of:
    - sdoh_AdministrativeArea
    - sdoh_Service
    range: string
class_uri: sdoh:AdministrativeArea

```
</details>