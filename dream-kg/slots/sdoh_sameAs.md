

# Slot: sameAs (sdoh_sameAs)


_URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website._





URI: [sdoh:sameAs](http://schema.org/sameAs)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohOrganization](../classes/SdohOrganization.md) | An organization such as a school, NGO, corporation, club, etc |  no  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| dreamkg:service/provider/4874573658193920 sdoh:sameAs https://www.twitter.com/@WedgeRecovery |

## Comments

* 127 occurrences with subject type sdoh_Organization and object type uri.

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
| self | sdoh:sameAs |
| native | dream-kg/:sdoh_sameAs |




## LinkML Source

<details>
```yaml
name: sdoh_sameAs
description: URL of a reference Web page that unambiguously indicates the item's identity.
  E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website.
title: sameAs
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 127 occurrences with subject type sdoh_Organization and object type uri.
examples:
- value: dreamkg:service/provider/4874573658193920 sdoh:sameAs https://www.twitter.com/@WedgeRecovery
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:sameAs
alias: sdoh_sameAs
domain_of:
- sdoh_Organization
range: uri

```
</details>