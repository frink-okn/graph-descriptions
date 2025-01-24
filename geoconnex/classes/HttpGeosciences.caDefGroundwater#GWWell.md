

# Class: No class (type) name specified (http___geosciences.ca_def_groundwater#GW_Well)


_No class (type) description specified_





URI: [http://geosciences.ca/def/groundwater#GW_Well](http://geosciences.ca/def/groundwater#GW_Well)






```mermaid
 classDiagram
    class HttpGeosciences.caDefGroundwater#GWWell
    click HttpGeosciences.caDefGroundwater#GWWell href "../HttpGeosciences.caDefGroundwater#GWWell"
      HttpGeosciences.caDefGroundwater#GWWell : hsdo_subjectOf
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWWell --> "0..1" Any : hsdo_subjectOf
    click Any href "../Any"

        
      HttpGeosciences.caDefGroundwater#GWWell : http___www.opengeospatial.org_standards_geosparql_sfWithin
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWWell --> "0..1" Any : http___www.opengeospatial.org_standards_geosparql_sfWithin
    click Any href "../Any"

        
      HttpGeosciences.caDefGroundwater#GWWell : owl_sameAs
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWWell --> "0..1" Any : owl_sameAs
    click Any href "../Any"

        
      HttpGeosciences.caDefGroundwater#GWWell : rdfs_label
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWWell --> "0..1" String : rdfs_label
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1514 occurrences with subject type rdfs_Resource and object type string.<br/>3204 occurrences with untyped subjects and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>5 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type string.<br/>5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type string. | direct |
| [http___www.opengeospatial.org_standards_geosparql_sfWithin](../slots/http___www.opengeospatial.org_standards_geosparql_sfWithin.md) | 0..1 <br/> [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md) | No slot (predicate) description specified <br/> 14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type rdfs_Resource.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem. | direct |
| [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No slot (predicate) description specified <br/> 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type http___rdfs.org_ns_void#Dataset.<br/>2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type rdfs_Resource.<br/>3227 occurrences with subject type rdfs_Resource and object type uri.<br/>6 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type uri.<br/>15 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type uri. | direct |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | No slot (predicate) description specified <br/> 1498 occurrences with subject type rdfs_Resource and object type rdfs_Resource.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.<br/>5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type http___geosciences.ca_def_groundwater#GW_Well. | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | [http___www.opengeospatial.org_standards_geosparql_sfContains](../slots/http___www.opengeospatial.org_standards_geosparql_sfContains.md) | range | [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) |
| [RdfsResource](../classes/RdfsResource.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) |
| [RdfsResource](../classes/RdfsResource.md) | [http___www.opengeospatial.org_standards_geosparql_sfContains](../slots/http___www.opengeospatial.org_standards_geosparql_sfContains.md) | range | [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://geosciences.ca/def/groundwater#GW_Well |
| native | geoconnex/:HttpGeosciences.caDefGroundwater#GWWell |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: http___geosciences.ca_def_groundwater#GW_Well
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 5 occurrences.
from_schema: geoconnex
rank: 1000
slots:
- rdfs_label
- http___www.opengeospatial.org_standards_geosparql_sfWithin
- hsdo_subjectOf
- owl_sameAs
class_uri: http://geosciences.ca/def/groundwater#GW_Well

```
</details>

### Induced

<details>
```yaml
name: http___geosciences.ca_def_groundwater#GW_Well
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 5 occurrences.
from_schema: geoconnex
rank: 1000
attributes:
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
    owner: http___geosciences.ca_def_groundwater#GW_Well
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - http___geosciences.ca_def_groundwater#GW_Well
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    range: string
  http___www.opengeospatial.org_standards_geosparql_sfWithin:
    name: http___www.opengeospatial.org_standards_geosparql_sfWithin
    description: No slot (predicate) description specified
    comments:
    - 14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well
      and object type rdfs_Resource.
    - 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well
      and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.
    examples:
    - description: http___geosciences.ca_def_groundwater#GW_Well → rdfs_Resource
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081603
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfWithin
        example_subject: https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201
    - description: http___geosciences.ca_def_groundwater#GW_Well → http___geosciences.ca_def_groundwater#GW_AquiferSystem
      object:
        example_object: https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN
        example_predicate: http://www.opengeospatial.org/standards/geosparql/sfWithin
        example_subject: https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201
    from_schema: geoconnex
    rank: 1000
    slot_uri: http://www.opengeospatial.org/standards/geosparql/sfWithin
    alias: http___www.opengeospatial.org_standards_geosparql_sfWithin
    owner: http___geosciences.ca_def_groundwater#GW_Well
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_Well
    range: Any
    any_of:
    - range: http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - range: rdfs_Resource
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
    owner: http___geosciences.ca_def_groundwater#GW_Well
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
    owner: http___geosciences.ca_def_groundwater#GW_Well
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
class_uri: http://geosciences.ca/def/groundwater#GW_Well

```
</details>