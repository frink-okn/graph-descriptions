

# Slot: used analysis method (coso_usedAnalysisMethod)


_A relation between an observation of a contaminant and the analysis method that was used to perform the observation._







URI: [coso:usedAnalysisMethod](http://w3id.org/coso/v1/contaminoso#usedAnalysisMethod)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[CosoAnalysisMethod](../classes/CosoAnalysisMethod.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[SosaProcedure](../classes/SosaProcedure.md)





## Comments

* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: coso_usedAnalysisMethod
description: A relation between an observation of a contaminant and the analysis method
  that was used to perform the observation.
title: used analysis method
comments:
- No occurrences of this slot in the graph.
from_schema: sawgraph-kg
rank: 1000
slot_uri: coso:usedAnalysisMethod
alias: coso_usedAnalysisMethod
subproperty_of: sosa_usedProcedure
union_of:
- '{''domain'': ''owl_Thing''}'
- '{''domain'': ''sosa_Observation''}'
- '{''domain'': ''coso_ContaminantObservation''}'
range: Any
any_of:
- range: coso_AnalysisMethod
- range: owl_Thing
- range: sosa_Procedure

```
</details>