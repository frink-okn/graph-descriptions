

# Class: Organization (hsdo_Organization)


_An organization such as a school, NGO, corporation, club, etc._





URI: [hsdo:Organization](hsdo:Organization)






```mermaid
 classDiagram
    class HsdoOrganization
    click HsdoOrganization href "../HsdoOrganization"
      HsdoOrganization : hsdo_name
        
          
    
    
    HsdoOrganization --> "0..1" String : hsdo_name
    click String href "../String"

        
      HsdoOrganization : hsdo_sameAs
        
          
    
    
    HsdoOrganization --> "0..1" Uri : hsdo_sameAs
    click Uri href "../Uri"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [hsdo_sameAs](../slots/hsdo_sameAs.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) | No slot (predicate) description specified | direct |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | [hsdo_provider](../slots/hsdo_provider.md) | range | [HsdoOrganization](../classes/HsdoOrganization.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:Organization |
| native | dream-kg/:HsdoOrganization |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: hsdo_Organization
description: An organization such as a school, NGO, corporation, club, etc.
title: Organization
notes:
- Class with 87 occurrences.
from_schema: dream-kg
rank: 1000
slots:
- hsdo_sameAs
- hsdo_name
class_uri: hsdo:Organization

```
</details>

### Induced

<details>
```yaml
name: hsdo_Organization
description: An organization such as a school, NGO, corporation, club, etc.
title: Organization
notes:
- Class with 87 occurrences.
from_schema: dream-kg
rank: 1000
attributes:
  hsdo_sameAs:
    name: hsdo_sameAs
    description: No slot (predicate) description specified
    comments:
    - 127 occurrences with subject type hsdo_Organization and object type uri.
    examples:
    - description: hsdo_Organization → uri
      object:
        example_object: https://www.facebook.com/NorthEastTreatmentCenters/
        example_predicate: hsdo:sameAs
        example_subject: dreamkg:service/provider/6378689670414336
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:sameAs
    alias: hsdo_sameAs
    owner: hsdo_Organization
    domain_of:
    - hsdo_Organization
    range: uri
  hsdo_name:
    name: hsdo_name
    description: No slot (predicate) description specified
    comments:
    - 88 occurrences with subject type hsdo_Service and object type string.
    - 89 occurrences with subject type hsdo_Organization and object type string.
    examples:
    - description: hsdo_Service → string
      object:
        example_object: Emergency Shelter
        example_predicate: hsdo:name
        example_subject: dreamkg:service/5398794886447104
    - description: hsdo_Organization → string
      object:
        example_object: Belmont Behavioral Health System
        example_predicate: hsdo:name
        example_subject: dreamkg:service/provider/4829363626049536
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:name
    alias: hsdo_name
    owner: hsdo_Organization
    domain_of:
    - hsdo_Organization
    - hsdo_Service
    range: string
class_uri: hsdo:Organization

```
</details>