

# Slot: label (rdfs_label)


_A human-readable name for the subject._






This slot occurs 4314237 times.


URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsW3id.orgBiolinkVocabChemicalEntity](../classes/HttpsW3id.orgBiolinkVocabChemicalEntity.md) |  |  no  |
| [OwlDataRange](../classes/OwlDataRange.md) | The class of OWL data ranges, which are special kinds of datatypes |  no  |
| [Bao0000179](../classes/Bao0000179.md) |  |  no  |
| [RdfList](../classes/RdfList.md) | The class of RDF Lists |  no  |
| [RdfsDatatype](../classes/RdfsDatatype.md) | The class of RDF datatypes |  no  |
| [OboCHEMINF000568](../classes/OboCHEMINF000568.md) |  |  no  |
| [DctAgentClass](../classes/DctAgentClass.md) | A group of agents |  no  |
| [OboCHEMINF000000](../classes/OboCHEMINF000000.md) |  |  no  |
| [OboCHEMINF000446](../classes/OboCHEMINF000446.md) |  |  no  |
| [Bao0000015](../classes/Bao0000015.md) |  |  no  |
| [DcamVocabularyEncodingScheme](../classes/DcamVocabularyEncodingScheme.md) | An enumerated set of resources |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)







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
- dcam_VocabularyEncodingScheme
- dct_AgentClass
- bao_0000015
- bao_0000179
- https___w3id.org_biolink_vocab_ChemicalEntity
- obo_CHEMINF_000000
- obo_CHEMINF_000446
- obo_CHEMINF_000568
range: Any
any_of:
- range: rdfs_Literal
- range: string

```
</details>