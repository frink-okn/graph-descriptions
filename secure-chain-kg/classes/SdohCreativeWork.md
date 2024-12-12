

# Class: CreativeWork (sdoh_CreativeWork)


_The most generic kind of creative work, including books, movies, photographs, software programs, etc._





URI: [sdoh:CreativeWork](http://schema.org/CreativeWork)






```mermaid
 classDiagram
    class SdohCreativeWork
    click SdohCreativeWork href "../SdohCreativeWork"
      SdohCreativeWork <|-- SecurechainLicense
        click SecurechainLicense href "../SecurechainLicense"
      
      SdohCreativeWork : sdoh_identifier
        
          
    
    
    SdohCreativeWork --> "0..1" String : sdoh_identifier
    click String href "../String"

        
      SdohCreativeWork : sdoh_name
        
          
    
    
    SdohCreativeWork --> "0..1" String : sdoh_name
    click String href "../String"

        
      
```





## Inheritance
* **SdohCreativeWork**
    * [SecurechainLicense](../classes/SecurechainLicense.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sdoh_identifier](../slots/sdoh_identifier.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [sdoh_name](../slots/sdoh_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |










## Examples

| Value |
| --- |
| securechain:License/gpl-3.0 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:CreativeWork |
| native | secure-chain-kg/:SdohCreativeWork |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_CreativeWork
description: The most generic kind of creative work, including books, movies, photographs,
  software programs, etc.
title: CreativeWork
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 20 occurences.
examples:
- value: securechain:License/gpl-3.0
from_schema: secure-chain-kg
rank: 1000
slots:
- sdoh_identifier
- sdoh_name
class_uri: sdoh:CreativeWork

```
</details>

### Induced

<details>
```yaml
name: sdoh_CreativeWork
description: The most generic kind of creative work, including books, movies, photographs,
  software programs, etc.
title: CreativeWork
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 20 occurences.
examples:
- value: securechain:License/gpl-3.0
from_schema: secure-chain-kg
rank: 1000
attributes:
  sdoh_identifier:
    name: sdoh_identifier
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 259334 occurrences with subject type securechain_Vulnerability and object type
      string.
    - 30434 occurrences with subject type sdoh_Person and object type string.
    - 445 occurrences with subject type securechain_VulnerabilityType and object type
      string.
    - 887 occurrences with subject type sdoh_Organization and object type string.
    - 20 occurrences with subject type sdoh_CreativeWork and object type string.
    examples:
    - value: securechain:Vulnerability/CVE-2019-9484 sdoh:identifier CVE-2019-9484
    - value: schema:Person/rncbc sdoh:identifier rncbc
    - value: securechain:VulnerabilityType/CWE-228 sdoh:identifier CWE-228
    - value: schema:Organization/Jgraph sdoh:identifier Q59339175
    - value: securechain:License/mpl-2.0 sdoh:identifier mpl-2.0
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: sdoh:identifier
    alias: sdoh_identifier
    owner: sdoh_CreativeWork
    domain_of:
    - sdoh_CreativeWork
    - sdoh_Organization
    - sdoh_Person
    - securechain_Vulnerability
    - securechain_VulnerabilityType
    range: string
  sdoh_name:
    name: sdoh_name
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 53378 occurrences with subject type securechain_Hardware and object type string.
    - 22002 occurrences with subject type sdoh_Organization and object type string.
    - 34469 occurrences with subject type securechain_Software and object type string.
    - 20 occurrences with subject type sdoh_CreativeWork and object type string.
    examples:
    - value: securechain:Hardware/nvr1xxx sdoh:name nvr1xxx
    - value: schema:Organization/opencaching sdoh:name opencaching
    - value: securechain:Software/libdime sdoh:name libdime
    - value: securechain:License/mit sdoh:name MIT License
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: sdoh:name
    alias: sdoh_name
    owner: sdoh_CreativeWork
    domain_of:
    - sdoh_CreativeWork
    - sdoh_Organization
    - securechain_Hardware
    - securechain_Software
    range: string
class_uri: sdoh:CreativeWork

```
</details>