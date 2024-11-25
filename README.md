# Graph Descriptions

This repository holds information about individual Theme 1 graphs based on the data provided for those graphs in FRINK's LakeFS repository. It is generated first by assembling a [LinkML schema](https://linkml.io/linkml/schemas/index.html), compiling information about the graph through iteration over its triples, and then using a modification of [this documentation generator](https://linkml.io/linkml/generators/markdown.html) to produce readable pages with class diagrams from that schema.

## Improving graph descriptions

If you wish to improve the descriptions of your graph's entity types and predicates, then you may introduce certain information (in the form of triples) to the data you submit to LakeFS. This information will then update any "TODO" placeholders you may encounter in the generated graph documentation.

All [CURIEs](https://www.w3.org/TR/curie/) below are defined through the URLs of the hyperlinks when those CURIEs are first introduced.

### IRI prefixes

We have observed the following IRI prefixes, and thus they will be appropriately substituted wherever they occur in the generated graph documentation:

<details>
<summary>Click here to view the list of prefixes, along with notes about some of them</summary>
| prefix | IRI | notes |
| --- | --- |  |
| sosa: | http://www.w3.org/ns/sosa/ |  |
| umls: | https://identifiers.org/umls: |  |
| niehs: | https://ice.ntp.niehs.nih.gov/property/ |  |
| semsci: | http://semanticscience.org/resource/SIO_ |  |
| dc: | http://purl.org/dc/elements/1.1/ |  |
| sockg: | http://www.semanticweb.org/zzy/ontologies/2024/0/soil-carbon-ontology/ | Should be substituted with a working IRI prefix. |
| dreamkg: | http://www.semanticweb.org/dreamkg/ijcai/ | Should be substituted with a working IRI prefix. |
| dct: | http://purl.org/dc/terms/ |  |
| xsd: | http://www.w3.org/2001/XMLSchema# |  |
| geo: | http://www.opengis.net/ont/geosparql# |  |
| cheminf: | http://purl.obolibrary.org/obo/CHEMINF_ |  |
| obo: | http://purl.obolibrary.org/obo/ |  |
| owl: | http://www.w3.org/2002/07/owl# |  |
| rdf: | http://www.w3.org/1999/02/22-rdf-syntax-ns# |  |
| scales: | http://schemas.scales-okn.org/rdf/scales# | Should be substituted with a working IRI prefix. |
| hsdo: | http://schema.org/ | This prefix should be substituted with schema: wherever it occurs. |
| schema: | https://schema.org/ |  |
| neo4j: | neo4j://graph.schema# | Not a real prefix; should be substituted wherever it occurs. |
| rural: | http://sail.ua.edu/ruralkg/ | Should be substituted with a working IRI prefix. |
| example: | http://example.org/ns# | Not a real prefix; should be substituted wherever it occurs. |
| securechain: | https://w3id.org/secure-chain/ |  |
| prov: | http://www.w3.org/ns/prov# |  |
| io: | https://spec.industrialontologies.org/ontology/core/Core/ |  |
| iosc: | https://spec.industrialontologies.org/ontology/supplychain/SupplyChain/ |  |
| sudokn: | http://asu.edu/semantics/SUDOKN/ | Should be substituted with a working IRI prefix. |
| sudokn2: | Utilities:communication/ | Not a real prefix; should be substituted wherever it occurs. |
| sudokn3: | Utilities:water/ | Not a real prefix; should be substituted wherever it occurs. |
| usfrsdata: | http://sawgraph.spatialai.org/v1/us-frs-data# | Should be substituted with a working IRI prefix. |
| usfrs: | http://sawgraph.spatialai.org/v1/us-frs# | Should be substituted with a working IRI prefix. |
| naics: | http://sawgraph.spatialai.org/v1/fio/naics# | Should be substituted with a working IRI prefix. |
| skos: | http://www.w3.org/2004/02/skos/core# |  |
| rdfs: | http://www.w3.org/2000/01/rdf-schema# |  |
| bao: | http://www.bioassayontology.org/bao#BAO_ |  |
| edam: | http://edamontology.org/ |  |
| qudt: | http://qudt.org/schema/qudt/ |  |
| ilisgs: | http://sawgraph.spatialai.org/v1/il-isgs# | Should be substituted with a working IRI prefix. |
| meegad: | http://sawgraph.spatialai.org/v1/me-egad# | Should be substituted with a working IRI prefix. |
| memgs: | http://sawgraph.spatialai.org/v1/me-mgs# | Should be substituted with a working IRI prefix. |
| ussdwis: | http://sawgraph.spatialai.org/v1/us-sdwis# | Should be substituted with a working IRI prefix. |
| pfas: | http://sawgraph.spatialai.org/v1/pfas# | Should be substituted with a working IRI prefix. |
| contaminoso: | http://sawgraph.spatialai.org/v1/contaminoso# | Should be substituted with a working IRI prefix. |
| relation: | http://relation.org/ | Not a real prefix; should be substituted wherever it occurs. |
| attribute: | http://attribute.org/ | Not a real prefix; should be substituted wherever it occurs. |
| phila: | https://metadata.phila.gov/ |  |
</details>

Please let [Mahir](mailto:mmorshed@scripps.edu) know if you introduce any new IRI prefixes not in the above list that should also be substituted.

### Ontology (owl:Ontology)

At the moment, since a single HDT file is assumed to represent a whole unit of data modeled in a particular way, it is also assumed that there is exactly one entity of type [owl:Ontology]( http://www.w3.org/2002/07/owl#Ontology) in your graph.

If we assume that the ontology entity has the CURIE "example:myOntology", then the following triples will have the following effects which it is hoped are understood from the examples given:

- example:myOntology [dct:title](http://purl.org/dc/terms/title) "Title of the ontology"
- example:myOntology [dct:description](http://purl.org/dc/terms/description) "Description of the ontology"
- example:myOntology [dct:hasVersion](http://purl.org/dc/terms/title) "0.0.1"
- example:myOntology [dct:created](http://purl.org/dc/terms/created) "2024-10-30T00:00:00Z"^^xsd:dateTime

Please let [Mahir](mailto:mmorshed@scripps.edu) know if the graph documentation generator should be aware of any other triples that characterize an ontology entity.

### Classes (owl:Class or rdfs:Class)

Each entity type in your graph should be an [rdfs:Class](http://www.w3.org/2000/01/rdf-schema#Class) or an [owl:Class](http://www.w3.org/2002/07/owl#Class). Thus either of the following triples must be present for an entity type with the CURIE "example:myClass"--it is not necessary to have both:

- example:myClass a rdfs:Class
- example:myClass a owl:Class

The following triples will have the following effects which it is hoped are understood from the examples given:

- example:myClass [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label) "ClassName"
- example:myClass [rdfs:comment](http://www.w3.org/2000/01/rdf-schema#comment) "Description of this class"
- example:myClass [rdfs:isDefinedBy](http://www.w3.org/2000/01/rdf-schema#isDefinedBy) <https://example.com/schema/that/defines/this/class.html>
- example:myClass [rdfs:subClassOf](http://www.w3.org/2000/01/rdf-schema#subClassOf) example:mySuperClass

Please let [Mahir](mailto:mmorshed@scripps.edu) know if the graph documentation generator should be aware of any other triples that characterize an entity type.

### Predicates

Each predicate in your graph should be at least one of a number of possible types--that is, a predicate "example:myPredicate" should have at least one of the following triples defined as appropriate:

- example:myPredicate a [rdf:Property](http://www.w3.org/1999/02/22-rdf-syntax-ns#Property)
- example:myPredicate a [rdfs:ContainerMembershipProperty](http://www.w3.org/2000/01/rdf-schema#ContainerMembershipProperty)
- example:myPredicate a [owl:DatatypeProperty](http://www.w3.org/2002/07/owl#DatatypeProperty)
- example:myPredicate a [owl:AnnotationProperty](http://www.w3.org/2002/07/owl#AnnotationProperty)
- example:myPredicate a [owl:ObjectProperty](http://www.w3.org/2002/07/owl#ObjectProperty)
- example:myPredicate a [owl:SymmetricProperty](http://www.w3.org/2002/07/owl#SymmetricProperty)
- example:myPredicate a [owl:TransitiveProperty](http://www.w3.org/2002/07/owl#TransitiveProperty)

The following triples will have the following effects which it is hoped are understood from the examples given:

- example:myPredicate [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label) "PredicateName"
- example:myPredicate [rdfs:comment](http://www.w3.org/2000/01/rdf-schema#comment) "Description of this class"
- example:myPredicate [skos:definition](http://www.w3.org/2004/02/skos/core#definition) "Description of this class"
- example:myPredicate [rdfs:domain](http://www.w3.org/2000/01/rdf-schema#domain) example:oneDomainType, example:anotherDomainTypeIfNeeded
- example:myPredicate [rdfs:range](http://www.w3.org/2000/01/rdf-schema#range) example:RangeType
- example:myPredicate [rdfs:subPropertyOf](http://www.w3.org/2000/01/rdf-schema#subPropertyOf) example:mySuperClass

Please let [Mahir](mailto:mmorshed@scripps.edu) know if the graph documentation generator should be aware of any other triples that characterize a predicate.

## Importing information from external ontologies

At the moment only auxiliary information from schema.org is introduced when a type or predicate from that ontology is encountered, so it is not strictly necessary to re-describe such a type/predicate if you use it in your own graph. Introducing such information from other external ontologies is planned to be supported soon.