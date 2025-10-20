

# Slot: http___id.nlm.nih.gov_mesh_vocab#hasDescriptor




This slot occurs 674909 times.


URI: [http://id.nlm.nih.gov/mesh/vocab#hasDescriptor](http://id.nlm.nih.gov/mesh/vocab#hasDescriptor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md)







## LinkML Source

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#hasDescriptor
from_schema: okns:biobricks-mesh-kg
rank: 1000
slot_uri: http://id.nlm.nih.gov/mesh/vocab#hasDescriptor
alias: http___id.nlm.nih.gov_mesh_vocab#hasDescriptor
domain_of:
- http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
- http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
range: Any
any_of:
- range: http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
- range: http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor

```
</details>