

# Slot: provider (hsdo_provider)


_The service provider, service operator, or service performer; the goods producer. Another party (a seller) may offer those services or goods on behalf of the provider. A provider may also serve as the seller._






This slot occurs 87 times.


URI: [hsdo:provider](http://schema.org/provider)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ProvEntity](../classes/ProvEntity.md)&nbsp;or&nbsp;<br />[HsdoOrganization](../classes/HsdoOrganization.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Service | hsdo_Organization | dreamkg:service/4542572480692224 | dreamkg:service/provider/4542572480692224 | 87 |
| hsdo_Service | prov_Entity | dreamkg:service/4542572480692224 | dreamkg:service/provider/4542572480692224 | 87 |
| prov_Entity | hsdo_Organization | dreamkg:service/4542572480692224 | dreamkg:service/provider/4542572480692224 | 87 |
| prov_Entity | prov_Entity | dreamkg:service/4542572480692224 | dreamkg:service/provider/4542572480692224 | 87 |




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
- object:
    example_object: dreamkg:service/provider/4542572480692224
    example_object_type: hsdo_Organization
    example_predicate: hsdo:provider
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: dreamkg:service/provider/4542572480692224
    example_object_type: prov_Entity
    example_predicate: hsdo:provider
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: hsdo_Service
- object:
    example_object: dreamkg:service/provider/4542572480692224
    example_object_type: hsdo_Organization
    example_predicate: hsdo:provider
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:service/provider/4542572480692224
    example_object_type: prov_Entity
    example_predicate: hsdo:provider
    example_subject: dreamkg:service/4542572480692224
    example_subject_type: prov_Entity
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:provider
alias: hsdo_provider
domain_of:
- hsdo_Service
- prov_Entity
range: Any
any_of:
- range: prov_Entity
- range: hsdo_Organization

```
</details>