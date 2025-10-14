

# Slot: paper_id (neo4j_paper_id)




This slot occurs 204 times.


URI: [neo4j:paper_id](neo4j://graph.schema#paper_id)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Field](../classes/HttpsClimatepub4kg.github.ioOntology#Field.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Innovation](../classes/HttpsClimatepub4kg.github.ioOntology#Innovation.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Method](../classes/HttpsClimatepub4kg.github.ioOntology#Method.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Task](../classes/HttpsClimatepub4kg.github.ioOntology#Task.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Problem](../classes/HttpsClimatepub4kg.github.ioOntology#Problem.md) |  |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: neo4j_paper_id
title: paper_id
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: neo4j:paper_id
alias: neo4j_paper_id
domain_of:
- https___climatepub4kg.github.io_ontology#Field
- https___climatepub4kg.github.io_ontology#Innovation
- https___climatepub4kg.github.io_ontology#Method
- https___climatepub4kg.github.io_ontology#Model
- https___climatepub4kg.github.io_ontology#Problem
- https___climatepub4kg.github.io_ontology#Task
union_of:
- neo4j_Innovation
- neo4j_Model
- neo4j_Field
- neo4j_Task
- neo4j_Problem
- neo4j_Method
range: string

```
</details>