# No schema name specified

No schema description specified



## Schema Diagram

```mermaid
erDiagram
HsdoCreativeWork {
    string hsdo_name  
    string hsdo_identifier  
}
HsdoIntangible {

}
HsdoOrganization {
    string hsdo_name  
    string hsdo_url  
    string hsdo_identifier  
}
HsdoPerson {
    string hsdo_identifier  
}
HsdoProduct {

}
HsdoSoftwareApplication {

}
SecurechainHardware {
    string hsdo_name  
}
SecurechainHardwareVersion {
    string securechain_versionName  
    string hsdo_name  
}
SecurechainLicense {
    string hsdo_name  
    string hsdo_identifier  
}
SecurechainSoftware {
    string hsdo_name  
}
SecurechainSoftwareVersion {
    uri securechain_dependsOn  
    string securechain_versionName  
    string hsdo_name  
}
SecurechainVulnerability {
    string hsdo_identifier  
}
SecurechainVulnerabilityType {
    string hsdo_identifier  
}

HsdoOrganization ||--|o SecurechainHardware : "hsdo_manufacturer"
SecurechainHardware ||--|o SecurechainHardwareVersion : "securechain_hasHardwareVersion"
SecurechainHardwareVersion ||--|o SecurechainVulnerability : "securechain_vulnerableTo"
SecurechainHardwareVersion ||--|o SecurechainHardwareVersion : "securechain_hasHardwareVersion"
SecurechainSoftware ||--|o HsdoPerson : "hsdo_contributor"
SecurechainSoftware ||--|o SecurechainSoftwareVersion : "securechain_hasSoftwareVersion"
SecurechainSoftwareVersion ||--|o SecurechainSoftwareVersion : "securechain_dependsOn"
SecurechainSoftwareVersion ||--|o SecurechainVulnerability : "securechain_vulnerableTo"
SecurechainSoftwareVersion ||--|o HsdoPerson : "hsdo_contributor"
SecurechainSoftwareVersion ||--|o SecurechainSoftwareVersion : "securechain_hasSoftwareVersion"
SecurechainVulnerability ||--|o SecurechainVulnerabilityType : "securechain_vulnerabilityType"

```



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [HsdoCreativeWork](classes/HsdoCreativeWork.md) | The most generic kind of creative work, including books, movies, photographs, software programs, etc.<br/>| 20 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainLicense](classes/SecurechainLicense.md) | No class (type) description specified<br/>| 0 | 
| [HsdoIntangible](classes/HsdoIntangible.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainVulnerability](classes/SecurechainVulnerability.md) | No class (type) description specified<br/>| 259334 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainVulnerabilityType](classes/SecurechainVulnerabilityType.md) | No class (type) description specified<br/>| 445 | 
| [HsdoOrganization](classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc.<br/>| 22889 | 
| [HsdoPerson](classes/HsdoPerson.md) | A person (alive, dead, undead, or fictional).<br/>| 30434 | 
| [HsdoProduct](classes/HsdoProduct.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainHardware](classes/SecurechainHardware.md) | No class (type) description specified<br/>| 53378 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainHardwareVersion](classes/SecurechainHardwareVersion.md) | No class (type) description specified<br/>| 57295 | 
| [HsdoSoftwareApplication](classes/HsdoSoftwareApplication.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainSoftware](classes/SecurechainSoftware.md) | No class (type) description specified<br/>| 34469 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SecurechainSoftwareVersion](classes/SecurechainSoftwareVersion.md) | No class (type) description specified<br/>| 164001 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [hsdo_contributor](slots/hsdo_contributor.md) | A secondary contributor to the CreativeWork or Event<br/>| 36716 |
| [hsdo_identifier](slots/hsdo_identifier.md) | The identifier property represents any kind of identifier for any kind of [[T...<br/>| 291120 |
| [hsdo_manufacturer](slots/hsdo_manufacturer.md) | The manufacturer of the product<br/>| 54369 |
| [hsdo_name](slots/hsdo_name.md) | The name of the item<br/>| 109866 |
| [hsdo_url](slots/hsdo_url.md) | URL of the item<br/>| 887 |
| [securechain_dependsOn](slots/securechain_dependsOn.md) | No slot (predicate) description specified<br/>| 1679918 |
| [securechain_discover](slots/securechain_discover.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [securechain_hasHardwareVersion](slots/securechain_hasHardwareVersion.md) | No slot (predicate) description specified<br/>| 57295 |
| [securechain_hasSoftwareVersion](slots/securechain_hasSoftwareVersion.md) | No slot (predicate) description specified<br/>| 164001 |
| [securechain_versionName](slots/securechain_versionName.md) | No slot (predicate) description specified<br/>| 221295 |
| [securechain_vulnerabilityType](slots/securechain_vulnerabilityType.md) | No slot (predicate) description specified<br/>| 177404 |
| [securechain_vulnerableTo](slots/securechain_vulnerableTo.md) | No slot (predicate) description specified<br/>| 472350 |









## IRI prefixes

* hsdo: http://schema.org/
* linkml: https://w3id.org/linkml/
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* schema: https://schema.org/
* securechain: https://w3id.org/secure-chain/
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
