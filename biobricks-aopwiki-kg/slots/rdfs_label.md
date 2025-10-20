

# Slot: label (rdfs_label)


_A human-readable name for the subject._






This slot occurs 4705 times.


URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571](../classes/HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571.md) |  |  no  |
| [HttpAopkb.orgAopOntology#KeyEventRelationship](../classes/HttpAopkb.orgAopOntology#KeyEventRelationship.md) |  |  no  |
| [RdfsDatatype](../classes/RdfsDatatype.md) | The class of RDF datatypes |  no  |
| [DctAgentClass](../classes/DctAgentClass.md) | A group of agents |  no  |
| [DcamVocabularyEncodingScheme](../classes/DcamVocabularyEncodingScheme.md) | An enumerated set of resources |  no  |
| [HttpAopkb.orgAopOntology#AdverseOutcomePathway](../classes/HttpAopkb.orgAopOntology#AdverseOutcomePathway.md) |  |  no  |
| [OwlDataRange](../classes/OwlDataRange.md) | The class of OWL data ranges, which are special kinds of datatypes |  no  |
| [RdfList](../classes/RdfList.md) | The class of RDF Lists |  no  |
| [HttpAopkb.orgAopOntology#KeyEvent](../classes/HttpAopkb.orgAopOntology#KeyEvent.md) |  |  no  |







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
- dcam_VocabularyEncodingScheme
- dct_AgentClass
- rdf_List
- rdfs_Datatype
- http___aopkb.org_aop_ontology#AdverseOutcomePathway
- http___aopkb.org_aop_ontology#KeyEvent
- http___aopkb.org_aop_ontology#KeyEventRelationship
- http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
range: Any
any_of:
- range: rdfs_Literal
- range: string

```
</details>