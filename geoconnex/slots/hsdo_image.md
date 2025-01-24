

# Slot: hsdo_image


_No slot (predicate) description specified_





URI: [hsdo:image](http://schema.org/image)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | No class (type) description specified |  no  |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [HsdoNewsArticle](../classes/HsdoNewsArticle.md) | A NewsArticle is an article whose content reports news, or provides backgroun... |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)&nbsp;or&nbsp;<br />[HsdoImageObject](../classes/HsdoImageObject.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → string | https://geoconnex.ca/id/hydrogeounits/Richelieu1 | hsdo:image | http://gin.gw-info.net/service/ngwds//en/wms/ngwd-wms/inset?REQUEST=GetMap&SERVICE=WMS&VERSION=1.1.1&LAYERS=area&STYLES=&FORMAT=image/png&BGCOLOR=0xFFFFFF&TRANSPARENT=TRUE&SRS=EPSG:4326&BBOX=-73.6883387829505,44.9741147159004,-72.8050177950318,45.6366054568393&WIDTH=400&HEIGHT=300&TABLE=gw_data.hydrogeological_units&FIELD=id&ID=1 |
| hsdo_Organization → hsdo_ImageObject | https://internetofwater.org/#organization | hsdo:image | https://internetofwater.org/#organizationLogo |
| hsdo_NewsArticle → uri | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pkg | hsdo:image | https://cdn.arcgis.com/sharing/rest/content/items/0ecb1aaf143b4e1981dbe30f38fceec5/resources/H3VVK2S0MqXGFbHoqFWxE.png?w=400 |


## Comments

* 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.
* 1 occurrences with subject type hsdo_Organization and object type hsdo_ImageObject.
* 2 occurrences with subject type hsdo_NewsArticle and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:image |
| native | geoconnex/:hsdo_image |




## LinkML Source

<details>
```yaml
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
domain_of:
- hsdo_NewsArticle
- hsdo_Organization
- http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
range: Any
any_of:
- range: uri
- range: string
- range: hsdo_ImageObject

```
</details>