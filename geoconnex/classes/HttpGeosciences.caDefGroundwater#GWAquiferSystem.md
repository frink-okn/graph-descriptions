

# Class: No class (type) name specified (http___geosciences.ca_def_groundwater#GW_AquiferSystem)


_No class (type) description specified_





URI: [http://geosciences.ca/def/groundwater#GW_AquiferSystem](http://geosciences.ca/def/groundwater#GW_AquiferSystem)






```mermaid
 classDiagram
    class HttpGeosciences.caDefGroundwater#GWAquiferSystem
    click HttpGeosciences.caDefGroundwater#GWAquiferSystem href "../HttpGeosciences.caDefGroundwater#GWAquiferSystem"
      HttpGeosciences.caDefGroundwater#GWAquiferSystem : hsdo_subjectOf
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWAquiferSystem --> "0..1" Any : hsdo_subjectOf
    click Any href "../Any"

        
      HttpGeosciences.caDefGroundwater#GWAquiferSystem : http___www.opengeospatial.org_standards_geosparql_sfContains
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWAquiferSystem --> "0..1" HttpGeosciences.caDefGroundwater#GWWell : http___www.opengeospatial.org_standards_geosparql_sfContains
    click HttpGeosciences.caDefGroundwater#GWWell href "../HttpGeosciences.caDefGroundwater#GWWell"

        
      HttpGeosciences.caDefGroundwater#GWAquiferSystem : http___www.opengeospatial.org_standards_geosparql_sfIntersects
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWAquiferSystem --> "0..1" Any : http___www.opengeospatial.org_standards_geosparql_sfIntersects
    click Any href "../Any"

        
      HttpGeosciences.caDefGroundwater#GWAquiferSystem : owl_sameAs
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWAquiferSystem --> "0..1" Any : owl_sameAs
    click Any href "../Any"

        
      HttpGeosciences.caDefGroundwater#GWAquiferSystem : rdfs_label
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWAquiferSystem --> "0..1" String : rdfs_label
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | No slot (predicate) description specified <br/> 1498 occurrences with subject type rdfs_Resource and object type rdfs_Resource.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.<br/>5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type http___geosciences.ca_def_groundwater#GW_Well. | direct |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1514 occurrences with subject type rdfs_Resource and object type string.<br/>3204 occurrences with untyped subjects and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>5 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type string.<br/>5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type string. | direct |
| [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | No slot (predicate) description specified <br/> 14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type rdfs_Resource.<br/>13 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type uri.<br/>108 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.<br/>14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.<br/>108 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type rdfs_Resource. | direct |
| [http___www.opengeospatial.org_standards_geosparql_sfContains](../slots/http___www.opengeospatial.org_standards_geosparql_sfContains.md) | 0..1 <br/> [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | No slot (predicate) description specified <br/> 14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_Well.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type http___geosciences.ca_def_groundwater#GW_Well. | direct |
| [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No slot (predicate) description specified <br/> 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type http___rdfs.org_ns_void#Dataset.<br/>2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type rdfs_Resource.<br/>3227 occurrences with subject type rdfs_Resource and object type uri.<br/>6 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type uri.<br/>15 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type uri. | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | [http___www.opengeospatial.org_standards_geosparql_sfWithin](../slots/http___www.opengeospatial.org_standards_geosparql_sfWithin.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) |
| [RdfsResource](../classes/RdfsResource.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) |
| [RdfsResource](../classes/RdfsResource.md) | [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://geosciences.ca/def/groundwater#GW_AquiferSystem |
| native | geoconnex/:HttpGeosciences.caDefGroundwater#GWAquiferSystem |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: http___geosciences.ca_def_groundwater#GW_AquiferSystem
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 2 occurrences.
from_schema: geoconnex
rank: 1000
slots:
- owl_sameAs
- rdfs_label
- http___www.opengeospatial.org_standards_geosparql_sfIntersects
- http___www.opengeospatial.org_standards_geosparql_sfContains
- hsdo_subjectOf
class_uri: http://geosciences.ca/def/groundwater#GW_AquiferSystem

```
</details>

### Induced

<details>
```yaml
name: http___geosciences.ca_def_groundwater#GW_AquiferSystem
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 2 occurrences.
from_schema: geoconnex
rank: 1000
attributes:
  owl_sameAs:
    name: owl_sameAs
    description: No slot (predicate) description specified
    comments:
    - 1498 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
    - 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.
    - 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
      and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.
    - 5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well
      and object type http___geosciences.ca_def_groundwater#GW_Well.
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
    owner: http___geosciences.ca_def_groundwater#GW_AquiferSystem
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
  rdfs_label:
    name: rdfs_label
    description: No slot (predicate) description specified
    comments:
    - 1514 occurrences with subject type rdfs_Resource and object type string.
    - 3204 occurrences with untyped subjects and object type string.
    - 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type string.
    - 5 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      string.
    - 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
      and object type string.
    - 5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well
      and object type string.
    examples:
    - description: rdfs_Resource → string
      object:
        example_object: Aquifer System
        example_predicate: rdfs:label
        example_subject: http://geosciences.ca/def/groundwater#GW_AquiferSystem
    - description: None → string
      object:
        example_object: Aquifer Summary Page
        example_predicate: rdfs:label
        example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → string
      object:
        example_object: 'Hydrogeologic unit : Southern St Lawrence Platform'
        example_predicate: rdfs:label
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    - description: http___rdfs.org_ns_void#Dataset → string
      object:
        example_object: Hydrography Linked Data Node - United States of America
        example_predicate: rdfs:label
        example_subject: https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node
    - description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → string
      object:
        example_object: New York sandstone aquifers
        example_predicate: rdfs:label
        example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN
    - description: http___geosciences.ca_def_groundwater#GW_Well → string
      object:
        example_object: VT-PFW    8
        example_predicate: rdfs:label
        example_subject: https://geoconnex.us/chyld-pilot/id/well/USGS-434217073010601
    from_schema: geoconnex
    rank: 1000
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___geosciences.ca_def_groundwater#GW_AquiferSystem
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - http___geosciences.ca_def_groundwater#GW_Well
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    range: string
  http___www.opengeospatial.org_standards_geosparql_sfIntersects:
    name: http___www.opengeospatial.org_standards_geosparql_sfIntersects
    description: No slot (predicate) description specified
    comments:
    - 14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type rdfs_Resource.
    - 13 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type uri.
    - 108 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.
    - 14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.
    - 108 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
      and object type rdfs_Resource.
    examples:
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081507-drainage_basin
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → uri
      object:
        example_object: https://cida-test.er.usgs.gov/chyld-pilot/id/hu/041504081005
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    - description: rdfs_Resource → http___geosciences.ca_def_groundwater#GW_AquiferSystem
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081604
    - description: rdfs_Resource → http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      object:
        example_object: https://geoconnex.ca/id/hydrogeounits/Richelieu1
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
        example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081507-drainage_basin
    - description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081604
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
        example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB
    from_schema: geoconnex
    rank: 1000
    slot_uri: http://www.opengeospatial.org/standards/geosparql/sfIntersects
    alias: http___www.opengeospatial.org_standards_geosparql_sfIntersects
    owner: http___geosciences.ca_def_groundwater#GW_AquiferSystem
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - rdfs_Resource
    range: Any
    any_of:
    - range: uri
    - range: http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - range: rdfs_Resource
    - range: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
  http___www.opengeospatial.org_standards_geosparql_sfContains:
    name: http___www.opengeospatial.org_standards_geosparql_sfContains
    description: No slot (predicate) description specified
    comments:
    - 14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_Well.
    - 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
      and object type http___geosciences.ca_def_groundwater#GW_Well.
    examples:
    - description: rdfs_Resource → http___geosciences.ca_def_groundwater#GW_Well
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/well/USGS-443646073124901
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfContains
        example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N100GLCIAL
    - description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → http___geosciences.ca_def_groundwater#GW_Well
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfContains
        example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN
    from_schema: geoconnex
    rank: 1000
    slot_uri: http://www.opengeospatial.org/standards/geosparql/sfContains
    alias: http___www.opengeospatial.org_standards_geosparql_sfContains
    owner: http___geosciences.ca_def_groundwater#GW_AquiferSystem
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - rdfs_Resource
    range: http___geosciences.ca_def_groundwater#GW_Well
  hsdo_subjectOf:
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
    - 15 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well
      and object type uri.
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
    owner: http___geosciences.ca_def_groundwater#GW_AquiferSystem
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
class_uri: http://geosciences.ca/def/groundwater#GW_AquiferSystem

```
</details>