

# Slot: owl_sameAs


_No slot (predicate) description specified_





URI: [owl:sameAs](http://www.w3.org/2002/07/owl#sameAs)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | No class (type) description specified |  no  |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | No class (type) description specified |  no  |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rdfs_Resource → rdfs_Resource | https://geoconnex.us/chyld-pilot/id/nat_aq/N100GLCIAL | owl:sameAs | https://geoconnex.us/chyld-pilot/id/nat_aq/N100GLCIAL |
| http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → http___geosciences.ca_def_groundwater#GW_HydrogeoUnit | https://geoconnex.ca/id/hydrogeounits/Richelieu1 | owl:sameAs | https://geoconnex.ca/id/hydrogeounits/Richelieu1 |
| http___geosciences.ca_def_groundwater#GW_AquiferSystem → http___geosciences.ca_def_groundwater#GW_AquiferSystem | https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB | owl:sameAs | https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB |
| http___geosciences.ca_def_groundwater#GW_Well → http___geosciences.ca_def_groundwater#GW_Well | https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201 | owl:sameAs | https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201 |


## Comments

* 1498 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
* 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.
* 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.
* 5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type http___geosciences.ca_def_groundwater#GW_Well.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | owl:sameAs |
| native | geoconnex/:owl_sameAs |




## LinkML Source

<details>
```yaml
name: owl_sameAs
description: No slot (predicate) description specified
comments:
- 1498 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
- 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
  and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.
- 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
  and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.
- 5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and
  object type http___geosciences.ca_def_groundwater#GW_Well.
examples:
- description: rdfs_Resource → rdfs_Resource
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/nat_aq/N100GLCIAL
    example_predicate: owl:sameAs
    example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N100GLCIAL
- description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
  object:
    example_object: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    example_predicate: owl:sameAs
    example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
- description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → http___geosciences.ca_def_groundwater#GW_AquiferSystem
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB
    example_predicate: owl:sameAs
    example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB
- description: http___geosciences.ca_def_groundwater#GW_Well → http___geosciences.ca_def_groundwater#GW_Well
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201
    example_predicate: owl:sameAs
    example_subject: https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201
from_schema: geoconnex
rank: 1000
slot_uri: owl:sameAs
alias: owl_sameAs
domain_of:
- http___geosciences.ca_def_groundwater#GW_AquiferSystem
- http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
- http___geosciences.ca_def_groundwater#GW_Well
- rdfs_Resource
range: Any
any_of:
- range: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
- range: http___geosciences.ca_def_groundwater#GW_AquiferSystem
- range: rdfs_Resource
- range: http___geosciences.ca_def_groundwater#GW_Well

```
</details>