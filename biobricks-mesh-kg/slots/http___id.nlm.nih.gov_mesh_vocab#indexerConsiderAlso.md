

# Slot: http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso




This slot occurs 47181 times.


URI: [http://id.nlm.nih.gov/mesh/vocab#indexerConsiderAlso](http://id.nlm.nih.gov/mesh/vocab#indexerConsiderAlso)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpId.nlm.nih.govMeshVocab#SCRDisease](../classes/HttpId.nlm.nih.govMeshVocab#SCRDisease.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCROrganism](../classes/HttpId.nlm.nih.govMeshVocab#SCROrganism.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCRChemical](../classes/HttpId.nlm.nih.govMeshVocab#SCRChemical.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCRProtocol](../classes/HttpId.nlm.nih.govMeshVocab#SCRProtocol.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md)







## LinkML Source

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso
from_schema: okns:biobricks-mesh-kg
rank: 1000
slot_uri: http://id.nlm.nih.gov/mesh/vocab#indexerConsiderAlso
alias: http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso
domain_of:
- http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
- http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
- http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
- http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
range: Any
any_of:
- range: http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
- range: uri
- range: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
- range: http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor

```
</details>