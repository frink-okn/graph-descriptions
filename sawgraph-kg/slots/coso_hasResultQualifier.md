

# Slot: has result qualifier (coso_hasResultQualifier)


_A relation between measured result and metadata that qualifies the result._







URI: [coso:hasResultQualifier](http://w3id.org/coso/v1/contaminoso#hasResultQualifier)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[CosoResultQualifier](../classes/CosoResultQualifier.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)





## Comments

* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: coso_hasResultQualifier
description: A relation between measured result and metadata that qualifies the result.
title: has result qualifier
comments:
- No occurrences of this slot in the graph.
from_schema: sawgraph-kg
rank: 1000
slot_uri: coso:hasResultQualifier
alias: coso_hasResultQualifier
union_of:
- '{''domain'': ''qudt_Concept''}'
- '{''domain'': ''qudt_Quantifiable''}'
- '{''domain'': ''owl_Thing''}'
- '{''domain'': ''qudt_Quantity''}'
- '{''domain'': ''__B0ec50ed72490f52ac3672a1e7857f5bc''}'
- '{''domain'': ''stad_Datapoint''}'
- '{''domain'': ''coso_ContaminantMeasurement''}'
- '{''domain'': ''__Bd4c82b4e72756dd07838e3ed64fc01d3''}'
- '{''domain'': ''__Bc61095527952bb22dc6c72bcea5e2015''}'
- '{''domain'': ''__Bb3b966a83ead8099fc1d9350e1c85c2d''}'
- '{''domain'': ''sosa_Result''}'
range: Any
any_of:
- range: coso_ResultQualifier
- range: owl_Thing

```
</details>