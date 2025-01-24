

# Class: No class (type) name specified (http___geosciences.ca_def_groundwater#GW_HydrogeoUnit)


_No class (type) description specified_





URI: [http://geosciences.ca/def/groundwater#GW_HydrogeoUnit](http://geosciences.ca/def/groundwater#GW_HydrogeoUnit)






```mermaid
 classDiagram
    class HttpGeosciences.caDefGroundwater#GWHydrogeoUnit
    click HttpGeosciences.caDefGroundwater#GWHydrogeoUnit href "../HttpGeosciences.caDefGroundwater#GWHydrogeoUnit"
      HttpGeosciences.caDefGroundwater#GWHydrogeoUnit : hsdo_description
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWHydrogeoUnit --> "0..1" String : hsdo_description
    click String href "../String"

        
      HttpGeosciences.caDefGroundwater#GWHydrogeoUnit : hsdo_image
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWHydrogeoUnit --> "0..1" Any : hsdo_image
    click Any href "../Any"

        
      HttpGeosciences.caDefGroundwater#GWHydrogeoUnit : hsdo_name
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWHydrogeoUnit --> "0..1" String : hsdo_name
    click String href "../String"

        
      HttpGeosciences.caDefGroundwater#GWHydrogeoUnit : http___geosciences.ca_def_groundwater#gwAquiferSystem
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWHydrogeoUnit --> "0..1" Uri : http___geosciences.ca_def_groundwater#gwAquiferSystem
    click Uri href "../Uri"

        
      HttpGeosciences.caDefGroundwater#GWHydrogeoUnit : http___www.opengeospatial.org_standards_geosparql_sfIntersects
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWHydrogeoUnit --> "0..1" Any : http___www.opengeospatial.org_standards_geosparql_sfIntersects
    click Any href "../Any"

        
      HttpGeosciences.caDefGroundwater#GWHydrogeoUnit : owl_sameAs
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWHydrogeoUnit --> "0..1" Any : owl_sameAs
    click Any href "../Any"

        
      HttpGeosciences.caDefGroundwater#GWHydrogeoUnit : rdfs_label
        
          
    
    
    HttpGeosciences.caDefGroundwater#GWHydrogeoUnit --> "0..1" String : rdfs_label
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | No slot (predicate) description specified <br/> 1498 occurrences with subject type rdfs_Resource and object type rdfs_Resource.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.<br/>5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type http___geosciences.ca_def_groundwater#GW_Well. | direct |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1514 occurrences with subject type rdfs_Resource and object type string.<br/>3204 occurrences with untyped subjects and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>5 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type string.<br/>5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type string. | direct |
| [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | No slot (predicate) description specified <br/> 14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type rdfs_Resource.<br/>13 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type uri.<br/>108 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.<br/>14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.<br/>108 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type rdfs_Resource. | direct |
| [hsdo_image](../slots/hsdo_image.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)&nbsp;or&nbsp;<br />[HsdoImageObject](../classes/HsdoImageObject.md) | No slot (predicate) description specified <br/> 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>1 occurrences with subject type hsdo_Organization and object type hsdo_ImageObject.<br/>2 occurrences with subject type hsdo_NewsArticle and object type uri. | direct |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1 occurrences with subject type rdfs_Resource and object type string.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork and object type string.<br/>2 occurrences with subject type hsdo_Person and object type string.<br/>3 occurrences with subject type hsdo_Organization and object type string.<br/>48677 occurrences with subject type hsdo_WebPage and object type string.<br/>3 occurrences with subject type hsdo_ListItem and object type string.<br/>1 occurrences with subject type hsdo_WebSite and object type string. | direct |
| [hsdo_description](../slots/hsdo_description.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork and object type string.<br/>48677 occurrences with subject type hsdo_WebPage and object type string.<br/>1 occurrences with subject type hsdo_WebSite and object type string.<br/>17 occurrences with subject type hsdo_error and object type string.<br/>2 occurrences with subject type hsdo_NewsArticle and object type string. | direct |
| [http___geosciences.ca_def_groundwater#gwAquiferSystem](../slots/http___geosciences.ca_def_groundwater#gwAquiferSystem.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) | No slot (predicate) description specified <br/> 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type uri. | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) |
| [RdfsResource](../classes/RdfsResource.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) |
| [RdfsResource](../classes/RdfsResource.md) | [http___www.opengeospatial.org_standards_geosparql_sfIntersects](../slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | any_of[range] | [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://geosciences.ca/def/groundwater#GW_HydrogeoUnit |
| native | geoconnex/:HttpGeosciences.caDefGroundwater#GWHydrogeoUnit |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 3 occurrences.
from_schema: geoconnex
rank: 1000
slots:
- owl_sameAs
- rdfs_label
- http___www.opengeospatial.org_standards_geosparql_sfIntersects
- hsdo_image
- hsdo_name
- hsdo_description
- http___geosciences.ca_def_groundwater#gwAquiferSystem
class_uri: http://geosciences.ca/def/groundwater#GW_HydrogeoUnit

```
</details>

### Induced

<details>
```yaml
name: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 3 occurrences.
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
    owner: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
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
    owner: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
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
    owner: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
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
  hsdo_image:
    name: hsdo_image
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type string.
    - 1 occurrences with subject type hsdo_Organization and object type hsdo_ImageObject.
    - 2 occurrences with subject type hsdo_NewsArticle and object type uri.
    examples:
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → string
      object:
        example_object: http://gin.gw-info.net/service/ngwds//en/wms/ngwd-wms/inset?REQUEST=GetMap&SERVICE=WMS&VERSION=1.1.1&LAYERS=area&STYLES=&FORMAT=image/png&BGCOLOR=0xFFFFFF&TRANSPARENT=TRUE&SRS=EPSG:4326&BBOX=-73.6883387829505,44.9741147159004,-72.8050177950318,45.6366054568393&WIDTH=400&HEIGHT=300&TABLE=gw_data.hydrogeological_units&FIELD=id&ID=1
        example_predicate: hsdo:image
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    - description: hsdo_Organization → hsdo_ImageObject
      object:
        example_object: https://internetofwater.org/#organizationLogo
        example_predicate: hsdo:image
        example_subject: https://internetofwater.org/#organization
    - description: hsdo_NewsArticle → uri
      object:
        example_object: https://cdn.arcgis.com/sharing/rest/content/items/0ecb1aaf143b4e1981dbe30f38fceec5/resources/H3VVK2S0MqXGFbHoqFWxE.png?w=400
        example_predicate: hsdo:image
        example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pkg
    from_schema: geoconnex
    rank: 1000
    slot_uri: hsdo:image
    alias: hsdo_image
    owner: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    domain_of:
    - hsdo_NewsArticle
    - hsdo_Organization
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    range: Any
    any_of:
    - range: uri
    - range: string
    - range: hsdo_ImageObject
  hsdo_name:
    name: hsdo_name
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type rdfs_Resource and object type string.
    - 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type string.
    - 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
      and object type string.
    - 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
      and object type string.
    - 2 occurrences with subject type hsdo_Person and object type string.
    - 3 occurrences with subject type hsdo_Organization and object type string.
    - 48677 occurrences with subject type hsdo_WebPage and object type string.
    - 3 occurrences with subject type hsdo_ListItem and object type string.
    - 1 occurrences with subject type hsdo_WebSite and object type string.
    examples:
    - description: rdfs_Resource → string
      object:
        example_object: 'Watershed : Little River - Riviere Richelieu'
        example_predicate: hsdo:name
        example_subject: https://geoconnex.ca/id/catchment/02OJ*CA
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → string
      object:
        example_object: 'Hydrogeologic unit : Southern St Lawrence Platform'
        example_predicate: hsdo:name
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    - description: https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
        → string
      object:
        example_object: Waunakee Marsh-Sixmile Creek
        example_predicate: hsdo:name
        example_subject: https://geoconnex.us/SELFIE/usgs/huc/huc12obs/070900020601
    - description: https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
        → string
      object:
        example_object: Waunakee Marsh-Sixmile Creek Monitoring Network
        example_predicate: hsdo:name
        example_subject: https://geoconnex.us/SELFIE/usgs/hydrometricnetwork/huc12obs/070900020601
    - description: hsdo_Person → string
      object:
        example_object: Kyle Onda
        example_predicate: hsdo:name
        example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pl0
    - description: hsdo_Organization → string
      object:
        example_object: Esri
        example_predicate: hsdo:name
        example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27plg
    - description: hsdo_WebPage → string
      object:
        example_object: Home
        example_predicate: hsdo:name
        example_subject: https://internetofwater.org/
    - description: hsdo_ListItem → string
      object:
        example_object: Home
        example_predicate: hsdo:name
        example_subject: https://internetofwater.org/#listItem
    - description: hsdo_WebSite → string
      object:
        example_object: Internet of Water
        example_predicate: hsdo:name
        example_subject: https://internetofwater.org/#website
    from_schema: geoconnex
    rank: 1000
    slot_uri: hsdo:name
    alias: hsdo_name
    owner: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    domain_of:
    - hsdo_ListItem
    - hsdo_Organization
    - hsdo_Person
    - hsdo_WebPage
    - hsdo_WebSite
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
    - https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
    - rdfs_Resource
    range: string
  hsdo_description:
    name: hsdo_description
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type string.
    - 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
      and object type string.
    - 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
      and object type string.
    - 48677 occurrences with subject type hsdo_WebPage and object type string.
    - 1 occurrences with subject type hsdo_WebSite and object type string.
    - 17 occurrences with subject type hsdo_error and object type string.
    - 2 occurrences with subject type hsdo_NewsArticle and object type string.
    examples:
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → string
      object:
        example_object: '

          In the context of the southern area of the St. Lawrence Platform of (south
          Lowlands), the clay unit is generally not continuous or thick. The bedrock
          is rather covered by a till unit of at least 10 m thick which may allow
          significant bedrock aquifer recharge rates. This limited sedimentary cover
          suggests that there would be links between the bedrock aquifer and streams,
          particularly along some sections of the Richelieu River, which constitute
          discharge areas. The flow is oriented east-west, from the recharge areas
          to Richelieu River or others discharge areas. The surficial permeable sediments
          with significant thickness have small spatial extension, thus that the aquifer
          potential is mainly based on fractured bedrock aquifer. In the unit, there
          is a significant use of groundwater as water supply. The predominant semi-confined
          conditions involve a moderate vulnerability of the bedrock aquifer. Groundwater
          exceeds frequently some aesthetic criteria as Fe, Mn, S, Na, and F in the
          central area of the hydrogeological unit.

          '
        example_predicate: hsdo:description
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    - description: https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
        → string
      object:
        example_object: USGS Watershed Boundary Dataset Twelve Digit Hydrologic Unit
          Code Watershed
        example_predicate: hsdo:description
        example_subject: https://geoconnex.us/SELFIE/usgs/huc/huc12obs/070900020601
    - description: https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
        → string
      object:
        example_object: Monitoring locations in the Waunakee Marsh-Sixmile Creek watershed.
        example_predicate: hsdo:description
        example_subject: https://geoconnex.us/SELFIE/usgs/hydrometricnetwork/huc12obs/070900020601
    - description: hsdo_WebPage → string
      object:
        example_object: The Internet of Water Coalition works with partners to build
          modern data infrastructure & create a community of people using water data
          to make better decisions
        example_predicate: hsdo:description
        example_subject: https://internetofwater.org/
    - description: hsdo_WebSite → string
      object:
        example_object: Better Water Data for Better Water Management
        example_predicate: hsdo:description
        example_subject: https://internetofwater.org/#website
    - description: hsdo_error → string
      object:
        example_object: 'Something bad happened. Contact us with Reference Number:
          115163272'
        example_predicate: hsdo:description
        example_subject: https://gleaner.io/xid/genid/cksk7tsip8t6t2qvs9a0
    - description: hsdo_NewsArticle → string
      object:
        example_object: 'Begin with a point of interest. For example:lon: -117.12lat:
          46.43'
        example_predicate: hsdo:description
        example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pkg
    from_schema: geoconnex
    rank: 1000
    slot_uri: hsdo:description
    alias: hsdo_description
    owner: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    domain_of:
    - hsdo_NewsArticle
    - hsdo_WebPage
    - hsdo_WebSite
    - hsdo_error
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
    - https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
    range: string
  http___geosciences.ca_def_groundwater#gwAquiferSystem:
    name: http___geosciences.ca_def_groundwater#gwAquiferSystem
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
      and object type uri.
    examples:
    - description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → uri
      object:
        example_object: https://geoconnex.ca/id/aquiferSystems/Richelieu
        example_predicate: http://geosciences.ca/def/groundwater#gwAquiferSystem
        example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    from_schema: geoconnex
    rank: 1000
    slot_uri: http://geosciences.ca/def/groundwater#gwAquiferSystem
    alias: http___geosciences.ca_def_groundwater#gwAquiferSystem
    owner: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    domain_of:
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    range: uri
class_uri: http://geosciences.ca/def/groundwater#GW_HydrogeoUnit

```
</details>