

# Slot: provider (hsdo_provider)


_The service provider, service operator, or service performer; the goods producer. Another party (a seller) may offer those services or goods on behalf of the provider. A provider may also serve as the seller._






This slot occurs 87 times.


URI: [hsdo:provider](http://schema.org/provider)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |







## Properties

* Range: [HsdoOrganization](../classes/HsdoOrganization.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Service | hsdo_Organization | dreamkg:service/6379467169595392 | dreamkg:service/provider/6379467169595392 | 87 |




## LinkML Source

<details>

```yaml
name: hsdo_provider
annotations:
  count:
    tag: count
    value: 87
description: The service provider, service operator, or service performer; the goods
  producer. Another party (a seller) may offer those services or goods on behalf of
  the provider. A provider may also serve as the seller.
title: provider
examples:
- description: hsdo_Service→hsdo_Organization
  object:
    example_object: dreamkg:service/provider/6379467169595392
    example_object_type: hsdo_Organization
    example_predicate: hsdo:provider
    example_subject: dreamkg:service/6379467169595392
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:provider
alias: hsdo_provider
domain_of:
- hsdo_Service
range: hsdo_Organization

```
</details>