

# Slot: TODO -- tell the world what this slot (predicate) describes. (contaminoso_ofSubstance)


_TODO -- tell the world what this slot (predicate) describes._





URI: [contaminoso:ofSubstance](http://sawgraph.spatialai.org/v1/contaminoso#ofSubstance)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoContaminantObservation](../classes/ContaminosoContaminantObservation.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ContaminosoSubstance](../classes/ContaminosoSubstance.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA contaminoso:ofSubstance http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-PFAS.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA |
| http://sawgraph.spatialai.org/v1/me-egad-data#observation.4101220941.TAI.20221208.DEP18029 contaminoso:ofSubstance meegad:parameter.SUM_PFOA_A_L-PFOA_A_BR |

## Comments

* 143027 occurrences with subject type contaminoso_ContaminantObservation and object type contaminoso_Substance.
* 37 occurrences with subject type contaminoso_ContaminantObservation and object type uri.

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
| self | contaminoso:ofSubstance |
| native | sawgraph-kg/:contaminoso_ofSubstance |




## LinkML Source

<details>
```yaml
name: contaminoso_ofSubstance
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 143027 occurrences with subject type contaminoso_ContaminantObservation and object
  type contaminoso_Substance.
- 37 occurrences with subject type contaminoso_ContaminantObservation and object type
  uri.
examples:
- value: http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
    contaminoso:ofSubstance http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-PFAS.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
- value: http://sawgraph.spatialai.org/v1/me-egad-data#observation.4101220941.TAI.20221208.DEP18029
    contaminoso:ofSubstance meegad:parameter.SUM_PFOA_A_L-PFOA_A_BR
from_schema: sawgraph-kg
rank: 1000
slot_uri: contaminoso:ofSubstance
alias: contaminoso_ofSubstance
domain_of:
- contaminoso_ContaminantObservation
subproperty_of: sosa_observedProperty
range: Any
any_of:
- range: contaminoso_Substance
- range: uri

```
</details>