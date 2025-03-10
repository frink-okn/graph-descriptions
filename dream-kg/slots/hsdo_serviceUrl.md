

# Slot: hsdo_serviceUrl


_The website to access the service._






This slot occurs 188 times.


URI: [schema:serviceUrl](http://schema.org/serviceUrl)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | A means for accessing a service, e |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_ServiceChannel | uri | dreamkg:service/channel/AB-4542572480692224 | https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224?postal=19139 | 188 |




## LinkML Source

<details>

```yaml
name: hsdo_serviceUrl
annotations:
  count:
    tag: count
    value: 188
description: The website to access the service.
examples:
- object:
    example_object: https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224?postal=19139
    example_object_type: uri
    example_predicate: schema:serviceUrl
    example_subject: dreamkg:service/channel/AB-4542572480692224
    example_subject_type: hsdo_ServiceChannel
from_schema: dream-kg
rank: 1000
slot_uri: schema:serviceUrl
alias: hsdo_serviceUrl
domain_of:
- hsdo_ServiceChannel
range: uri

```
</details>