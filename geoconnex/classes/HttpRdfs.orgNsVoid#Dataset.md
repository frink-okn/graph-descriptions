

# Class: No class (type) name specified (http___rdfs.org_ns_void#Dataset)


_No class (type) description specified_





URI: [http://rdfs.org/ns/void#Dataset](http://rdfs.org/ns/void#Dataset)






```mermaid
 classDiagram
    class HttpRdfs.orgNsVoid#Dataset
    click HttpRdfs.orgNsVoid#Dataset href "../HttpRdfs.orgNsVoid#Dataset"
      HttpRdfs.orgNsVoid#Dataset : dc_description
        
          
    
    
    HttpRdfs.orgNsVoid#Dataset --> "0..1" String : dc_description
    click String href "../String"

        
      HttpRdfs.orgNsVoid#Dataset : dct_conformsTo
        
          
    
    
    HttpRdfs.orgNsVoid#Dataset --> "0..1" Any : dct_conformsTo
    click Any href "../Any"

        
      HttpRdfs.orgNsVoid#Dataset : dct_format
        
          
    
    
    HttpRdfs.orgNsVoid#Dataset --> "0..1" String : dct_format
    click String href "../String"

        
      HttpRdfs.orgNsVoid#Dataset : hsdo_provider
        
          
    
    
    HttpRdfs.orgNsVoid#Dataset --> "0..1" Any : hsdo_provider
    click Any href "../Any"

        
      HttpRdfs.orgNsVoid#Dataset : hsdo_subjectOf
        
          
    
    
    HttpRdfs.orgNsVoid#Dataset --> "0..1" Any : hsdo_subjectOf
    click Any href "../Any"

        
      HttpRdfs.orgNsVoid#Dataset : https___geoconnex.ca_id_connectedTo
        
          
    
    
    HttpRdfs.orgNsVoid#Dataset --> "0..1" Uri : https___geoconnex.ca_id_connectedTo
    click Uri href "../Uri"

        
      HttpRdfs.orgNsVoid#Dataset : rdfs_label
        
          
    
    
    HttpRdfs.orgNsVoid#Dataset --> "0..1" String : rdfs_label
    click String href "../String"

        
      HttpRdfs.orgNsVoid#Dataset : schema_provider
        
          
    
    
    HttpRdfs.orgNsVoid#Dataset --> "0..1" Any : schema_provider
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [dc_description](../slots/dc_description.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>2 occurrences with subject type rdfs_Resource and object type string. | direct |
| [dct_conformsTo](../slots/dct_conformsTo.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string) | No slot (predicate) description specified <br/> 56432 occurrences with subject type schema_DataDownload and object type string.<br/>3194 occurrences with untyped subjects and object type uri.<br/>2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.<br/>4 occurrences with subject type rdfs_Resource and object type uri. | direct |
| [schema_provider](../slots/schema_provider.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[SchemaGovernmentOrganization](../classes/SchemaGovernmentOrganization.md)&nbsp;or&nbsp;<br />[schema_url](../slots/schema_url.md) | No slot (predicate) description specified <br/> 28216 occurrences with subject type schema_Dataset and object type schema_GovernmentOrganization.<br/>1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.<br/>2 occurrences with subject type rdfs_Resource and object type uri.<br/>98534 occurrences with subject type schema_Place and object type schema_url.<br/>185872 occurrences with subject type hyf__HY_HydroLocation and object type uri.<br/>13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_GovernmentOrganization. | direct |
| [https___geoconnex.ca_id_connectedTo](../slots/https___geoconnex.ca_id_connectedTo.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) | No slot (predicate) description specified <br/> 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri. | direct |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1514 occurrences with subject type rdfs_Resource and object type string.<br/>3204 occurrences with untyped subjects and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>5 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type string.<br/>5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type string. | direct |
| [dct_format](../slots/dct_format.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 7697 occurrences with untyped subjects and object type string.<br/>3 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>6 occurrences with subject type rdfs_Resource and object type string. | direct |
| [hsdo_provider](../slots/hsdo_provider.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string) | No slot (predicate) description specified <br/> 3194 occurrences with untyped subjects and object type uri.<br/>1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.<br/>2 occurrences with subject type rdfs_Resource and object type uri.<br/>48672 occurrences with subject type hsdo_WebPage and object type string. | direct |
| [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No slot (predicate) description specified <br/> 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type http___rdfs.org_ns_void#Dataset.<br/>2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type rdfs_Resource.<br/>3227 occurrences with subject type rdfs_Resource and object type uri.<br/>6 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type uri.<br/>15 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type uri. | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | any_of[range] | [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | any_of[range] | [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) |
| [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | any_of[range] | [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) |
| [RdfsResource](../classes/RdfsResource.md) | [http___rdfs.org_ns_void#target](../slots/http___rdfs.org_ns_void#target.md) | any_of[range] | [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) |
| [RdfsResource](../classes/RdfsResource.md) | [hsdo_subjectOf](../slots/hsdo_subjectOf.md) | any_of[range] | [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://rdfs.org/ns/void#Dataset |
| native | geoconnex/:HttpRdfs.orgNsVoid#Dataset |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: http___rdfs.org_ns_void#Dataset
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 2 occurrences.
from_schema: geoconnex
rank: 1000
slots:
- dc_description
- dct_conformsTo
- schema_provider
- https___geoconnex.ca_id_connectedTo
- rdfs_label
- dct_format
- hsdo_provider
- hsdo_subjectOf
class_uri: http://rdfs.org/ns/void#Dataset

```
</details>

### Induced

<details>
```yaml
name: http___rdfs.org_ns_void#Dataset
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 2 occurrences.
from_schema: geoconnex
rank: 1000
attributes:
  dc_description:
    name: dc_description
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      string.
    - 2 occurrences with subject type rdfs_Resource and object type string.
    examples:
    - description: http___rdfs.org_ns_void#Dataset → string
      object:
        example_object: 'Representation of the data node: catalog of features i.e.
          /id/s. Contains triples like: CAN_Watershed gsip:inNodeCatalog /id/CAN_LOD_Node'
        example_predicate: dc:description
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
    - description: rdfs_Resource → string
      object:
        example_object: 'Representation containing links between data nodes. Only
          contains triples like: /id/CAN_LOD_Node connectedTo /id/US_LOD_Node'
        example_predicate: dc:description
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    from_schema: geoconnex
    rank: 1000
    slot_uri: dc:description
    alias: dc_description
    owner: http___rdfs.org_ns_void#Dataset
    domain_of:
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    range: string
  dct_conformsTo:
    name: dct_conformsTo
    description: No slot (predicate) description specified
    comments:
    - 56432 occurrences with subject type schema_DataDownload and object type string.
    - 3194 occurrences with untyped subjects and object type uri.
    - 2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      uri.
    - 4 occurrences with subject type rdfs_Resource and object type uri.
    examples:
    - description: schema_DataDownload → string
      object:
        example_object: https://labs.waterdata.usgs.gov/docs/sensorthings/index.html
        example_predicate: dct:conformsTo
        example_subject: _:b1000004
    - description: None → uri
      object:
        example_object: https://github.com/NRCan/GSIP
        example_predicate: dct:conformsTo
        example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
    - description: http___rdfs.org_ns_void#Dataset → uri
      object:
        example_object: https://github.com/NRCan/GSIP
        example_predicate: dct:conformsTo
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
    - description: rdfs_Resource → uri
      object:
        example_object: https://github.com/NRCan/GSIP
        example_predicate: dct:conformsTo
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    from_schema: geoconnex
    rank: 1000
    slot_uri: dct:conformsTo
    alias: dct_conformsTo
    owner: http___rdfs.org_ns_void#Dataset
    domain_of:
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    - schema_DataDownload
    range: Any
    any_of:
    - range: uri
    - range: string
  schema_provider:
    name: schema_provider
    description: No slot (predicate) description specified
    comments:
    - 28216 occurrences with subject type schema_Dataset and object type schema_GovernmentOrganization.
    - 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      uri.
    - 2 occurrences with subject type rdfs_Resource and object type uri.
    - 98534 occurrences with subject type schema_Place and object type schema_url.
    - 185872 occurrences with subject type hyf__HY_HydroLocation and object type uri.
    - 13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_GovernmentOrganization.
    examples:
    - description: schema_Dataset → schema_GovernmentOrganization
      object:
        example_object: https://gleaner.io/xid/genid/cri6355vd7os738ck6h0
        example_predicate: schema:provider
        example_subject: https://gleaner.io/xid/genid/cri6355vd7os738ck6jg
    - description: http___rdfs.org_ns_void#Dataset → uri
      object:
        example_object: https://labs.waterdata.usgs.gov
        example_predicate: schema:provider
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
    - description: rdfs_Resource → uri
      object:
        example_object: https://labs.waterdata.usgs.gov
        example_predicate: schema:provider
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    - description: schema_Place → schema_url
      object:
        example_object: https://nid.usace.army.mil
        example_predicate: schema:provider
        example_subject: https://geoconnex.us/ref/dams/1000001
    - description: hyf__HY_HydroLocation → uri
      object:
        example_object: https://waterdata.usgs.gov
        example_predicate: schema:provider
        example_subject: https://geoconnex.us/ref/gages/1000001
    - description: hyf__HY_HydroLocation → schema_GovernmentOrganization
      object:
        example_object: _:b850488
        example_predicate: schema:provider
        example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900'
    from_schema: geoconnex
    rank: 1000
    slot_uri: schema:provider
    alias: schema_provider
    owner: http___rdfs.org_ns_void#Dataset
    domain_of:
    - http___rdfs.org_ns_void#Dataset
    - hyf__HY_HydroLocation
    - rdfs_Resource
    - schema_Dataset
    - schema_Place
    range: Any
    any_of:
    - range: uri
    - range: schema_GovernmentOrganization
    - range: schema_url
  https___geoconnex.ca_id_connectedTo:
    name: https___geoconnex.ca_id_connectedTo
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      uri.
    examples:
    - description: http___rdfs.org_ns_void#Dataset → uri
      object:
        example_object: https://geoconnex.ca/id/LOD_Node/CAN_Hydro_LOD_Node
        example_predicate: https://geoconnex.ca/id/connectedTo
        example_subject: https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node
    from_schema: geoconnex
    rank: 1000
    slot_uri: https://geoconnex.ca/id/connectedTo
    alias: https___geoconnex.ca_id_connectedTo
    owner: http___rdfs.org_ns_void#Dataset
    domain_of:
    - http___rdfs.org_ns_void#Dataset
    range: uri
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
    owner: http___rdfs.org_ns_void#Dataset
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_AquiferSystem
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - http___geosciences.ca_def_groundwater#GW_Well
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    range: string
  dct_format:
    name: dct_format
    description: No slot (predicate) description specified
    comments:
    - 7697 occurrences with untyped subjects and object type string.
    - 3 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      string.
    - 6 occurrences with subject type rdfs_Resource and object type string.
    examples:
    - description: None → string
      object:
        example_object: text/html
        example_predicate: dct:format
        example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
    - description: http___rdfs.org_ns_void#Dataset → string
      object:
        example_object: application/ld+json
        example_predicate: dct:format
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
    - description: rdfs_Resource → string
      object:
        example_object: application/ld+json
        example_predicate: dct:format
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    from_schema: geoconnex
    rank: 1000
    slot_uri: dct:format
    alias: dct_format
    owner: http___rdfs.org_ns_void#Dataset
    domain_of:
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    range: string
  hsdo_provider:
    name: hsdo_provider
    description: No slot (predicate) description specified
    comments:
    - 3194 occurrences with untyped subjects and object type uri.
    - 1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
      uri.
    - 2 occurrences with subject type rdfs_Resource and object type uri.
    - 48672 occurrences with subject type hsdo_WebPage and object type string.
    examples:
    - description: None → uri
      object:
        example_object: https://labs.waterdata.usgs.gov
        example_predicate: hsdo:provider
        example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
    - description: http___rdfs.org_ns_void#Dataset → uri
      object:
        example_object: https://labs.waterdata.usgs.gov
        example_predicate: hsdo:provider
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/all
    - description: rdfs_Resource → uri
      object:
        example_object: https://labs.waterdata.usgs.gov
        example_predicate: hsdo:provider
        example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
    - description: hsdo_WebPage → string
      object:
        example_object: https://epa.gov
        example_predicate: hsdo:provider
        example_subject: https://geoconnex.us/epa/hmw/010100020101
    from_schema: geoconnex
    rank: 1000
    slot_uri: hsdo:provider
    alias: hsdo_provider
    owner: http___rdfs.org_ns_void#Dataset
    domain_of:
    - hsdo_WebPage
    - http___rdfs.org_ns_void#Dataset
    - rdfs_Resource
    range: Any
    any_of:
    - range: uri
    - range: string
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
    owner: http___rdfs.org_ns_void#Dataset
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
class_uri: http://rdfs.org/ns/void#Dataset

```
</details>