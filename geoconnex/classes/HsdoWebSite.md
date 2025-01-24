

# Class: WebSite (hsdo_WebSite)


_A WebSite is a set of related web pages and other items typically served from a single web domain and accessible via URLs._





URI: [hsdo:WebSite](http://schema.org/WebSite)






```mermaid
 classDiagram
    class HsdoWebSite
    click HsdoWebSite href "../HsdoWebSite"
      HsdoWebSite : hsdo_description
        
          
    
    
    HsdoWebSite --> "0..1" String : hsdo_description
    click String href "../String"

        
      HsdoWebSite : hsdo_inLanguage
        
          
    
    
    HsdoWebSite --> "0..1" String : hsdo_inLanguage
    click String href "../String"

        
      HsdoWebSite : hsdo_name
        
          
    
    
    HsdoWebSite --> "0..1" String : hsdo_name
    click String href "../String"

        
      HsdoWebSite : hsdo_potentialAction
        
          
    
    
    HsdoWebSite --> "0..1" HsdoSearchAction : hsdo_potentialAction
    click HsdoSearchAction href "../HsdoSearchAction"

        
      HsdoWebSite : hsdo_publisher
        
          
    
    
    HsdoWebSite --> "0..1" HsdoOrganization : hsdo_publisher
    click HsdoOrganization href "../HsdoOrganization"

        
      HsdoWebSite : hsdo_url
        
          
    
    
    HsdoWebSite --> "0..1" Any : hsdo_url
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [hsdo_potentialAction](../slots/hsdo_potentialAction.md) | 0..1 <br/> [HsdoSearchAction](../classes/HsdoSearchAction.md) | No slot (predicate) description specified <br/> 1 occurrences with subject type hsdo_WebSite and object type hsdo_SearchAction. | direct |
| [hsdo_publisher](../slots/hsdo_publisher.md) | 0..1 <br/> [HsdoOrganization](../classes/HsdoOrganization.md) | No slot (predicate) description specified <br/> 1 occurrences with subject type hsdo_WebSite and object type hsdo_Organization.<br/>2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Organization. | direct |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1 occurrences with subject type rdfs_Resource and object type string.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork and object type string.<br/>2 occurrences with subject type hsdo_Person and object type string.<br/>3 occurrences with subject type hsdo_Organization and object type string.<br/>48677 occurrences with subject type hsdo_WebPage and object type string.<br/>3 occurrences with subject type hsdo_ListItem and object type string.<br/>1 occurrences with subject type hsdo_WebSite and object type string. | direct |
| [hsdo_description](../slots/hsdo_description.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork and object type string.<br/>48677 occurrences with subject type hsdo_WebPage and object type string.<br/>1 occurrences with subject type hsdo_WebSite and object type string.<br/>17 occurrences with subject type hsdo_error and object type string.<br/>2 occurrences with subject type hsdo_NewsArticle and object type string. | direct |
| [hsdo_inLanguage](../slots/hsdo_inLanguage.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 1 occurrences with subject type hsdo_WebSite and object type string.<br/>3 occurrences with subject type hsdo_WebPage and object type string. | direct |
| [hsdo_url](../slots/hsdo_url.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[HsdoWebPage](../classes/HsdoWebPage.md) | No slot (predicate) description specified <br/> 5 occurrences with subject type hsdo_ImageObject and object type uri.<br/>4 occurrences with subject type hsdo_WebPage and object type hsdo_WebPage.<br/>1 occurrences with subject type hsdo_Organization and object type hsdo_WebPage.<br/>1 occurrences with subject type hsdo_WebSite and object type hsdo_WebPage.<br/>1 occurrences with subject type hsdo_WebPage and object type uri. | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HsdoWebPage](../classes/HsdoWebPage.md) | [hsdo_isPartOf](../slots/hsdo_isPartOf.md) | range | [HsdoWebSite](../classes/HsdoWebSite.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:WebSite |
| native | geoconnex/:HsdoWebSite |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: hsdo_WebSite
conforms_to: No schema conformance document specified
description: A WebSite is a set of related web pages and other items typically served
  from a single web domain and accessible via URLs.
title: WebSite
notes:
- Class with 1 occurrences.
from_schema: geoconnex
rank: 1000
slots:
- hsdo_potentialAction
- hsdo_publisher
- hsdo_name
- hsdo_description
- hsdo_inLanguage
- hsdo_url
class_uri: hsdo:WebSite

```
</details>

### Induced

<details>
```yaml
name: hsdo_WebSite
conforms_to: No schema conformance document specified
description: A WebSite is a set of related web pages and other items typically served
  from a single web domain and accessible via URLs.
title: WebSite
notes:
- Class with 1 occurrences.
from_schema: geoconnex
rank: 1000
attributes:
  hsdo_potentialAction:
    name: hsdo_potentialAction
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type hsdo_WebSite and object type hsdo_SearchAction.
    examples:
    - description: hsdo_WebSite → hsdo_SearchAction
      object:
        example_object: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pjg
        example_predicate: hsdo:potentialAction
        example_subject: https://internetofwater.org/#website
    from_schema: geoconnex
    rank: 1000
    slot_uri: hsdo:potentialAction
    alias: hsdo_potentialAction
    owner: hsdo_WebSite
    domain_of:
    - hsdo_WebSite
    range: hsdo_SearchAction
  hsdo_publisher:
    name: hsdo_publisher
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type hsdo_WebSite and object type hsdo_Organization.
    - 2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Organization.
    examples:
    - description: hsdo_WebSite → hsdo_Organization
      object:
        example_object: https://internetofwater.org/#organization
        example_predicate: hsdo:publisher
        example_subject: https://internetofwater.org/#website
    - description: hsdo_NewsArticle → hsdo_Organization
      object:
        example_object: https://gleaner.io/xid/genid/cktr9esip8ta6ev27png
        example_predicate: hsdo:publisher
        example_subject: https://gleaner.io/xid/genid/cktr9esip8ta6ev27pmg
    from_schema: geoconnex
    rank: 1000
    slot_uri: hsdo:publisher
    alias: hsdo_publisher
    owner: hsdo_WebSite
    domain_of:
    - hsdo_NewsArticle
    - hsdo_WebSite
    range: hsdo_Organization
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
    owner: hsdo_WebSite
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
    owner: hsdo_WebSite
    domain_of:
    - hsdo_NewsArticle
    - hsdo_WebPage
    - hsdo_WebSite
    - hsdo_error
    - http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
    - https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment
    - https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork
    range: string
  hsdo_inLanguage:
    name: hsdo_inLanguage
    description: No slot (predicate) description specified
    comments:
    - 1 occurrences with subject type hsdo_WebSite and object type string.
    - 3 occurrences with subject type hsdo_WebPage and object type string.
    examples:
    - description: hsdo_WebSite → string
      object:
        example_object: en-US
        example_predicate: hsdo:inLanguage
        example_subject: https://internetofwater.org/#website
    - description: hsdo_WebPage → string
      object:
        example_object: en-US
        example_predicate: hsdo:inLanguage
        example_subject: https://internetofwater.org/#webpage
    from_schema: geoconnex
    rank: 1000
    slot_uri: hsdo:inLanguage
    alias: hsdo_inLanguage
    owner: hsdo_WebSite
    domain_of:
    - hsdo_WebPage
    - hsdo_WebSite
    range: string
  hsdo_url:
    name: hsdo_url
    description: No slot (predicate) description specified
    comments:
    - 5 occurrences with subject type hsdo_ImageObject and object type uri.
    - 4 occurrences with subject type hsdo_WebPage and object type hsdo_WebPage.
    - 1 occurrences with subject type hsdo_Organization and object type hsdo_WebPage.
    - 1 occurrences with subject type hsdo_WebSite and object type hsdo_WebPage.
    - 1 occurrences with subject type hsdo_WebPage and object type uri.
    examples:
    - description: hsdo_ImageObject → uri
      object:
        example_object: https://storymaps.arcgis.com/static/images/logo.png
        example_predicate: hsdo:url
        example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pm0
    - description: hsdo_WebPage → hsdo_WebPage
      object:
        example_object: https://internetofwater.org/internet-of-water-principles/
        example_predicate: hsdo:url
        example_subject: https://internetofwater.org/internet-of-water-principles/#webpage
    - description: hsdo_Organization → hsdo_WebPage
      object:
        example_object: https://internetofwater.org/
        example_predicate: hsdo:url
        example_subject: https://internetofwater.org/#organization
    - description: hsdo_WebSite → hsdo_WebPage
      object:
        example_object: https://internetofwater.org/
        example_predicate: hsdo:url
        example_subject: https://internetofwater.org/#website
    - description: hsdo_WebPage → uri
      object:
        example_object: https://internetofwater.org/who-we-are/
        example_predicate: hsdo:url
        example_subject: https://internetofwater.org/who-we-are/#webpage
    from_schema: geoconnex
    rank: 1000
    slot_uri: hsdo:url
    alias: hsdo_url
    owner: hsdo_WebSite
    domain_of:
    - hsdo_ImageObject
    - hsdo_Organization
    - hsdo_WebPage
    - hsdo_WebSite
    range: Any
    any_of:
    - range: uri
    - range: hsdo_WebPage
class_uri: hsdo:WebSite

```
</details>