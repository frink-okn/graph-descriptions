

# Class: CreativeWork (hsdo_CreativeWork)


_The most generic kind of creative work, including books, movies, photographs, software programs, etc._






This class occurs 20 times.


URI: [hsdo:CreativeWork](http://schema.org/CreativeWork)






```mermaid
 classDiagram
    class HsdoCreativeWork
    click HsdoCreativeWork href "../HsdoCreativeWork"
      HsdoCreativeWork <|-- SecurechainLicense
        click SecurechainLicense href "../SecurechainLicense"
      
      HsdoCreativeWork : hsdo_identifier
        
          
    
    
    HsdoCreativeWork --> "0..1" String : hsdo_identifier
    click String href "../String"

        
      HsdoCreativeWork : hsdo_name
        
          
    
    
    HsdoCreativeWork --> "0..1" String : hsdo_name
    click String href "../String"

        
      
```





## Inheritance
* **HsdoCreativeWork**
    * [SecurechainLicense](../classes/SecurechainLicense.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | The name of the item <br/>  | direct | 20 |
| [hsdo_identifier](../slots/hsdo_identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | The identifier property represents any kind of identifier for any kind of [[T... <br/>  | direct | 20 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: hsdo_CreativeWork
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 20
description: The most generic kind of creative work, including books, movies, photographs,
  software programs, etc.
title: CreativeWork
from_schema: secure-chain-kg
rank: 1000
slots:
- hsdo_name
- hsdo_identifier
slot_usage:
  hsdo_identifier:
    name: hsdo_identifier
    annotations:
      string:
        tag: string
        value: 20
  hsdo_name:
    name: hsdo_name
    annotations:
      string:
        tag: string
        value: 20
class_uri: hsdo:CreativeWork

```
</details>

### Induced

<details>

```yaml
name: hsdo_CreativeWork
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 20
description: The most generic kind of creative work, including books, movies, photographs,
  software programs, etc.
title: CreativeWork
from_schema: secure-chain-kg
rank: 1000
slot_usage:
  hsdo_identifier:
    name: hsdo_identifier
    annotations:
      string:
        tag: string
        value: 20
  hsdo_name:
    name: hsdo_name
    annotations:
      string:
        tag: string
        value: 20
attributes:
  hsdo_name:
    name: hsdo_name
    annotations:
      string:
        tag: string
        value: 20
    description: The name of the item.
    title: name
    examples:
    - object:
        example_object: '-'
        example_object_type: string
        example_predicate: hsdo:name
        example_subject: securechain:Hardware/-
        example_subject_type: securechain_Hardware
    - object:
        example_object: '%240.99_kindle_books_project'
        example_object_type: string
        example_predicate: hsdo:name
        example_subject: schema:Organization/%25240.99_kindle_books_project
        example_subject_type: hsdo_Organization
    - object:
        example_object: Permission to use, copy, modify, and/or distribute this software
          for any
        example_object_type: string
        example_predicate: hsdo:name
        example_subject: securechain:License/0bsd
        example_subject_type: hsdo_CreativeWork
    - object:
        example_object: ''
        example_object_type: string
        example_predicate: hsdo:name
        example_subject: securechain:Software/
        example_subject_type: securechain_Software
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: hsdo:name
    alias: hsdo_name
    owner: hsdo_CreativeWork
    domain_of:
    - hsdo_CreativeWork
    - hsdo_Organization
    - securechain_Hardware
    - securechain_Software
    range: string
  hsdo_identifier:
    name: hsdo_identifier
    annotations:
      string:
        tag: string
        value: 20
    description: 'The identifier property represents any kind of identifier for any
      kind of [[Thing]], such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides
      dedicated properties for representing many of these, either as textual strings
      or as URL (URI) links. See [background notes](/docs/datamodel.html#identifierBg)
      for more details.␊        '
    title: identifier
    examples:
    - object:
        example_object: 0----0
        example_object_type: string
        example_predicate: hsdo:identifier
        example_subject: schema:Person/0----0
        example_subject_type: hsdo_Person
    - object:
        example_object: CVE-1999-0043
        example_object_type: string
        example_predicate: hsdo:identifier
        example_subject: securechain:Vulnerability/CVE-1999-0043
        example_subject_type: securechain_Vulnerability
    - object:
        example_object: CWE-1
        example_object_type: string
        example_predicate: hsdo:identifier
        example_subject: securechain:VulnerabilityType/CWE-1
        example_subject_type: securechain_VulnerabilityType
    - object:
        example_object: Q2150861
        example_object_type: string
        example_predicate: hsdo:identifier
        example_subject: schema:Organization/1Password
        example_subject_type: hsdo_Organization
    - object:
        example_object: 0bsd
        example_object_type: string
        example_predicate: hsdo:identifier
        example_subject: securechain:License/0bsd
        example_subject_type: hsdo_CreativeWork
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: hsdo:identifier
    alias: hsdo_identifier
    owner: hsdo_CreativeWork
    domain_of:
    - hsdo_CreativeWork
    - hsdo_Organization
    - hsdo_Person
    - securechain_Vulnerability
    - securechain_VulnerabilityType
    range: string
class_uri: hsdo:CreativeWork

```
</details>