

# Class: TODO -- what's a good name for this class (type)? (securechain_SoftwareVersion)


_No type description provided_





URI: [securechain:SoftwareVersion](https://w3id.org/secure-chain/SoftwareVersion)






```mermaid
 classDiagram
    class SecurechainSoftwareVersion
    click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"
      SecurechainSoftware <|-- SecurechainSoftwareVersion
        click SecurechainSoftware href "../SecurechainSoftware"
      
      SecurechainSoftwareVersion : sdoh_contributor
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SdohPerson : sdoh_contributor
    click SdohPerson href "../SdohPerson"

        
      SecurechainSoftwareVersion : sdoh_name
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" String : sdoh_name
    click String href "../String"

        
      SecurechainSoftwareVersion : securechain_dependsOn
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" Any : securechain_dependsOn
    click Any href "../Any"

        
      SecurechainSoftwareVersion : securechain_hasSoftwareVersion
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SecurechainSoftwareVersion : securechain_hasSoftwareVersion
    click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"

        
      SecurechainSoftwareVersion : securechain_versionName
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" String : securechain_versionName
    click String href "../String"

        
      SecurechainSoftwareVersion : securechain_vulnerableTo
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SecurechainVulnerability : securechain_vulnerableTo
    click SecurechainVulnerability href "../SecurechainVulnerability"

        
      
```





## Inheritance
* [SdohSoftwareApplication](../classes/SdohSoftwareApplication.md)
    * [SecurechainSoftware](../classes/SecurechainSoftware.md)
        * **SecurechainSoftwareVersion**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [securechain_dependsOn](../slots/securechain_dependsOn.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No slot description provided | direct |
| [securechain_vulnerableTo](../slots/securechain_vulnerableTo.md) | 0..1 <br/> [SecurechainVulnerability](../classes/SecurechainVulnerability.md) | No slot description provided | direct |
| [securechain_versionName](../slots/securechain_versionName.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | 0..1 <br/> [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No slot description provided | [SecurechainSoftware](../classes/SecurechainSoftware.md) |
| [sdoh_contributor](../slots/sdoh_contributor.md) | 0..1 <br/> [SdohPerson](../classes/SdohPerson.md) | No slot description provided | [SecurechainSoftware](../classes/SecurechainSoftware.md) |
| [sdoh_name](../slots/sdoh_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | [SecurechainSoftware](../classes/SecurechainSoftware.md) |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_dependsOn](../slots/securechain_dependsOn.md) | any_of[range] | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |







## Examples

| Value |
| --- |
| securechain:SoftwareVersion/kdoctools#5.103.0-1 |

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
| self | securechain:SoftwareVersion |
| native | secure-chain-kg/:SecurechainSoftwareVersion |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: securechain_SoftwareVersion
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 164001 occurences.
examples:
- value: securechain:SoftwareVersion/kdoctools#5.103.0-1
from_schema: secure-chain-kg
rank: 1000
is_a: securechain_Software
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
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 164001 occurences.
examples:
- value: securechain:SoftwareVersion/kdoctools#5.103.0-1
from_schema: secure-chain-kg
rank: 1000
is_a: securechain_Software
attributes:
  securechain_dependsOn:
    name: securechain_dependsOn
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 696916 occurrences with subject type securechain_SoftwareVersion and object
      type securechain_SoftwareVersion.
    - 982961 occurrences with untyped subjects and object type https://w3id.org/secure-chain/SoftwareVersion.
    - 39 occurrences with untyped subjects and object type uri.
    - 2 occurrences with subject type securechain_SoftwareVersion and object type
      uri.
    examples:
    - value: securechain:SoftwareVersion/RedPanda-CPP#1.0.6 securechain:dependsOn
        securechain:SoftwareVersion/debhelper#%3D12~
    - value: securechain:SoftwareVersion/dde-qt5integration#5.5.23-1build3 securechain:dependsOn
        securechain:SoftwareVersion/libqt5x11extras5#%3E%3D+5.6.0
    - value: securechain:SoftwareVersion/kstars#4%3A3.5.5-1 securechain:dependsOn
        securechain:SoftwareVersion/indi#4%3A3.5.5-1
    - value: securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2 securechain:dependsOn
        securechain:SoftwareVersion/dosbox#0.74-2
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:dependsOn
    alias: securechain_dependsOn
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_SoftwareVersion
    range: Any
    any_of:
    - range: uri
    - range: securechain_SoftwareVersion
  securechain_vulnerableTo:
    name: securechain_vulnerableTo
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 445386 occurrences with subject type securechain_HardwareVersion and object
      type securechain_Vulnerability.
    - 21897 occurrences with untyped subjects and object type https://w3id.org/secure-chain/Vulnerability.
    - 5067 occurrences with subject type securechain_SoftwareVersion and object type
      securechain_Vulnerability.
    examples:
    - value: securechain:HardwareVersion/x12dpl-i6#- securechain:vulnerableTo securechain:Vulnerability/CVE-2023-33412
    - value: securechain:HardwareVersion/wireless-n_7260#- securechain:vulnerableTo
        securechain:Vulnerability/CVE-2018-12177
    - value: securechain:SoftwareVersion/freetype#2.2.1-5 securechain:vulnerableTo
        securechain:Vulnerability/CVE-2011-0226
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:vulnerableTo
    alias: securechain_vulnerableTo
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_HardwareVersion
    - securechain_SoftwareVersion
    range: securechain_Vulnerability
  securechain_versionName:
    name: securechain_versionName
    description: No slot description provided
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
    - value: securechain:SoftwareVersion/libaudcore5#%3E%3D+3.9 securechain:versionName
        >= 3.9
    - value: securechain:HardwareVersion/vantage_velocity#- securechain:versionName
        -
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:versionName
    alias: securechain_versionName
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_HardwareVersion
    - securechain_SoftwareVersion
    range: string
  securechain_hasSoftwareVersion:
    name: securechain_hasSoftwareVersion
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 164001 occurrences with subject type securechain_Software and object type securechain_SoftwareVersion.
    examples:
    - value: securechain:Software/intel-vaapi-driver securechain:hasSoftwareVersion
        securechain:SoftwareVersion/intel-vaapi-driver#1.0.17-1
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:hasSoftwareVersion
    alias: securechain_hasSoftwareVersion
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Software
    range: securechain_SoftwareVersion
  sdoh_contributor:
    name: sdoh_contributor
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 33048 occurrences with subject type securechain_Software and object type sdoh_Person.
    - 3668 occurrences with untyped subjects and object type http://schema.org/Person.
    examples:
    - value: securechain:Software/cuml sdoh:contributor schema:Person/minseokl
    - value: securechain:Software/velox sdoh:contributor schema:Person/DavidSGK
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: sdoh:contributor
    alias: sdoh_contributor
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Software
    range: sdoh_Person
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
    owner: securechain_SoftwareVersion
    domain_of:
    - sdoh_CreativeWork
    - sdoh_Organization
    - securechain_Hardware
    - securechain_Software
    range: string
class_uri: securechain:SoftwareVersion

```
</details>