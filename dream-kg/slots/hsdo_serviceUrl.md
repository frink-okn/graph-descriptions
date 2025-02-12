

# Slot: serviceUrl (hsdo_serviceUrl)


_The website to access the service._






This slot occurs 188 times.


URI: [hsdo:serviceUrl](http://schema.org/serviceUrl)



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
| hsdo_ServiceChannel | uri | dreamkg:service/channel/AB-5922109384294400 | https://www.auntbertha.com//catholic-social-services-of-the-archdiocese-of-philadelphia---saint-john%2527s-hospice-%2528sjh%2529--philadelphia-pa--good-shepherd/5922109384294400?postal=19102 | 188 |




## LinkML Source

<details>

```yaml
name: hsdo_serviceUrl
annotations:
  count:
    tag: count
    value: 188
description: The website to access the service.
title: serviceUrl
examples:
- description: hsdo_ServiceChannel→uri
  object:
    example_object: https://www.auntbertha.com//catholic-social-services-of-the-archdiocese-of-philadelphia---saint-john%2527s-hospice-%2528sjh%2529--philadelphia-pa--good-shepherd/5922109384294400?postal=19102
    example_object_type: uri
    example_predicate: hsdo:serviceUrl
    example_subject: dreamkg:service/channel/AB-5922109384294400
    example_subject_type: hsdo_ServiceChannel
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:serviceUrl
alias: hsdo_serviceUrl
domain_of:
- hsdo_ServiceChannel
range: uri

```
</details>