

# Class: SecurechainHardware




This class occurs 53378 times.


URI: [securechain:Hardware](https://w3id.org/secure-chain/Hardware)






```mermaid
 classDiagram
    class SecurechainHardware
    click SecurechainHardware href "../SecurechainHardware"
      SdosProduct <|-- SecurechainHardware
        click SdosProduct href "../SdosProduct"
      

      SecurechainHardware <|-- SecurechainHardwareVersion
        click SecurechainHardwareVersion href "../SecurechainHardwareVersion"
      
      
      SecurechainHardware : sdos_manufacturer
        
          
    
    
    SecurechainHardware --> "0..1" SdosOrganization : sdos_manufacturer
    click SdosOrganization href "../SdosOrganization"

        
      SecurechainHardware : sdos_name
        
          
    
    
    SecurechainHardware --> "0..1" SdosText : sdos_name
    click SdosText href "../SdosText"

        
      SecurechainHardware : sdos_programmingLanguage
        
          
    
    
    SecurechainHardware --> "0..1" Any : sdos_programmingLanguage
    click Any href "../Any"

        
      SecurechainHardware : securechain_ecosystem
        
          
    
    
    SecurechainHardware --> "0..1" Any : securechain_ecosystem
    click Any href "../Any"

        
      SecurechainHardware : securechain_hasHardwareVersion
        
          
    
    
    SecurechainHardware --> "0..1" SecurechainHardwareVersion : securechain_hasHardwareVersion
    click SecurechainHardwareVersion href "../SecurechainHardwareVersion"

        
      SecurechainHardware : securechain_hasSoftwareVersion
        
          
    
    
    SecurechainHardware --> "0..1" SecurechainSoftwareVersion : securechain_hasSoftwareVersion
    click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"

        
      
```





## Inheritance
* [SdosThing](../classes/SdosThing.md)
    * [SdosProduct](../classes/SdosProduct.md)
        * **SecurechainHardware**
            * [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | 0..1 <br/> [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |  <br/>  | direct | 73 |
| [securechain_ecosystem](../slots/securechain_ecosystem.md) | 0..1 <br/> [SdosText](../classes/SdosText.md)&nbsp;or&nbsp;<br />[xsd:string](xsd:string) |  <br/>  | direct | 22 |
| [sdos_name](../slots/sdos_name.md) | 0..1 <br/> [SdosText](../classes/SdosText.md) | The name of the item <br/>  | direct | 53378 |
| [sdos_programmingLanguage](../slots/sdos_programmingLanguage.md) | 0..1 <br/> [SdosComputerLanguage](../classes/SdosComputerLanguage.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md) | The computer programming language <br/>  | direct | 22 |
| [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | 0..1 <br/> [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) |  <br/>  | direct | 57295 |
| [sdos_manufacturer](../slots/sdos_manufacturer.md) | 0..1 <br/> [SdosOrganization](../classes/SdosOrganization.md) | The manufacturer of the product <br/>  | direct | 57993 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SecurechainHardware](../classes/SecurechainHardware.md) | [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | domain | [SecurechainHardware](../classes/SecurechainHardware.md) |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | domain | [SecurechainHardware](../classes/SecurechainHardware.md) |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | domain | [SecurechainHardware](../classes/SecurechainHardware.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | domain | [SecurechainHardware](../classes/SecurechainHardware.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: securechain_Hardware
from_schema: okns:secure-chain-kg
rank: 1000
is_a: sdos_Product
slots:
- securechain_hasSoftwareVersion
- securechain_ecosystem
- sdos_name
- sdos_programmingLanguage
- securechain_hasHardwareVersion
- sdos_manufacturer
class_uri: securechain:Hardware

```
</details>

### Induced

<details>

```yaml
name: securechain_Hardware
from_schema: okns:secure-chain-kg
rank: 1000
is_a: sdos_Product
attributes:
  securechain_hasSoftwareVersion:
    name: securechain_hasSoftwareVersion
    from_schema: okns:secure-chain-kg
    rank: 1000
    domain: securechain_Software
    slot_uri: securechain:hasSoftwareVersion
    alias: securechain_hasSoftwareVersion
    owner: securechain_Hardware
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
    owner: securechain_Hardware
    domain_of:
    - securechain_Hardware
    - securechain_Software
    range: Any
    any_of:
    - range: sdos_Text
    - range: string
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
    owner: securechain_Hardware
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
    owner: securechain_Hardware
    domain_of:
    - securechain_Hardware
    - securechain_Software
    range: Any
    any_of:
    - range: sdos_ComputerLanguage
    - range: sdos_Text
  securechain_hasHardwareVersion:
    name: securechain_hasHardwareVersion
    from_schema: okns:secure-chain-kg
    rank: 1000
    domain: securechain_Hardware
    slot_uri: securechain:hasHardwareVersion
    alias: securechain_hasHardwareVersion
    owner: securechain_Hardware
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
    owner: securechain_Hardware
    domain_of:
    - securechain_Hardware
    - securechain_Software
    range: sdos_Organization
class_uri: securechain:Hardware

```
</details>