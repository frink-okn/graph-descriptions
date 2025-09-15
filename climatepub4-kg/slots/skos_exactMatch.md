

# Slot: has exact match (skos_exactMatch)


_skos:exactMatch is used to link two concepts, indicating a high degree of confidence that the concepts can be used interchangeably across a wide range of information retrieval applications. skos:exactMatch is a transitive property, and is a sub-property of skos:closeMatch._






This slot occurs 4018 times.


URI: [skos:exactMatch](http://www.w3.org/2004/02/skos/core#exactMatch)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdosLegalForceStatus](../classes/SdosLegalForceStatus.md) | A list of possible statuses for the legal force of a legislation |  no  |
| [SdosLegalValueLevel](../classes/SdosLegalValueLevel.md) | A list of possible levels for the legal validity of a legislation |  no  |
| [SdosIPTCDigitalSourceEnumeration](../classes/SdosIPTCDigitalSourceEnumeration.md) | <a href="https://www |  no  |







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
- sdos_IPTCDigitalSourceEnumeration
- sdos_LegalForceStatus
- sdos_LegalValueLevel
subproperty_of: skos_closeMatch
range: Any

```
</details>