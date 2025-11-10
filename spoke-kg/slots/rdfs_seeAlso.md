

# Slot: seeAlso (rdfs_seeAlso)


_Further information about the subject resource._






This slot occurs 42904 times.


URI: [rdfs:seeAlso](http://www.w3.org/2000/01/rdf-schema#seeAlso)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlDataRange](../classes/OwlDataRange.md) | The class of OWL data ranges, which are special kinds of datatypes |  no  |
| [RdfsDatatype](../classes/RdfsDatatype.md) | The class of RDF datatypes |  no  |
| [HttpsW3id.orgBiolinkVocabDisease](../classes/HttpsW3id.orgBiolinkVocabDisease.md) |  |  no  |
| [DcamVocabularyEncodingScheme](../classes/DcamVocabularyEncodingScheme.md) | An enumerated set of resources |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)







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
- rdfs_Datatype
- dcam_VocabularyEncodingScheme
- https___w3id.org_biolink_vocab_Disease
range: Any
any_of:
- range: rdfs_Resource
- range: uri

```
</details>