

# Slot: comment (rdfs_comment)


_A description of the subject resource._






This slot occurs 141 times.


URI: [rdfs:comment](http://www.w3.org/2000/01/rdf-schema#comment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlDataRange](../classes/OwlDataRange.md) | The class of OWL data ranges, which are special kinds of datatypes |  no  |
| [RdfList](../classes/RdfList.md) | The class of RDF Lists |  no  |
| [HttpsPurl.orgOknFrinkKgSpoke-genelabSchemaMetaNode](../classes/HttpsPurl.orgOknFrinkKgSpoke-genelabSchemaMetaNode.md) |  |  no  |
| [HttpsW3id.orgBiolinkVocabStudy](../classes/HttpsW3id.orgBiolinkVocabStudy.md) |  |  no  |
| [RdfsDatatype](../classes/RdfsDatatype.md) | The class of RDF datatypes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: rdfs_comment
description: A description of the subject resource.
title: comment
from_schema: okns:owl-rdf-rdfs
source: http://www.w3.org/2000/01/rdf-schema#
domain: rdfs_Resource
slot_uri: rdfs:comment
domain_of:
- rdf_List
- rdfs_Datatype
- https___purl.org_okn_frink_kg_spoke-genelab_schema_MetaNode
- https___w3id.org_biolink_vocab_Study
range: Any
any_of:
- range: rdfs_Literal
- range: string

```
</details>