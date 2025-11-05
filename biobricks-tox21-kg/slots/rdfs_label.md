

# Slot: label (rdfs_label)


_A human-readable name for the subject._






This slot occurs 9045 times.


URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [DctAgentClass](../classes/DctAgentClass.md) | A group of agents |  no  |
| [DcamVocabularyEncodingScheme](../classes/DcamVocabularyEncodingScheme.md) | An enumerated set of resources |  no  |
| [OboCHEMINF000446](../classes/OboCHEMINF000446.md) |  |  no  |
| [RdfList](../classes/RdfList.md) | The class of RDF Lists |  no  |
| [RdfsDatatype](../classes/RdfsDatatype.md) | The class of RDF datatypes |  no  |
| [OwlDataRange](../classes/OwlDataRange.md) | The class of OWL data ranges, which are special kinds of datatypes |  no  |







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
- obo_CHEMINF_000446
range: Any
any_of:
- range: rdfs_Literal
- range: string

```
</details>