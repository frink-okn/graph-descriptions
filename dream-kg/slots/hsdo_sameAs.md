

# Slot: hsdo_sameAs


_URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website._






This slot occurs 127 times.


URI: [schema:sameAs](http://schema.org/sameAs)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Organization | uri | dreamkg:service/provider/4542572480692224 | https://www.facebook.com/ChildGuidanceResourceCenters | 127 |
| prov_Entity | uri | dreamkg:service/provider/4542572480692224 | https://www.facebook.com/ChildGuidanceResourceCenters | 127 |




## LinkML Source

<details>

```yaml
name: hsdo_sameAs
annotations:
  count:
    tag: count
    value: 127
description: URL of a reference Web page that unambiguously indicates the item's identity.
  E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website.
examples:
- object:
    example_object: https://www.facebook.com/ChildGuidanceResourceCenters
    example_object_type: uri
    example_predicate: schema:sameAs
    example_subject: dreamkg:service/provider/4542572480692224
    example_subject_type: hsdo_Organization
- object:
    example_object: https://www.facebook.com/ChildGuidanceResourceCenters
    example_object_type: uri
    example_predicate: schema:sameAs
    example_subject: dreamkg:service/provider/4542572480692224
    example_subject_type: prov_Entity
from_schema: dream-kg
rank: 1000
slot_uri: schema:sameAs
alias: hsdo_sameAs
domain_of:
- hsdo_Organization
- prov_Entity
range: uri

```
</details>