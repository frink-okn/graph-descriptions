

# Slot: No slot (predicate) name specified (skos_definition)


_No slot (predicate) description specified_






This slot occurs 62 times.


URI: [skos:definition](http://www.w3.org/2004/02/skos/core#definition)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-SiteType](../classes/MeEgadEGAD-SiteType.md) | No class (type) description specified |  no  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_NamedIndividual | string | me_egad_data:siteType.AGRICFARM | Includes dairies, feedlots, large herds of livestock, and chicken farms, as well as areas with recent sludge spreading as part of the Statewide PFAS Investigation under Maine LD 1600 | 62 |




## LinkML Source

<details>

```yaml
name: skos_definition
annotations:
  count:
    tag: count
    value: 62
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Includes dairies, feedlots, large herds of livestock, and chicken
      farms, as well as areas with recent sludge spreading as part of the Statewide
      PFAS Investigation under Maine LD 1600
    example_object_type: string
    example_predicate: skos:definition
    example_subject: me_egad_data:siteType.AGRICFARM
    example_subject_type: owl_NamedIndividual
from_schema: sawgraph-kg
rank: 1000
slot_uri: skos:definition
alias: skos_definition
domain_of:
- owl_NamedIndividual
- me_egad_EGAD-SiteType
range: string

```
</details>