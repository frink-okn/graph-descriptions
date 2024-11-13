

# Class: TODO -- what's a good name for what this class (type) describes? (securechain_SoftwareVersion)


_TODO -- tell the world what this class (type) describes._





URI: [securechain:SoftwareVersion](https://w3id.org/secure-chain/SoftwareVersion)






```mermaid
 classDiagram
    class SecurechainSoftwareVersion
    click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"
      SecurechainSoftwareVersion : securechain_dependsOn
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" Any : securechain_dependsOn
    click Any href "../Any"

        
      SecurechainSoftwareVersion : securechain_versionName
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" String : securechain_versionName
    click String href "../String"

        
      SecurechainSoftwareVersion : securechain_vulnerableTo
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" Any : securechain_vulnerableTo
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [securechain_dependsOn](../slots/securechain_dependsOn.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | TODO -- tell the world what this slot (predicate) describes | direct |
| [securechain_vulnerableTo](../slots/securechain_vulnerableTo.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SecurechainVulnerability](../classes/SecurechainVulnerability.md)&nbsp;or&nbsp;<br />[SecurechainVulnerability](../classes/SecurechainVulnerability.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [securechain_versionName](../slots/securechain_versionName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_dependsOn](../slots/securechain_dependsOn.md) | any_of[range] | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |







## Examples

| Value |
| --- |
| securechain:SoftwareVersion/vcftools#0.1.9-1 |

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
| self | securechain:SoftwareVersion |
| native | secure-chain-kg/develop/:SecurechainSoftwareVersion |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: securechain_SoftwareVersion
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 164001 instances of this class.
examples:
- value: securechain:SoftwareVersion/vcftools#0.1.9-1
from_schema: secure-chain-kg/develop
slots:
- securechain_dependsOn
- securechain_vulnerableTo
- securechain_versionName
class_uri: securechain:SoftwareVersion

```
</details>

### Induced

<details>
```yaml
name: securechain_SoftwareVersion
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 164001 instances of this class.
examples:
- value: securechain:SoftwareVersion/vcftools#0.1.9-1
from_schema: secure-chain-kg/develop
attributes:
  securechain_dependsOn:
    name: securechain_dependsOn
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 696916 occurrences with subject type securechain_SoftwareVersion and object
      type securechain_SoftwareVersion.
    - 2 occurrences with subject type securechain_SoftwareVersion and object type
      uri.
    - 982961 occurrences on untyped entities with type securechain_SoftwareVersion.
    - 39 occurrences on untyped entities with datatype uri.
    examples:
    - value: securechain:SoftwareVersion/anymeal#1.31-1 securechain:dependsOn securechain:SoftwareVersion/libqt5widgets5t64#%3E%3D+5.0.2
    - value: securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2 securechain:dependsOn
        securechain:SoftwareVersion/dosbox#0.74-2
    from_schema: secure-chain-kg/develop
    rank: 1000
    slot_uri: securechain:dependsOn
    alias: securechain_dependsOn
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_SoftwareVersion
    range: Any
    any_of:
    - range: securechain_SoftwareVersion
    - range: uri
  securechain_vulnerableTo:
    name: securechain_vulnerableTo
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 445386 occurrences with subject type securechain_HardwareVersion and object
      type securechain_Vulnerability.
    - 5067 occurrences with subject type securechain_SoftwareVersion and object type
      securechain_Vulnerability.
    - 21897 occurrences on untyped entities with type securechain_Vulnerability.
    examples:
    - value: securechain:HardwareVersion/xeon_e5-2699r_v4#- securechain:vulnerableTo
        securechain:Vulnerability/CVE-2021-0114
    - value: securechain:SoftwareVersion/mapserver#4.10.0-5%2Betch1 securechain:vulnerableTo
        securechain:Vulnerability/CVE-2009-0839
    from_schema: secure-chain-kg/develop
    rank: 1000
    slot_uri: securechain:vulnerableTo
    alias: securechain_vulnerableTo
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_HardwareVersion
    - securechain_SoftwareVersion
    range: Any
    any_of:
    - range: securechain_Vulnerability
    - range: securechain_Vulnerability
  securechain_versionName:
    name: securechain_versionName
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 164001 occurrences with subject type securechain_SoftwareVersion and object
      type string.
    - 57295 occurrences with subject type securechain_HardwareVersion and object type
      string.
    examples:
    - value: securechain:SoftwareVersion/gee-0.8#0.8 securechain:versionName 0.8
    - value: securechain:HardwareVersion/wsr-600dhp#- securechain:versionName -
    from_schema: secure-chain-kg/develop
    rank: 1000
    slot_uri: securechain:versionName
    alias: securechain_versionName
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_HardwareVersion
    - securechain_SoftwareVersion
    range: string
class_uri: securechain:SoftwareVersion

```
</details>