

# Slot: hsdo_serviceUrl


_No slot (predicate) description specified_





URI: [hsdo:serviceUrl](http://schema.org/serviceUrl)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | A means for accessing a service, e |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_ServiceChannel → uri | dreamkg:service/channel/AB-6032260047568896 | hsdo:serviceUrl | https://www.auntbertha.com//merakey---pennsylvania--philadelphia-pa--adult-substance-use-disorder-services/6032260047568896?postal=19139 |


## Comments

* 188 occurrences with subject type hsdo_ServiceChannel and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:serviceUrl |
| native | dream-kg/:hsdo_serviceUrl |




## LinkML Source

<details>
```yaml
name: hsdo_serviceUrl
description: No slot (predicate) description specified
comments:
- 188 occurrences with subject type hsdo_ServiceChannel and object type uri.
examples:
- description: hsdo_ServiceChannel → uri
  object:
    example_object: https://www.auntbertha.com//merakey---pennsylvania--philadelphia-pa--adult-substance-use-disorder-services/6032260047568896?postal=19139
    example_predicate: hsdo:serviceUrl
    example_subject: dreamkg:service/channel/AB-6032260047568896
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:serviceUrl
alias: hsdo_serviceUrl
domain_of:
- hsdo_ServiceChannel
range: uri

```
</details>