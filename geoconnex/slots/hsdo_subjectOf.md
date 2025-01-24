

# Slot: hsdo_subjectOf


_No slot (predicate) description specified_





URI: [hsdo:subjectOf](http://schema.org/subjectOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | No class (type) description specified |  no  |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | No class (type) description specified |  no  |
| [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| http___rdfs.org_ns_void#Dataset → http___rdfs.org_ns_void#Dataset | https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node | hsdo:subjectOf | https://info.geoconnex.us/chyld-pilot/data/node/all |
| http___rdfs.org_ns_void#Dataset → rdfs_Resource | https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node | hsdo:subjectOf | https://info.geoconnex.us/chyld-pilot/data/node/cross |
| rdfs_Resource → uri | https://geoconnex.us/chyld-pilot/id/gage/04271500 | hsdo:subjectOf | https://cida.usgs.gov/nldi/nwissite/USGS-04271500 |
| http___geosciences.ca_def_groundwater#GW_AquiferSystem → uri | https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN | hsdo:subjectOf | http://water.usgs.gov/ogw/aquiferbasics/sandston.html |
| http___geosciences.ca_def_groundwater#GW_Well → uri | https://geoconnex.us/chyld-pilot/id/well/USGS-434217073010601 | hsdo:subjectOf | http://waterdata.usgs.gov/nwis/inventory?search_site_no=434217073010601&search_site_no_match_type=exact&sort_key=site_no&group_key=NONE&sitefile_output_format=html_table&column_name=agency_cd&column_name=site_no&column_name=station_nm&format=station_manuscript&list_of_search_criteria=search_site_no |


## Comments

* 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type http___rdfs.org_ns_void#Dataset.
* 2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type rdfs_Resource.
* 3227 occurrences with subject type rdfs_Resource and object type uri.
* 6 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type uri.
* 15 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:subjectOf |
| native | geoconnex/:hsdo_subjectOf |




## LinkML Source

<details>
```yaml
name: hsdo_subjectOf
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
  http___rdfs.org_ns_void#Dataset.
- 2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
  rdfs_Resource.
- 3227 occurrences with subject type rdfs_Resource and object type uri.
- 6 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
  and object type uri.
- 15 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and
  object type uri.
examples:
- description: http___rdfs.org_ns_void#Dataset → http___rdfs.org_ns_void#Dataset
  object:
    example_object: https://info.geoconnex.us/chyld-pilot/data/node/all
    example_predicate: hsdo:subjectOf
    example_subject: https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node
- description: http___rdfs.org_ns_void#Dataset → rdfs_Resource
  object:
    example_object: https://info.geoconnex.us/chyld-pilot/data/node/cross
    example_predicate: hsdo:subjectOf
    example_subject: https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node
- description: rdfs_Resource → uri
  object:
    example_object: https://cida.usgs.gov/nldi/nwissite/USGS-04271500
    example_predicate: hsdo:subjectOf
    example_subject: https://geoconnex.us/chyld-pilot/id/gage/04271500
- description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → uri
  object:
    example_object: http://water.usgs.gov/ogw/aquiferbasics/sandston.html
    example_predicate: hsdo:subjectOf
    example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN
- description: http___geosciences.ca_def_groundwater#GW_Well → uri
  object:
    example_object: http://waterdata.usgs.gov/nwis/inventory?search_site_no=434217073010601&search_site_no_match_type=exact&sort_key=site_no&group_key=NONE&sitefile_output_format=html_table&column_name=agency_cd&column_name=site_no&column_name=station_nm&format=station_manuscript&list_of_search_criteria=search_site_no
    example_predicate: hsdo:subjectOf
    example_subject: https://geoconnex.us/chyld-pilot/id/well/USGS-434217073010601
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:subjectOf
alias: hsdo_subjectOf
domain_of:
- http___geosciences.ca_def_groundwater#GW_AquiferSystem
- http___geosciences.ca_def_groundwater#GW_Well
- http___rdfs.org_ns_void#Dataset
- rdfs_Resource
range: Any
any_of:
- range: uri
- range: rdfs_Resource
- range: http___rdfs.org_ns_void#Dataset

```
</details>