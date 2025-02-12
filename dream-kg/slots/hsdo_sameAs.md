

# Slot: sameAs (hsdo_sameAs)


_URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website._






This slot occurs 127 times.


URI: [hsdo:sameAs](http://schema.org/sameAs)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Organization | uri | dreamkg:service/provider/5017006984921088 | https://www.facebook.com/sainthelenaparish | 127 |




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
title: sameAs
examples:
- description: hsdo_Organization→uri
  object:
    example_object: https://www.facebook.com/sainthelenaparish
    example_object_type: uri
    example_predicate: hsdo:sameAs
    example_subject: dreamkg:service/provider/5017006984921088
    example_subject_type: hsdo_Organization
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:sameAs
alias: hsdo_sameAs
domain_of:
- hsdo_Organization
range: uri

```
</details>