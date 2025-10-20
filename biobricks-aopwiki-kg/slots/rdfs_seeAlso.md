

# Slot: seeAlso (rdfs_seeAlso)


_Further information about the subject resource._






This slot occurs 4548 times.


URI: [rdfs:seeAlso](http://www.w3.org/2000/01/rdf-schema#seeAlso)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [EdamData2291](../classes/EdamData2291.md) |  |  no  |
| [RdfsDatatype](../classes/RdfsDatatype.md) | The class of RDF datatypes |  no  |
| [HttpAopkb.orgAopOntology#KeyEventRelationship](../classes/HttpAopkb.orgAopOntology#KeyEventRelationship.md) |  |  no  |
| [DcamVocabularyEncodingScheme](../classes/DcamVocabularyEncodingScheme.md) | An enumerated set of resources |  no  |
| [HttpAopkb.orgAopOntology#AdverseOutcomePathway](../classes/HttpAopkb.orgAopOntology#AdverseOutcomePathway.md) |  |  no  |
| [EdamData1025](../classes/EdamData1025.md) |  |  no  |
| [OwlDataRange](../classes/OwlDataRange.md) | The class of OWL data ranges, which are special kinds of datatypes |  no  |
| [HttpAopkb.orgAopOntology#KeyEvent](../classes/HttpAopkb.orgAopOntology#KeyEvent.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)







## LinkML Source

<details>

```yaml
name: rdfs_seeAlso
description: Further information about the subject resource.
title: seeAlso
from_schema: okns:owl-rdf-rdfs
source: http://www.w3.org/2000/01/rdf-schema#
domain: rdfs_Resource
slot_uri: rdfs:seeAlso
domain_of:
- dcam_VocabularyEncodingScheme
- rdfs_Datatype
- edam_data_1025
- edam_data_2291
- http___aopkb.org_aop_ontology#AdverseOutcomePathway
- http___aopkb.org_aop_ontology#KeyEvent
- http___aopkb.org_aop_ontology#KeyEventRelationship
range: Any
any_of:
- range: rdfs_Resource
- range: uri

```
</details>