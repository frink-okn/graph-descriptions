

# Slot: rdfs_isDefinedBy


_No slot (predicate) description specified_






This slot occurs 6 times.


URI: [rdfs:isDefinedBy](http://www.w3.org/2000/01/rdf-schema#isDefinedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtAspectClass](../classes/QudtAspectClass.md) | No class (type) description specified |  yes  |
| [Vaem#CatalogEntry](../classes/Vaem#CatalogEntry.md) | No class (type) description specified |  yes  |
| [QudtIntegerEncodingType](../classes/QudtIntegerEncodingType.md) | The encoding scheme for integer types |  yes  |
| [QudtCharEncodingType](../classes/QudtCharEncodingType.md) | The class of all character encoding schemes, each of which defines a rule or ... |  yes  |
| [QudtByteEncodingType](../classes/QudtByteEncodingType.md) | This class contains the various ways that information may be encoded into byt... |  yes  |
| [QudtOrderedType](../classes/QudtOrderedType.md) | Describes how a data or information structure is ordered |  yes  |
| [QudtFloatingPointEncodingType](../classes/QudtFloatingPointEncodingType.md) | A "Encoding" with the following instance(s): "Double Precision Encoding", "Si... |  yes  |
| [Vaem#GraphMetaData](../classes/Vaem#GraphMetaData.md) | No class (type) description specified |  yes  |
| [QudtEndianType](../classes/QudtEndianType.md) | No class (type) description specified |  yes  |
| [QudtSignednessType](../classes/QudtSignednessType.md) | No class (type) description specified |  yes  |
| [OwlOntologyProperty](../classes/OwlOntologyProperty.md) | The class of ontology properties |  yes  |
| [QudtBitEncodingType](../classes/QudtBitEncodingType.md) | A bit encoding is a correspondence between the two possible values of a bit, ... |  yes  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  yes  |
| [QudtBooleanEncodingType](../classes/QudtBooleanEncodingType.md) | No class (type) description specified |  yes  |
| [Vaem#Party](../classes/Vaem#Party.md) | No class (type) description specified |  yes  |
| [QudtCardinalityType](../classes/QudtCardinalityType.md) | ␊  In mathematics, the cardinality of a set is a measure of the number of ele... |  yes  |
| [QudtDateTimeStringEncodingType](../classes/QudtDateTimeStringEncodingType.md) | Date Time encodings are logical encodings for expressing date/time quantities... |  yes  |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlOntology](../classes/OwlOntology.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| qudt_Unit | uri | http://qudt.org/vocab/unit/MicroGM-PER-KiloGM | http://qudt.org/vocab/unit | 4 |
| qudt_Unit | owl_Ontology | http://qudt.org/vocab/unit/NanoGM-PER-L | http://qudt.org/2.1/vocab/unit | 2 |




## LinkML Source

<details>

```yaml
name: rdfs_isDefinedBy
annotations:
  count:
    tag: count
    value: 6
description: No slot (predicate) description specified
examples:
- object:
    example_object: http://qudt.org/vocab/unit
    example_object_type: uri
    example_predicate: rdfs:isDefinedBy
    example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
    example_subject_type: qudt_Unit
- object:
    example_object: http://qudt.org/2.1/vocab/unit
    example_object_type: owl_Ontology
    example_predicate: rdfs:isDefinedBy
    example_subject: http://qudt.org/vocab/unit/NanoGM-PER-L
    example_subject_type: qudt_Unit
from_schema: sawgraph-kg
rank: 1000
slot_uri: rdfs:isDefinedBy
alias: rdfs_isDefinedBy
domain_of:
- owl_OntologyProperty
- qudt_AspectClass
- qudt_BitEncodingType
- qudt_BooleanEncodingType
- qudt_ByteEncodingType
- qudt_CardinalityType
- qudt_CharEncodingType
- qudt_DateTimeStringEncodingType
- qudt_EndianType
- qudt_FloatingPointEncodingType
- qudt_IntegerEncodingType
- qudt_OrderedType
- qudt_SignednessType
- qudt_Unit
- vaem_#CatalogEntry
- vaem_#GraphMetaData
- vaem_#Party
range: Any
any_of:
- range: owl_Ontology
- range: uri

```
</details>