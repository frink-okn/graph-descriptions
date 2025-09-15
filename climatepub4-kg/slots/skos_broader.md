

# Slot: has broader (skos_broader)


_Relates a concept to a concept that is more general in meaning._






This slot occurs 46537 times.


URI: [skos:broader](http://www.w3.org/2004/02/skos/core#broader)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)





## Comments

* description: Broader concepts are typically rendered as parents in a concept hierarchy (tree).



## LinkML Source

<details>

```yaml
name: skos_broader
description: Relates a concept to a concept that is more general in meaning.
title: has broader
notes:
- By convention, skos:broader is only used to assert an immediate (i.e. direct) hierarchical
  link between two conceptual resources.
- No occurrences of this slot in the graph.
comments:
- 'description: Broader concepts are typically rendered as parents in a concept hierarchy
  (tree).'
from_schema: okns:skos
source: http://www.w3.org/2004/02/skos/core
slot_uri: skos:broader
subproperty_of: skos_broaderTransitive
inverse: skos_narrower
range: Any

```
</details>