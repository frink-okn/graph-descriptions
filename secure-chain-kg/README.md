# secure-chain-kg

TODO -- tell the world what this schema describes.

URI: secure-chain-kg/develop

Name: secure-chain-kg



## Schema Diagram

```mermaid
erDiagram
Any {

}
SecurechainHardware {
    string sdoh_name  
}
SecurechainHardwareVersion {
    string securechain_versionName  
}
SecurechainSoftware {
    string sdoh_name  
}
SecurechainSoftwareVersion {
    string securechain_versionName  
}
SecurechainVulnerability {
    string sdoh_identifier  
}
SecurechainVulnerabilityType {
    string sdoh_identifier  
}
RdfProperty {

}
RdfsClass {

}
SdohCreativeWork {
    string sdoh_name  
    string sdoh_identifier  
}
SdohOrganization {
    string sdoh_name  
    string sdoh_identifier  
    string sdoh_url  
}
SdohPerson {
    string sdoh_identifier  
}

SecurechainHardware ||--|o SecurechainHardwareVersion : "securechain_hasHardwareVersion"
SecurechainHardwareVersion ||--|o Any : "securechain_vulnerableTo"
SecurechainSoftware ||--|o SecurechainSoftwareVersion : "securechain_hasSoftwareVersion"
SecurechainSoftware ||--|o SdohPerson : "sdoh_contributor"
SecurechainSoftwareVersion ||--|o Any : "securechain_dependsOn"
SecurechainSoftwareVersion ||--|o Any : "securechain_vulnerableTo"
SecurechainVulnerability ||--|o SecurechainVulnerabilityType : "securechain_vulnerabilityType"
RdfsClass ||--|o Any : "rdfs_subClassOf"
SdohOrganization ||--|o SecurechainHardware : "sdoh_manufacturer"

```


## Classes

| Class | Description |
| --- | --- |
| [Any](classes/Any.md) | None |
| [RdfProperty](classes/RdfProperty.md) | TODO -- tell the world what this class (type) describes. |
| [RdfsClass](classes/RdfsClass.md) | TODO -- tell the world what this class (type) describes. |
| [SdohCreativeWork](classes/SdohCreativeWork.md) | TODO -- tell the world what this class (type) describes. |
| [SdohOrganization](classes/SdohOrganization.md) | TODO -- tell the world what this class (type) describes. |
| [SdohPerson](classes/SdohPerson.md) | TODO -- tell the world what this class (type) describes. |
| [SecurechainHardware](classes/SecurechainHardware.md) | TODO -- tell the world what this class (type) describes. |
| [SecurechainHardwareVersion](classes/SecurechainHardwareVersion.md) | TODO -- tell the world what this class (type) describes. |
| [SecurechainSoftware](classes/SecurechainSoftware.md) | TODO -- tell the world what this class (type) describes. |
| [SecurechainSoftwareVersion](classes/SecurechainSoftwareVersion.md) | TODO -- tell the world what this class (type) describes. |
| [SecurechainVulnerability](classes/SecurechainVulnerability.md) | TODO -- tell the world what this class (type) describes. |
| [SecurechainVulnerabilityType](classes/SecurechainVulnerabilityType.md) | TODO -- tell the world what this class (type) describes. |



## Slots

| Slot | Description |
| --- | --- |
| [rdfs_subClassOf](slots/rdfs_subClassOf.md) | TODO -- tell the world what this slot (predicate) describes |
| [sdoh_contributor](slots/sdoh_contributor.md) | TODO -- tell the world what this slot (predicate) describes |
| [sdoh_identifier](slots/sdoh_identifier.md) | TODO -- tell the world what this slot (predicate) describes |
| [sdoh_manufacturer](slots/sdoh_manufacturer.md) | TODO -- tell the world what this slot (predicate) describes |
| [sdoh_name](slots/sdoh_name.md) | TODO -- tell the world what this slot (predicate) describes |
| [sdoh_url](slots/sdoh_url.md) | TODO -- tell the world what this slot (predicate) describes |
| [securechain_dependsOn](slots/securechain_dependsOn.md) | TODO -- tell the world what this slot (predicate) describes |
| [securechain_hasHardwareVersion](slots/securechain_hasHardwareVersion.md) | TODO -- tell the world what this slot (predicate) describes |
| [securechain_hasSoftwareVersion](slots/securechain_hasSoftwareVersion.md) | TODO -- tell the world what this slot (predicate) describes |
| [securechain_versionName](slots/securechain_versionName.md) | TODO -- tell the world what this slot (predicate) describes |
| [securechain_vulnerabilityType](slots/securechain_vulnerabilityType.md) | TODO -- tell the world what this slot (predicate) describes |
| [securechain_vulnerableTo](slots/securechain_vulnerableTo.md) | TODO -- tell the world what this slot (predicate) describes |


## Enumerations

| Enumeration | Description |
| --- | --- |


## Types

| Type | Description |
| --- | --- |


## Subsets

| Subset | Description |
| --- | --- |
