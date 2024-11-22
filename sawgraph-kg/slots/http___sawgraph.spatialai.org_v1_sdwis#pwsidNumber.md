

# Slot: TODO -- tell the world what this slot (predicate) describes. (http___sawgraph.spatialai.org_v1_sdwis#pwsidNumber)


_Uniquely identifies the water system within a specific state. Format: SSXXXXXXXXXX where: SS = the Federal Information Processing Standard (FIPS) Pub 5-2 State abbreviation in which the water system is located, or the region number of the EPA region responsible for an Indian reservation, and XXXXXXXXXX = the water system identification code assigned by the State._





URI: [http://sawgraph.spatialai.org/v1/sdwis#pwsidNumber](http://sawgraph.spatialai.org/v1/sdwis#pwsidNumber)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeegadEGAD-Site](../classes/MeegadEGAD-Site.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#site.124837 http://sawgraph.spatialai.org/v1/sdwis#pwsidNumber ME0002893 |

## Comments

* 61 occurrences with subject type meegad_EGAD-Site and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sawgraph-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://sawgraph.spatialai.org/v1/sdwis#pwsidNumber |
| native | sawgraph-kg/:http___sawgraph.spatialai.org_v1_sdwis#pwsidNumber |




## LinkML Source

<details>
```yaml
name: http___sawgraph.spatialai.org_v1_sdwis#pwsidNumber
description: 'Uniquely identifies the water system within a specific state. Format:
  SSXXXXXXXXXX where: SS = the Federal Information Processing Standard (FIPS) Pub
  5-2 State abbreviation in which the water system is located, or the region number
  of the EPA region responsible for an Indian reservation, and XXXXXXXXXX = the water
  system identification code assigned by the State.'
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 61 occurrences with subject type meegad_EGAD-Site and object type string.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#site.124837 http://sawgraph.spatialai.org/v1/sdwis#pwsidNumber
    ME0002893
from_schema: sawgraph-kg
rank: 1000
slot_uri: http://sawgraph.spatialai.org/v1/sdwis#pwsidNumber
alias: http___sawgraph.spatialai.org_v1_sdwis#pwsidNumber
domain_of:
- meegad_EGAD-Site
range: string

```
</details>