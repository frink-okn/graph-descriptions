

# Slot: No slot description provided (sosa_observedProperty)


_No slot description provided_





URI: [sosa:observedProperty](http://www.w3.org/ns/sosa/observedProperty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoContaminantObservation](../classes/ContaminosoContaminantObservation.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ContaminosoSubstance](../classes/ContaminosoSubstance.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA sosa:observedProperty http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-PFAS.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA |
| http://sawgraph.spatialai.org/v1/me-egad-data#observation.4101220941.TAI.20221208.DEP18029 sosa:observedProperty meegad:parameter.SUM_PFOA_A_L-PFOA_A_BR |

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
| self | sosa:observedProperty |
| native | sawgraph-kg/:sosa_observedProperty |




## LinkML Source

<details>
```yaml
name: sosa_observedProperty
description: No slot description provided
title: No slot description provided
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
    sosa:observedProperty http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-PFAS.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
- value: http://sawgraph.spatialai.org/v1/me-egad-data#observation.4101220941.TAI.20221208.DEP18029
    sosa:observedProperty meegad:parameter.SUM_PFOA_A_L-PFOA_A_BR
from_schema: sawgraph-kg
rank: 1000
slot_uri: sosa:observedProperty
alias: sosa_observedProperty
domain_of:
- contaminoso_ContaminantObservation
range: Any
any_of:
- range: contaminoso_Substance
- range: uri

```
</details>