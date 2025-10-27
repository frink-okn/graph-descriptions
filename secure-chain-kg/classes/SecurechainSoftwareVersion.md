

# Class: SecurechainSoftwareVersion




This class occurs 8593149 times.


URI: [securechain:SoftwareVersion](https://w3id.org/secure-chain/SoftwareVersion)






```mermaid
 classDiagram
    class SecurechainSoftwareVersion
    click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"
      SecurechainSoftware <|-- SecurechainSoftwareVersion
        click SecurechainSoftware href "../SecurechainSoftware"
      
      SecurechainSoftwareVersion : sdos_contributor
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" Any : sdos_contributor
    click Any href "../Any"

        
      SecurechainSoftwareVersion : sdos_identifier
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" Any : sdos_identifier
    click Any href "../Any"

        
      SecurechainSoftwareVersion : sdos_license
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" Any : sdos_license
    click Any href "../Any"

        
      SecurechainSoftwareVersion : sdos_manufacturer
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SdosOrganization : sdos_manufacturer
    click SdosOrganization href "../SdosOrganization"

        
      SecurechainSoftwareVersion : sdos_name
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SdosText : sdos_name
    click SdosText href "../SdosText"

        
      SecurechainSoftwareVersion : sdos_programmingLanguage
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" Any : sdos_programmingLanguage
    click Any href "../Any"

        
      SecurechainSoftwareVersion : sdos_url
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SdosURL : sdos_url
    click SdosURL href "../SdosURL"

        
      SecurechainSoftwareVersion : securechain_dependsOn
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SecurechainSoftwareVersion : securechain_dependsOn
    click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"

        
      SecurechainSoftwareVersion : securechain_ecosystem
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" Any : securechain_ecosystem
    click Any href "../Any"

        
      SecurechainSoftwareVersion : securechain_hasHardwareVersion
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SecurechainHardwareVersion : securechain_hasHardwareVersion
    click SecurechainHardwareVersion href "../SecurechainHardwareVersion"

        
      SecurechainSoftwareVersion : securechain_hasSoftwareVersion
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SecurechainSoftwareVersion : securechain_hasSoftwareVersion
    click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"

        
      SecurechainSoftwareVersion : securechain_versionName
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" Any : securechain_versionName
    click Any href "../Any"

        
      SecurechainSoftwareVersion : securechain_vulnerableTo
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SecurechainVulnerability : securechain_vulnerableTo
    click SecurechainVulnerability href "../SecurechainVulnerability"

        
      
```





## Inheritance
* [SdosThing](../classes/SdosThing.md)
    * [SdosCreativeWork](../classes/SdosCreativeWork.md)
        * [SdosSoftwareApplication](../classes/SdosSoftwareApplication.md)
            * [SecurechainSoftware](../classes/SecurechainSoftware.md)
                * **SecurechainSoftwareVersion**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [securechain_versionName](../slots/securechain_versionName.md) | 0..1 <br/> [SdosText](../classes/SdosText.md)&nbsp;or&nbsp;<br />[xsd:string](xsd:string) |  <br/>  | direct | 8593148 |
| [sdos_url](../slots/sdos_url.md) | 0..1 <br/> [SdosURL](../classes/SdosURL.md) | URL of the item <br/>  | direct | 7733913 |
| [sdos_license](../slots/sdos_license.md) | 0..1 <br/> [SdosURL](../classes/SdosURL.md)&nbsp;or&nbsp;<br />[SdosCreativeWork](../classes/SdosCreativeWork.md) | A license document that applies to this content, typically indicated by URL <br/>  | direct | 5018025 |
| [securechain_dependsOn](../slots/securechain_dependsOn.md) | 0..1 <br/> [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |  <br/>  | direct | 29574574 |
| [securechain_vulnerableTo](../slots/securechain_vulnerableTo.md) | 0..1 <br/> [SecurechainVulnerability](../classes/SecurechainVulnerability.md) |  <br/>  | direct | 383356 |
| [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | 0..1 <br/> [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |  | [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |
| [securechain_ecosystem](../slots/securechain_ecosystem.md) | 0..1 <br/> [SdosText](../classes/SdosText.md)&nbsp;or&nbsp;<br />[xsd:string](xsd:string) |  | [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |
| [sdos_contributor](../slots/sdos_contributor.md) | 0..1 <br/> [SdosOrganization](../classes/SdosOrganization.md)&nbsp;or&nbsp;<br />[SdosPerson](../classes/SdosPerson.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI) | A secondary contributor to the CreativeWork or Event | [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |
| [sdos_name](../slots/sdos_name.md) | 0..1 <br/> [SdosText](../classes/SdosText.md) | The name of the item | [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |
| [sdos_programmingLanguage](../slots/sdos_programmingLanguage.md) | 0..1 <br/> [SdosComputerLanguage](../classes/SdosComputerLanguage.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md) | The computer programming language | [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |
| [sdos_identifier](../slots/sdos_identifier.md) | 0..1 <br/> [SdosURL](../classes/SdosURL.md)&nbsp;or&nbsp;<br />[SdosPropertyValue](../classes/SdosPropertyValue.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md) | The identifier property represents any kind of identifier for any kind of [[T... | [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |
| [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | 0..1 <br/> [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) |  | [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |
| [sdos_manufacturer](../slots/sdos_manufacturer.md) | 0..1 <br/> [SdosOrganization](../classes/SdosOrganization.md) | The manufacturer of the product | [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SecurechainHardware](../classes/SecurechainHardware.md) | [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | [securechain_vulnerableTo](../slots/securechain_vulnerableTo.md) | domain | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_dependsOn](../slots/securechain_dependsOn.md) | domain | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_dependsOn](../slots/securechain_dependsOn.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_vulnerableTo](../slots/securechain_vulnerableTo.md) | domain | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: securechain_SoftwareVersion
from_schema: okns:secure-chain-kg
rank: 1000
is_a: securechain_Software
slots:
- securechain_versionName
- sdos_url
- sdos_license
- securechain_dependsOn
- securechain_vulnerableTo
class_uri: securechain:SoftwareVersion

```
</details>

### Induced

<details>

```yaml
name: securechain_SoftwareVersion
from_schema: okns:secure-chain-kg
rank: 1000
is_a: securechain_Software
attributes:
  securechain_versionName:
    name: securechain_versionName
    from_schema: okns:secure-chain-kg
    rank: 1000
    slot_uri: securechain:versionName
    alias: securechain_versionName
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_HardwareVersion
    - securechain_SoftwareVersion
    range: Any
    any_of:
    - range: sdos_Text
    - range: string
  sdos_url:
    name: sdos_url
    description: URL of the item.
    title: url
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    domain: sdos_Thing
    slot_uri: sdos:url
    alias: sdos_url
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Software
    - securechain_SoftwareVersion
    range: sdos_URL
  sdos_license:
    name: sdos_license
    description: A license document that applies to this content, typically indicated
      by URL.
    title: license
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    domain: sdos_CreativeWork
    slot_uri: sdos:license
    alias: sdos_license
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_SoftwareVersion
    range: Any
    any_of:
    - range: sdos_URL
    - range: sdos_CreativeWork
  securechain_dependsOn:
    name: securechain_dependsOn
    from_schema: okns:secure-chain-kg
    rank: 1000
    domain: securechain_SoftwareVersion
    slot_uri: securechain:dependsOn
    alias: securechain_dependsOn
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_SoftwareVersion
    range: securechain_SoftwareVersion
  securechain_vulnerableTo:
    name: securechain_vulnerableTo
    from_schema: okns:secure-chain-kg
    rank: 1000
    domain: securechain_SoftwareVersion
    slot_uri: securechain:vulnerableTo
    alias: securechain_vulnerableTo
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_HardwareVersion
    - securechain_SoftwareVersion
    range: securechain_Vulnerability
  securechain_hasSoftwareVersion:
    name: securechain_hasSoftwareVersion
    from_schema: okns:secure-chain-kg
    rank: 1000
    domain: securechain_Software
    slot_uri: securechain:hasSoftwareVersion
    alias: securechain_hasSoftwareVersion
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Hardware
    - securechain_Software
    range: securechain_SoftwareVersion
  securechain_ecosystem:
    name: securechain_ecosystem
    from_schema: okns:secure-chain-kg
    rank: 1000
    domain: securechain_Software
    slot_uri: securechain:ecosystem
    alias: securechain_ecosystem
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Hardware
    - securechain_Software
    range: Any
    any_of:
    - range: sdos_Text
    - range: string
  sdos_contributor:
    name: sdos_contributor
    description: A secondary contributor to the CreativeWork or Event.
    title: contributor
    from_schema: okns:sdo
    slot_uri: sdos:contributor
    alias: sdos_contributor
    owner: securechain_SoftwareVersion
    domain_of:
    - sdos_CarUsageType
    - sdos_DayOfWeek
    - sdos_DeliveryMethod
    - sdos_DriveWheelConfigurationValue
    - sdos_LegalForceStatus
    - sdos_LegalValueLevel
    - sdos_MusicAlbumProductionType
    - sdos_MusicAlbumReleaseType
    - sdos_MusicReleaseFormatType
    - sdos_SteeringPositionValue
    - securechain_Software
    union_of:
    - sdos_CreativeWork
    - sdos_Event
    range: Any
    any_of:
    - range: sdos_Organization
    - range: sdos_Person
    - range: uri
  sdos_name:
    name: sdos_name
    description: The name of the item.
    title: name
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    exact_mappings:
    - http://purl.org/dc/terms/title
    domain: sdos_Thing
    slot_uri: sdos:name
    alias: sdos_name
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Hardware
    - securechain_License
    - securechain_Software
    subproperty_of: rdfs_label
    range: sdos_Text
  sdos_programmingLanguage:
    name: sdos_programmingLanguage
    description: The computer programming language.
    title: programmingLanguage
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    domain: sdos_SoftwareSourceCode
    slot_uri: sdos:programmingLanguage
    alias: sdos_programmingLanguage
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Hardware
    - securechain_Software
    range: Any
    any_of:
    - range: sdos_ComputerLanguage
    - range: sdos_Text
  sdos_identifier:
    name: sdos_identifier
    description: The identifier property represents any kind of identifier for any
      kind of [[Thing]], such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides
      dedicated properties for representing many of these, either as textual strings
      or as URL (URI) links. See [background notes](/docs/datamodel.html#identifierBg)
      for more details.
    title: identifier
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    exact_mappings:
    - http://purl.org/dc/terms/identifier
    domain: sdos_Thing
    slot_uri: sdos:identifier
    alias: sdos_identifier
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_License
    - securechain_Software
    - securechain_Vulnerability
    - securechain_VulnerabilityType
    range: Any
    any_of:
    - range: sdos_URL
    - range: sdos_PropertyValue
    - range: sdos_Text
  securechain_hasHardwareVersion:
    name: securechain_hasHardwareVersion
    from_schema: okns:secure-chain-kg
    rank: 1000
    domain: securechain_Hardware
    slot_uri: securechain:hasHardwareVersion
    alias: securechain_hasHardwareVersion
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Hardware
    - securechain_Software
    range: securechain_HardwareVersion
  sdos_manufacturer:
    name: sdos_manufacturer
    description: The manufacturer of the product.
    title: manufacturer
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:sdo
    domain: sdos_Product
    slot_uri: sdos:manufacturer
    alias: sdos_manufacturer
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Hardware
    - securechain_Software
    range: sdos_Organization
class_uri: securechain:SoftwareVersion

```
</details>