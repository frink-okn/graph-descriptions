

# Slot: TODO -- tell the world what this slot (predicate) describes. (contaminoso_analyzedBy)


_TODO -- tell the world what this slot (predicate) describes._





URI: [contaminoso:analyzedBy](http://sawgraph.spatialai.org/v1/contaminoso#analyzedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoContaminantObservation](../classes/ContaminosoContaminantObservation.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [ProvOrganization](../classes/ProvOrganization.md)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#observation.WG17410824.AAWH.20230125.DEP18018 contaminoso:analyzedBy http://sawgraph.spatialai.org/v1/me-egad-data#organization.lab.AAWH |

## Comments

* 142175 occurrences with subject type contaminoso_ContaminantObservation and object type prov_Organization.

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
| self | contaminoso:analyzedBy |
| native | sawgraph-kg/:contaminoso_analyzedBy |




## LinkML Source

<details>
```yaml
name: contaminoso_analyzedBy
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 142175 occurrences with subject type contaminoso_ContaminantObservation and object
  type prov_Organization.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#observation.WG17410824.AAWH.20230125.DEP18018
    contaminoso:analyzedBy http://sawgraph.spatialai.org/v1/me-egad-data#organization.lab.AAWH
from_schema: sawgraph-kg
rank: 1000
slot_uri: contaminoso:analyzedBy
alias: contaminoso_analyzedBy
domain_of:
- contaminoso_ContaminantObservation
range: prov_Organization

```
</details>