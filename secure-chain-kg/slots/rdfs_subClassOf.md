

# Slot: rdfs_subClassOf


_TODO -- tell the world what this slot (predicate) describes._





URI: [rdfs:subClassOf](http://www.w3.org/2000/01/rdf-schema#subClassOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfsClass](../classes/RdfsClass.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfsClass](../classes/RdfsClass.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| securechain:SoftwareVersion rdfs:subClassOf securechain:Software |
| securechain:Hardware rdfs:subClassOf sdoh:Product |

## Comments

* 2 occurrences with subject type rdfs_Class and object type rdfs_Class.
* 5 occurrences with subject type rdfs_Class and object type uri.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg/develop




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rdfs:subClassOf |
| native | secure-chain-kg/develop/:rdfs_subClassOf |




## LinkML Source

<details>
```yaml
name: rdfs_subClassOf
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 2 occurrences with subject type rdfs_Class and object type rdfs_Class.
- 5 occurrences with subject type rdfs_Class and object type uri.
examples:
- value: securechain:SoftwareVersion rdfs:subClassOf securechain:Software
- value: securechain:Hardware rdfs:subClassOf sdoh:Product
from_schema: secure-chain-kg/develop
rank: 1000
slot_uri: rdfs:subClassOf
alias: rdfs_subClassOf
domain_of:
- rdfs_Class
range: Any
any_of:
- range: rdfs_Class
- range: uri

```
</details>