

# Class: TODO -- what's a good name for what this class (type) describes? (sdoh_Person)


_TODO -- tell the world what this class (type) describes._





URI: [sdoh:Person](http://schema.org/Person)






```mermaid
 classDiagram
    class SdohPerson
    click SdohPerson href "../SdohPerson"
      SdohPerson : sdoh_identifier
        
          
    
    
    SdohPerson --> "0..1" String : sdoh_identifier
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
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | [sdoh_contributor](../slots/sdoh_contributor.md) | range | [SdohPerson](../classes/SdohPerson.md) |







## Examples

| Value |
| --- |
| schema:Person/johnlunney |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg/develop




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:Person |
| native | secure-chain-kg/develop/:SdohPerson |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_Person
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 30434 instances of this class.
examples:
- value: schema:Person/johnlunney
from_schema: secure-chain-kg/develop
slots:
- sdoh_identifier
class_uri: sdoh:Person

```
</details>

### Induced

<details>
```yaml
name: sdoh_Person
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 30434 instances of this class.
examples:
- value: schema:Person/johnlunney
from_schema: secure-chain-kg/develop
attributes:
  sdoh_identifier:
    name: sdoh_identifier
    description: TODO -- tell the world what this slot (predicate) describes.
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
    - value: securechain:Vulnerability/CVE-2023-52458 sdoh:identifier CVE-2023-52458
    - value: schema:Person/Touhou-fan sdoh:identifier Touhou-fan
    - value: securechain:VulnerabilityType/CWE-842 sdoh:identifier CWE-842
    - value: schema:Organization/Basecamp sdoh:identifier Q36908
    - value: securechain:License/bsl-1.0 sdoh:identifier bsl-1.0
    from_schema: secure-chain-kg/develop
    rank: 1000
    slot_uri: sdoh:identifier
    alias: sdoh_identifier
    owner: sdoh_Person
    domain_of:
    - securechain_Vulnerability
    - securechain_VulnerabilityType
    - sdoh_CreativeWork
    - sdoh_Organization
    - sdoh_Person
    range: string
class_uri: sdoh:Person

```
</details>