

# Slot: serviceUrl (sdoh_serviceUrl)


_The website to access the service._





URI: [sdoh:serviceUrl](http://schema.org/serviceUrl)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohServiceChannel](../classes/SdohServiceChannel.md) | A means for accessing a service, e |  no  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| dreamkg:service/channel/AB-6453846037626880 sdoh:serviceUrl https://www.auntbertha.com//helping-hands-ministry%252C-inc.--philadelphia-pa--social-services---basic-needs-assistance/6453846037626880?postal=19135 |

## Comments

* 188 occurrences with subject type sdoh_ServiceChannel and object type uri.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:serviceUrl |
| native | dream-kg/:sdoh_serviceUrl |




## LinkML Source

<details>
```yaml
name: sdoh_serviceUrl
description: The website to access the service.
title: serviceUrl
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 188 occurrences with subject type sdoh_ServiceChannel and object type uri.
examples:
- value: dreamkg:service/channel/AB-6453846037626880 sdoh:serviceUrl https://www.auntbertha.com//helping-hands-ministry%252C-inc.--philadelphia-pa--social-services---basic-needs-assistance/6453846037626880?postal=19135
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:serviceUrl
alias: sdoh_serviceUrl
domain_of:
- sdoh_ServiceChannel
range: uri

```
</details>