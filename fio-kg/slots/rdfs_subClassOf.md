

# Slot: subClassOf (rdfs_subClassOf)


_The subject is a subclass of a class._






This slot occurs 30 times.


URI: [rdfs:subClassOf](http://www.w3.org/2000/01/rdf-schema#subClassOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdosMedicalSpecialty](../classes/SdosMedicalSpecialty.md) | Any specific branch of medical science or practice |  no  |
| [QudtAspectClass](../classes/QudtAspectClass.md) |  |  no  |
| [RdfsDatatype](../classes/RdfsDatatype.md) | The class of RDF datatypes |  no  |
| [OwlDataRange](../classes/OwlDataRange.md) | The class of OWL data ranges, which are special kinds of datatypes |  no  |







## Properties

* Range: [RdfsClass](../classes/RdfsClass.md)







## LinkML Source

<details>

```yaml
name: rdfs_subClassOf
description: The subject is a subclass of a class.
title: subClassOf
from_schema: okns:owl-rdf-rdfs
source: http://www.w3.org/2000/01/rdf-schema#
domain: rdfs_Class
slot_uri: rdfs:subClassOf
domain_of:
- sdos_MedicalSpecialty
- rdfs_Datatype
- qudt_AspectClass
range: rdfs_Class

```
</details>