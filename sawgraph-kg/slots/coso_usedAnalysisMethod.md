

# Slot: used analysis method (coso_usedAnalysisMethod)


_A relation between an observation of a contaminant and the analysis method that was used to perform the observation._







URI: [coso:usedAnalysisMethod](http://w3id.org/coso/v1/contaminoso#usedAnalysisMethod)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[CosoAnalysisMethod](../classes/CosoAnalysisMethod.md)&nbsp;or&nbsp;<br />[SosaProcedure](../classes/SosaProcedure.md)







## LinkML Source

<details>

```yaml
name: coso_usedAnalysisMethod
description: A relation between an observation of a contaminant and the analysis method
  that was used to perform the observation.
title: used analysis method
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:usedAnalysisMethod
alias: coso_usedAnalysisMethod
subproperty_of: sosa_usedProcedure
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: owl_Thing
- range: coso_AnalysisMethod
- range: sosa_Procedure

```
</details>