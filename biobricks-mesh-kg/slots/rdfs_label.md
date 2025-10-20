

# Slot: label (rdfs_label)


_A human-readable name for the subject._






This slot occurs 1565840 times.


URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlDataRange](../classes/OwlDataRange.md) | The class of OWL data ranges, which are special kinds of datatypes |  no  |
| [HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#TreeNumber](../classes/HttpId.nlm.nih.govMeshVocab#TreeNumber.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCRPopulation](../classes/HttpId.nlm.nih.govMeshVocab#SCRPopulation.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCRProtocol](../classes/HttpId.nlm.nih.govMeshVocab#SCRProtocol.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md) |  |  no  |
| [RdfsDatatype](../classes/RdfsDatatype.md) | The class of RDF datatypes |  no  |
| [RdfList](../classes/RdfList.md) | The class of RDF Lists |  no  |
| [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCRDisease](../classes/HttpId.nlm.nih.govMeshVocab#SCRDisease.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCROrganism](../classes/HttpId.nlm.nih.govMeshVocab#SCROrganism.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#PublicationType](../classes/HttpId.nlm.nih.govMeshVocab#PublicationType.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#CheckTag](../classes/HttpId.nlm.nih.govMeshVocab#CheckTag.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#SCRChemical](../classes/HttpId.nlm.nih.govMeshVocab#SCRChemical.md) |  |  no  |
| [HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: rdfs_label
description: A human-readable name for the subject.
title: label
from_schema: okns:owl-rdf-rdfs
source: http://www.w3.org/2000/01/rdf-schema#
domain: rdfs_Resource
slot_uri: rdfs:label
domain_of:
- rdf_List
- rdfs_Datatype
- http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
- http___id.nlm.nih.gov_mesh_vocab#CheckTag
- http___id.nlm.nih.gov_mesh_vocab#Concept
- http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
- http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
- http___id.nlm.nih.gov_mesh_vocab#PublicationType
- http___id.nlm.nih.gov_mesh_vocab#Qualifier
- http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
- http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
- http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
- http___id.nlm.nih.gov_mesh_vocab#SCR_Population
- http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
- http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
- http___id.nlm.nih.gov_mesh_vocab#TreeNumber
range: Any
any_of:
- range: rdfs_Literal
- range: string

```
</details>