

# Slot: label (rdfs_label)


_A human-readable name for the subject._






This slot occurs 70963 times.


URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsW3id.orgBiolinkVocabGene](../classes/HttpsW3id.orgBiolinkVocabGene.md) |  |  no  |
| [HttpsPurl.orgOknFrinkKgSpoke-genelabSchemaMethylationRegion](../classes/HttpsPurl.orgOknFrinkKgSpoke-genelabSchemaMethylationRegion.md) |  |  no  |
| [OwlDataRange](../classes/OwlDataRange.md) | The class of OWL data ranges, which are special kinds of datatypes |  no  |
| [HttpsPurl.orgOknFrinkKgSpoke-genelabSchemaMission](../classes/HttpsPurl.orgOknFrinkKgSpoke-genelabSchemaMission.md) |  |  no  |
| [RdfList](../classes/RdfList.md) | The class of RDF Lists |  no  |
| [HttpsPurl.orgOknFrinkKgSpoke-genelabSchemaMetaNode](../classes/HttpsPurl.orgOknFrinkKgSpoke-genelabSchemaMetaNode.md) |  |  no  |
| [OboOBI0000070](../classes/OboOBI0000070.md) |  |  no  |
| [HttpsW3id.orgBiolinkVocabStudy](../classes/HttpsW3id.orgBiolinkVocabStudy.md) |  |  no  |
| [RdfsDatatype](../classes/RdfsDatatype.md) | The class of RDF datatypes |  no  |







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
- https___purl.org_okn_frink_kg_spoke-genelab_schema_MetaNode
- https___purl.org_okn_frink_kg_spoke-genelab_schema_MethylationRegion
- https___purl.org_okn_frink_kg_spoke-genelab_schema_Mission
- https___w3id.org_biolink_vocab_Gene
- https___w3id.org_biolink_vocab_Study
- obo_OBI_0000070
range: Any
any_of:
- range: rdfs_Literal
- range: string

```
</details>