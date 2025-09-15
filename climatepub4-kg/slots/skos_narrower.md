

# Slot: has narrower (skos_narrower)


_Relates a concept to a concept that is more specific in meaning._






This slot occurs 46537 times.


URI: [skos:narrower](http://www.w3.org/2004/02/skos/core#narrower)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)





## Comments

* description: Narrower concepts are typically rendered as children in a concept hierarchy (tree).



## LinkML Source

<details>

```yaml
name: skos_narrower
description: Relates a concept to a concept that is more specific in meaning.
title: has narrower
notes:
- By convention, skos:broader is only used to assert an immediate (i.e. direct) hierarchical
  link between two conceptual resources.
- No occurrences of this slot in the graph.
comments:
- 'description: Narrower concepts are typically rendered as children in a concept
  hierarchy (tree).'
from_schema: okns:skos
source: http://www.w3.org/2004/02/skos/core
slot_uri: skos:narrower
subproperty_of: skos_narrowerTransitive
inverse: skos_broader
range: Any

```
</details>