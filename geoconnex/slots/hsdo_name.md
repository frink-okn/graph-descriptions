

# Slot: hsdo_name


_No slot (predicate) description specified_





URI: [hsdo:name](http://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrometricNetwork](../classes/HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrometricNetwork.md) | No class (type) description specified |  no  |
| [HsdoWebSite](../classes/HsdoWebSite.md) | A WebSite is a set of related web pages and other items typically served from... |  no  |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [HsdoPerson](../classes/HsdoPerson.md) | A person (alive, dead, undead, or fictional) |  no  |
| [HsdoWebPage](../classes/HsdoWebPage.md) | A web page |  no  |
| [HsdoListItem](../classes/HsdoListItem.md) | An list item, e |  no  |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | No class (type) description specified |  no  |
| [HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYCatchment](../classes/HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYCatchment.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rdfs_Resource → string | https://geoconnex.ca/id/catchment/02OJ*CA | hsdo:name | Watershed : Little River - Riviere Richelieu |
| http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → string | https://geoconnex.ca/id/hydrogeounits/Richelieu1 | hsdo:name | Hydrogeologic unit : Southern St Lawrence Platform |
| https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment → string | https://geoconnex.us/SELFIE/usgs/huc/huc12obs/070900020601 | hsdo:name | Waunakee Marsh-Sixmile Creek |
| https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork → string | https://geoconnex.us/SELFIE/usgs/hydrometricnetwork/huc12obs/070900020601 | hsdo:name | Waunakee Marsh-Sixmile Creek Monitoring Network |
| hsdo_Person → string | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pl0 | hsdo:name | Kyle Onda |
| hsdo_Organization → string | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27plg | hsdo:name | Esri |
| hsdo_WebPage → string | https://internetofwater.org/ | hsdo:name | Home |
| hsdo_ListItem → string | https://internetofwater.org/#listItem | hsdo:name | Home |
| hsdo_WebSite → string | https://internetofwater.org/#website | hsdo:name | Internet of Water |


## Comments

* 1 occurrences with subject type rdfs_Resource and object type string.
* 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.
* 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type string.
* 1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork and object type string.
* 2 occurrences with subject type hsdo_Person and object type string.
* 3 occurrences with subject type hsdo_Organization and object type string.
* 48677 occurrences with subject type hsdo_WebPage and object type string.
* 3 occurrences with subject type hsdo_ListItem and object type string.
* 1 occurrences with subject type hsdo_WebSite and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:name |
| native | geoconnex/:hsdo_name |




## LinkML Source

<details>
```yaml
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

```
</details>