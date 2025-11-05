

# Slot: http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo




This slot occurs 426098 times.


URI: [http://id.nlm.nih.gov/mesh/vocab#preferredMappedTo](http://id.nlm.nih.gov/mesh/vocab#preferredMappedTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpId.nlm.nih.govMeshVocab#SCRProtocol](../classes/HttpId.nlm.nih.govMeshVocab#SCRProtocol.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCRPopulation](../classes/HttpId.nlm.nih.govMeshVocab#SCRPopulation.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCRDisease](../classes/HttpId.nlm.nih.govMeshVocab#SCRDisease.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCROrganism](../classes/HttpId.nlm.nih.govMeshVocab#SCROrganism.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCRChemical](../classes/HttpId.nlm.nih.govMeshVocab#SCRChemical.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md)







## LinkML Source

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo
from_schema: okns:biobricks-mesh-kg
rank: 1000
slot_uri: http://id.nlm.nih.gov/mesh/vocab#preferredMappedTo
alias: http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo
domain_of:
- http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
- http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
- http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
- http___id.nlm.nih.gov_mesh_vocab#SCR_Population
- http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
range: Any
any_of:
- range: http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
- range: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
- range: http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor

```
</details>