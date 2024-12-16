# No schema name specified

No schema description specified



## Schema Diagram

```mermaid
erDiagram
Neo4jCompound {
    string neo4j_name  
    string neo4j_identifier  
    string neo4j_sources  
}
Neo4jDisease {
    string neo4j_name  
    string neo4j_identifier  
    string neo4j_source  
}
Neo4jEnvironment {
    string neo4j_name  
    string neo4j_identifier  
    string neo4j_sources  
}
Neo4jLocation {
    string neo4j_name  
    string neo4j_identifier  
    string neo4j_sources  
}
Neo4jOrganism {
    string neo4j_name  
    string neo4j_identifier  
    string neo4j_sources  
}
Neo4jSDoH {
    string neo4j_name  
    string neo4j_identifier  
    string neo4j_sources  
}

Neo4jCompound ||--|o Neo4jCompound : "neo4j_INTERACTS_CiC"
Neo4jCompound ||--|o Neo4jCompound : "neo4j_PARTOF_CpC"
Neo4jCompound ||--|o Neo4jCompound : "neo4j_ISA_CiC"
Neo4jCompound ||--|o Neo4jCompound : "neo4j_HASROLE_ChC"
Neo4jCompound ||--|o Neo4jDisease : "neo4j_CONTRAINDICATES_CcD"
Neo4jCompound ||--|o Neo4jDisease : "neo4j_TREATS_CtD"
Neo4jCompound ||--|o Neo4jLocation : "neo4j_FOUNDIN_CfL"
Neo4jDisease ||--|o Neo4jLocation : "neo4j_MORTALITY_DmL"
Neo4jDisease ||--|o Neo4jDisease : "neo4j_ISA_DiD"
Neo4jDisease ||--|o Neo4jDisease : "neo4j_RESEMBLES_DrD"
Neo4jDisease ||--|o Neo4jLocation : "neo4j_PREVALENCE_DpL"
Neo4jEnvironment ||--|o Neo4jEnvironment : "neo4j_ISA_EiE"
Neo4jEnvironment ||--|o Neo4jLocation : "neo4j_FOUNDIN_EfL"
Neo4jLocation ||--|o Neo4jLocation : "neo4j_PARTOF_LpL"
Neo4jOrganism ||--|o Neo4jCompound : "neo4j_RESPONDS_TO_OrC"
Neo4jOrganism ||--|o Neo4jLocation : "neo4j_ISOLATEDIN_OiL"
Neo4jSDoH ||--|o Neo4jDisease : "neo4j_ASSOCIATES_SaD"
Neo4jSDoH ||--|o Neo4jSDoH : "neo4j_ISA_SiS"
Neo4jSDoH ||--|o Neo4jLocation : "neo4j_PREVALENCEIN_SpL"

```


## IRI prefixes

* linkml: https://w3id.org/linkml/
* neo4j: neo4j://graph.schema#
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#



## Classes

| Class | Description |
| --- | --- |
| [Neo4jCompound](classes/Neo4jCompound.md) | No class (type) description specified<br/>Class with 798 occurrences.| 
| [Neo4jDisease](classes/Neo4jDisease.md) | No class (type) description specified<br/>Class with 180 occurrences.| 
| [Neo4jEnvironment](classes/Neo4jEnvironment.md) | No class (type) description specified<br/>Class with 2 occurrences.| 
| [Neo4jLocation](classes/Neo4jLocation.md) | No class (type) description specified<br/>Class with 106067 occurrences.| 
| [Neo4jOrganism](classes/Neo4jOrganism.md) | No class (type) description specified<br/>Class with 321442 occurrences.| 
| [Neo4jSDoH](classes/Neo4jSDoH.md) | No class (type) description specified<br/>Class with 1426 occurrences.| 





## Slots

| Slot | Description |
| --- | --- |
| [neo4j_ASSOCIATES_SaD](slots/neo4j_ASSOCIATES_SaD.md) | No slot (predicate) description specified<br/>39 occurrences with subject type neo4j_SDoH and object type neo4j_Disease.|
| [neo4j_CONTRAINDICATES_CcD](slots/neo4j_CONTRAINDICATES_CcD.md) | No slot (predicate) description specified<br/>51 occurrences with subject type neo4j_Compound and object type neo4j_Disease.|
| [neo4j_FOUNDIN_CfL](slots/neo4j_FOUNDIN_CfL.md) | No slot (predicate) description specified<br/>563803 occurrences with subject type neo4j_Compound and object type neo4j_Location.|
| [neo4j_FOUNDIN_EfL](slots/neo4j_FOUNDIN_EfL.md) | No slot (predicate) description specified<br/>11367 occurrences with subject type neo4j_Environment and object type neo4j_Location.|
| [neo4j_HASROLE_ChC](slots/neo4j_HASROLE_ChC.md) | No slot (predicate) description specified<br/>34 occurrences with subject type neo4j_Compound and object type neo4j_Compound.|
| [neo4j_identifier](slots/neo4j_identifier.md) | No slot (predicate) description specified<br/>2 occurrences with subject type neo4j_Environment and object type string.<br/>1426 occurrences with subject type neo4j_SDoH and object type string.<br/>106067 occurrences with subject type neo4j_Location and object type string.<br/>180 occurrences with subject type neo4j_Disease and object type string.<br/>798 occurrences with subject type neo4j_Compound and object type string.<br/>321442 occurrences with subject type neo4j_Organism and object type string.|
| [neo4j_INTERACTS_CiC](slots/neo4j_INTERACTS_CiC.md) | No slot (predicate) description specified<br/>1 occurrences with subject type neo4j_Compound and object type neo4j_Compound.|
| [neo4j_ISA_CiC](slots/neo4j_ISA_CiC.md) | No slot (predicate) description specified<br/>56 occurrences with subject type neo4j_Compound and object type neo4j_Compound.|
| [neo4j_ISA_DiD](slots/neo4j_ISA_DiD.md) | No slot (predicate) description specified<br/>41 occurrences with subject type neo4j_Disease and object type neo4j_Disease.|
| [neo4j_ISA_EiE](slots/neo4j_ISA_EiE.md) | No slot (predicate) description specified<br/>1 occurrences with subject type neo4j_Environment and object type neo4j_Environment.|
| [neo4j_ISA_SiS](slots/neo4j_ISA_SiS.md) | No slot (predicate) description specified<br/>999 occurrences with subject type neo4j_SDoH and object type neo4j_SDoH.|
| [neo4j_ISOLATEDIN_OiL](slots/neo4j_ISOLATEDIN_OiL.md) | No slot (predicate) description specified<br/>321442 occurrences with subject type neo4j_Organism and object type neo4j_Location.|
| [neo4j_MORTALITY_DmL](slots/neo4j_MORTALITY_DmL.md) | No slot (predicate) description specified<br/>10802 occurrences with subject type neo4j_Disease and object type neo4j_Location.|
| [neo4j_name](slots/neo4j_name.md) | No slot (predicate) description specified<br/>2 occurrences with subject type neo4j_Environment and object type string.<br/>1426 occurrences with subject type neo4j_SDoH and object type string.<br/>106067 occurrences with subject type neo4j_Location and object type string.<br/>180 occurrences with subject type neo4j_Disease and object type string.<br/>798 occurrences with subject type neo4j_Compound and object type string.<br/>321442 occurrences with subject type neo4j_Organism and object type string.|
| [neo4j_PARTOF_CpC](slots/neo4j_PARTOF_CpC.md) | No slot (predicate) description specified<br/>18 occurrences with subject type neo4j_Compound and object type neo4j_Compound.|
| [neo4j_PARTOF_LpL](slots/neo4j_PARTOF_LpL.md) | No slot (predicate) description specified<br/>119810 occurrences with subject type neo4j_Location and object type neo4j_Location.|
| [neo4j_PREVALENCE_DpL](slots/neo4j_PREVALENCE_DpL.md) | No slot (predicate) description specified<br/>275085 occurrences with subject type neo4j_Disease and object type neo4j_Location.|
| [neo4j_PREVALENCEIN_SpL](slots/neo4j_PREVALENCEIN_SpL.md) | No slot (predicate) description specified<br/>2999117 occurrences with subject type neo4j_SDoH and object type neo4j_Location.|
| [neo4j_RESEMBLES_DrD](slots/neo4j_RESEMBLES_DrD.md) | No slot (predicate) description specified<br/>67 occurrences with subject type neo4j_Disease and object type neo4j_Disease.|
| [neo4j_RESPONDS_TO_OrC](slots/neo4j_RESPONDS_TO_OrC.md) | No slot (predicate) description specified<br/>5138 occurrences with subject type neo4j_Organism and object type neo4j_Compound.|
| [neo4j_source](slots/neo4j_source.md) | No slot (predicate) description specified<br/>180 occurrences with subject type neo4j_Disease and object type string.|
| [neo4j_sources](slots/neo4j_sources.md) | No slot (predicate) description specified<br/>2 occurrences with subject type neo4j_Environment and object type string.<br/>1426 occurrences with subject type neo4j_SDoH and object type string.<br/>106067 occurrences with subject type neo4j_Location and object type string.<br/>3336 occurrences with subject type neo4j_Compound and object type string.<br/>321442 occurrences with subject type neo4j_Organism and object type string.|
| [neo4j_TREATS_CtD](slots/neo4j_TREATS_CtD.md) | No slot (predicate) description specified<br/>163 occurrences with subject type neo4j_Compound and object type neo4j_Disease.|







