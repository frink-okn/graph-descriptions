# securechainkg

No schema description specified



## Schema Diagram

```mermaid
erDiagram
B8e37d573f67cafe60bd7c79e143cd62e {

}
Bcfd3c14c389f3c8ba32c30498a1d8b29 {

}
HsdoCreativeWork {

}
HsdoIntangible {

}
HsdoOrganization {
    string hsdo_name  
    string hsdo_identifier  
    string hsdo_programmingLanguage  
    string hsdo_url  
    uri hsdo_url  
    string securechain_ecosystem  
}
HsdoPerson {
    string hsdo_name  
}
HsdoProduct {

}
HsdoSoftwareApplication {

}
HsdoText {

}
SecurechainHardware {
    string hsdo_name  
    string hsdo_programmingLanguage  
    string securechain_ecosystem  
}
SecurechainHardwareVersion {
    string securechain_versionName  
    string hsdo_name  
    string hsdo_programmingLanguage  
    string securechain_ecosystem  
}
SecurechainLicense {
    string hsdo_name  
    string hsdo_identifier  
}
SecurechainSoftware {
    string hsdo_name  
    string hsdo_identifier  
    string hsdo_programmingLanguage  
    string hsdo_url  
    uri hsdo_url  
    string securechain_ecosystem  
}
SecurechainSoftwareVersion {
    string securechain_versionName  
    string hsdo_url  
    uri hsdo_url  
    string hsdo_name  
    string hsdo_identifier  
    string hsdo_programmingLanguage  
    string securechain_ecosystem  
}
SecurechainVulnerability {
    string hsdo_identifier  
}
SecurechainVulnerabilityType {
    string hsdo_identifier  
}

HsdoOrganization ||--|o SecurechainHardwareVersion : "securechain_hasHardwareVersion"
HsdoOrganization ||--|o HsdoText : "securechain_ecosystem"
HsdoOrganization ||--|o SecurechainSoftwareVersion : "securechain_hasSoftwareVersion"
HsdoOrganization ||--|o HsdoOrganization : "hsdo_manufacturer"
HsdoOrganization ||--|o SecurechainHardware : "hsdo_manufacturer"
HsdoOrganization ||--|o SecurechainSoftware : "hsdo_manufacturer"
SecurechainHardware ||--|o SecurechainHardwareVersion : "securechain_hasHardwareVersion"
SecurechainHardware ||--|o HsdoText : "securechain_ecosystem"
SecurechainHardware ||--|o SecurechainSoftwareVersion : "securechain_hasSoftwareVersion"
SecurechainHardware ||--|o HsdoOrganization : "hsdo_manufacturer"
SecurechainHardware ||--|o SecurechainHardware : "hsdo_manufacturer"
SecurechainHardware ||--|o SecurechainSoftware : "hsdo_manufacturer"
SecurechainHardwareVersion ||--|o HsdoText : "securechain_versionName"
SecurechainHardwareVersion ||--|o SecurechainVulnerability : "securechain_vulnerableTo"
SecurechainHardwareVersion ||--|o SecurechainHardwareVersion : "securechain_hasHardwareVersion"
SecurechainHardwareVersion ||--|o HsdoText : "securechain_ecosystem"
SecurechainHardwareVersion ||--|o SecurechainSoftwareVersion : "securechain_hasSoftwareVersion"
SecurechainHardwareVersion ||--|o HsdoOrganization : "hsdo_manufacturer"
SecurechainHardwareVersion ||--|o SecurechainHardware : "hsdo_manufacturer"
SecurechainHardwareVersion ||--|o SecurechainSoftware : "hsdo_manufacturer"
SecurechainSoftware ||--|o HsdoPerson : "hsdo_contributor"
SecurechainSoftware ||--|o SecurechainHardwareVersion : "securechain_hasHardwareVersion"
SecurechainSoftware ||--|o HsdoText : "securechain_ecosystem"
SecurechainSoftware ||--|o SecurechainSoftwareVersion : "securechain_hasSoftwareVersion"
SecurechainSoftware ||--|o HsdoOrganization : "hsdo_manufacturer"
SecurechainSoftware ||--|o SecurechainHardware : "hsdo_manufacturer"
SecurechainSoftware ||--|o SecurechainSoftware : "hsdo_manufacturer"
SecurechainSoftwareVersion ||--|o SecurechainVulnerability : "securechain_vulnerableTo"
SecurechainSoftwareVersion ||--|o SecurechainSoftwareVersion : "securechain_dependsOn"
SecurechainSoftwareVersion ||--|o HsdoText : "securechain_versionName"
SecurechainSoftwareVersion ||--|o SecurechainLicense : "hsdo_license"
SecurechainSoftwareVersion ||--|o HsdoPerson : "hsdo_contributor"
SecurechainSoftwareVersion ||--|o SecurechainHardwareVersion : "securechain_hasHardwareVersion"
SecurechainSoftwareVersion ||--|o HsdoText : "securechain_ecosystem"
SecurechainSoftwareVersion ||--|o SecurechainSoftwareVersion : "securechain_hasSoftwareVersion"
SecurechainSoftwareVersion ||--|o HsdoOrganization : "hsdo_manufacturer"
SecurechainSoftwareVersion ||--|o SecurechainHardware : "hsdo_manufacturer"
SecurechainSoftwareVersion ||--|o SecurechainSoftware : "hsdo_manufacturer"
SecurechainVulnerability ||--|o SecurechainVulnerabilityType : "securechain_vulnerabilityType"

```



## Imports


* linkml:types



## Classes

| Class | Description | Occurrences |
| --- | --- | --- || [B8e37d573f67cafe60bd7c79e143cd62e](classes/B8e37d573f67cafe60bd7c79e143cd62e.md) | No class (type) description specified<br/>|  | 
| [Bcfd3c14c389f3c8ba32c30498a1d8b29](classes/Bcfd3c14c389f3c8ba32c30498a1d8b29.md) | No class (type) description specified<br/>|  | 

| [HsdoCreativeWork](classes/HsdoCreativeWork.md) | No class (type) description specified<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainLicense](classes/SecurechainLicense.md) | No class (type) description specified<br/>| 294 | 
| [HsdoIntangible](classes/HsdoIntangible.md) | No class (type) description specified<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainVulnerability](classes/SecurechainVulnerability.md) | No class (type) description specified<br/>| 259806 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainVulnerabilityType](classes/SecurechainVulnerabilityType.md) | No class (type) description specified<br/>| 445 | 
| [HsdoOrganization](classes/HsdoOrganization.md) | No class (type) description specified<br/>| 22889 | 
| [HsdoPerson](classes/HsdoPerson.md) | No class (type) description specified<br/>| 27009 | 
| [HsdoProduct](classes/HsdoProduct.md) | No class (type) description specified<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainHardware](classes/SecurechainHardware.md) | No class (type) description specified<br/>| 53378 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainHardwareVersion](classes/SecurechainHardwareVersion.md) | No class (type) description specified<br/>| 57295 | 
| [HsdoSoftwareApplication](classes/HsdoSoftwareApplication.md) | No class (type) description specified<br/>|  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainSoftware](classes/SecurechainSoftware.md) | No class (type) description specified<br/>| 803769 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainSoftwareVersion](classes/SecurechainSoftwareVersion.md) | No class (type) description specified<br/>| 8593149 | 
| [HsdoText](classes/HsdoText.md) | No class (type) description specified<br/>|  | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [hsdo_contributor](slots/hsdo_contributor.md) | No slot (predicate) description specified<br/>| 32408 |
| [hsdo_identifier](slots/hsdo_identifier.md) | No slot (predicate) description specified<br/>| 261432 |
| [hsdo_license](slots/hsdo_license.md) | No slot (predicate) description specified<br/>| 5018025 |
| [hsdo_manufacturer](slots/hsdo_manufacturer.md) | No slot (predicate) description specified<br/>| 54369 |
| [hsdo_name](slots/hsdo_name.md) | No slot (predicate) description specified<br/>| 906771 |
| [hsdo_programmingLanguage](slots/hsdo_programmingLanguage.md) | No slot (predicate) description specified<br/>| 803769 |
| [hsdo_url](slots/hsdo_url.md) | No slot (predicate) description specified<br/>| 7734800 |
| [securechain_dependsOn](slots/securechain_dependsOn.md) | No slot (predicate) description specified<br/>| 29787726 |
| [securechain_discover](slots/securechain_discover.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [securechain_ecosystem](slots/securechain_ecosystem.md) | No slot (predicate) description specified<br/>| 803769 |
| [securechain_hasHardwareVersion](slots/securechain_hasHardwareVersion.md) | No slot (predicate) description specified<br/>| 57295 |
| [securechain_hasSoftwareVersion](slots/securechain_hasSoftwareVersion.md) | No slot (predicate) description specified<br/>| 8593149 |
| [securechain_operatesOn](slots/securechain_operatesOn.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.|  |
| [securechain_versionName](slots/securechain_versionName.md) | No slot (predicate) description specified<br/>| 8650443 |
| [securechain_vulnerabilityType](slots/securechain_vulnerabilityType.md) | No slot (predicate) description specified<br/>| 177404 |
| [securechain_vulnerableTo](slots/securechain_vulnerableTo.md) | No slot (predicate) description specified<br/>| 835140 |









## IRI prefixes

* hsdo: http://schema.org/
* linkml: https://w3id.org/linkml/
* owl: http://www.w3.org/2002/07/owl#
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* securechain: https://w3id.org/secure-chain/
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
* schema: http://schema.org/
