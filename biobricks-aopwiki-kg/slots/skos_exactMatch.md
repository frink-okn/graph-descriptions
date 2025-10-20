

# Slot: has exact match (skos_exactMatch)


_skos:exactMatch is used to link two concepts, indicating a high degree of confidence that the concepts can be used interchangeably across a wide range of information retrieval applications. skos:exactMatch is a transitive property, and is a sub-property of skos:closeMatch._






This slot occurs 13692 times.


URI: [skos:exactMatch](http://www.w3.org/2004/02/skos/core#exactMatch)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpSemanticscience.orgResourceCHEMINF000446](../classes/HttpSemanticscience.orgResourceCHEMINF000446.md) |  |  no  |
| [EdamData1025](../classes/EdamData1025.md) |  |  no  |
| [HttpSemanticscience.orgResourceCHEMINF000000](../classes/HttpSemanticscience.orgResourceCHEMINF000000.md) |  |  no  |
| [EdamData2298](../classes/EdamData2298.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)





## Comments

* description: skos:exactMatch is disjoint with each of the properties skos:broadMatch and skos:relatedMatch.



## LinkML Source

<details>

```yaml
name: skos_exactMatch
description: skos:exactMatch is used to link two concepts, indicating a high degree
  of confidence that the concepts can be used interchangeably across a wide range
  of information retrieval applications. skos:exactMatch is a transitive property,
  and is a sub-property of skos:closeMatch.
title: has exact match
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: skos:exactMatch is disjoint with each of the properties skos:broadMatch
  and skos:relatedMatch.'
from_schema: okns:skos
source: http://www.w3.org/2004/02/skos/core
slot_uri: skos:exactMatch
domain_of:
- edam_data_1025
- edam_data_2298
- http___semanticscience.org_resource_CHEMINF_000000
- http___semanticscience.org_resource_CHEMINF_000446
subproperty_of: skos_closeMatch
range: Any

```
</details>