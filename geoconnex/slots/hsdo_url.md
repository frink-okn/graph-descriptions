

# Slot: hsdo_url


_No slot (predicate) description specified_





URI: [hsdo:url](http://schema.org/url)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |
| [HsdoImageObject](../classes/HsdoImageObject.md) | An image file |  no  |
| [HsdoWebPage](../classes/HsdoWebPage.md) | A web page |  no  |
| [HsdoWebSite](../classes/HsdoWebSite.md) | A WebSite is a set of related web pages and other items typically served from... |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[HsdoWebPage](../classes/HsdoWebPage.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_ImageObject → uri | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pm0 | hsdo:url | https://storymaps.arcgis.com/static/images/logo.png |
| hsdo_WebPage → hsdo_WebPage | https://internetofwater.org/internet-of-water-principles/#webpage | hsdo:url | https://internetofwater.org/internet-of-water-principles/ |
| hsdo_Organization → hsdo_WebPage | https://internetofwater.org/#organization | hsdo:url | https://internetofwater.org/ |
| hsdo_WebSite → hsdo_WebPage | https://internetofwater.org/#website | hsdo:url | https://internetofwater.org/ |
| hsdo_WebPage → uri | https://internetofwater.org/who-we-are/#webpage | hsdo:url | https://internetofwater.org/who-we-are/ |


## Comments

* 5 occurrences with subject type hsdo_ImageObject and object type uri.
* 4 occurrences with subject type hsdo_WebPage and object type hsdo_WebPage.
* 1 occurrences with subject type hsdo_Organization and object type hsdo_WebPage.
* 1 occurrences with subject type hsdo_WebSite and object type hsdo_WebPage.
* 1 occurrences with subject type hsdo_WebPage and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:url |
| native | geoconnex/:hsdo_url |




## LinkML Source

<details>
```yaml
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
domain_of:
- hsdo_ImageObject
- hsdo_Organization
- hsdo_WebPage
- hsdo_WebSite
range: Any
any_of:
- range: uri
- range: hsdo_WebPage

```
</details>