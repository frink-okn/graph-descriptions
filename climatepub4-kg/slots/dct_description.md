

# Slot: Description (dct_description)


_Description may include but is not limited to: an abstract, a table of contents, a graphical representation, or a free-text account of the resource._






This slot occurs 13188 times.


URI: [dct:description](http://purl.org/dc/terms/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [VaemGraphRole](../classes/VaemGraphRole.md) | GraphRole is used to characterize how a graph of resources participates in an... |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)





## Comments

* description: An account of the resource.



## LinkML Source

<details>

```yaml
name: dct_description
description: 'Description may include but is not limited to: an abstract, a table
  of contents, a graphical representation, or a free-text account of the resource.'
title: Description
comments:
- 'description: An account of the resource.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:description
domain_of:
- vaem_GraphRole
subproperty_of: dc_description
range: string

```
</details>