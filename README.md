# Graph Descriptions

This repository holds information about individual Theme 1 graphs based on the data provided for those graphs in FRINK's LakeFS repository.

It is generated first by assembling a [LinkML schema](https://linkml.io/linkml/schemas/index.html), compiling information about the graph through iteration over its triples, and then using a modification of [this documentation generator](https://linkml.io/linkml/generators/markdown.html) to produce readable pages with class diagrams from that schema.

## Improving graph descriptions

If you wish to improve the descriptions of your graph's entity types and predicates, then you may introduce certain information (in the form of triples) to the data you submit to LakeFS. This information will then update any indicators of absent informatoin that you may encounter in the generated graph documentation.

All [CURIEs](https://www.w3.org/TR/curie/) below are defined through the URLs of the hyperlinks when those CURIEs are first introduced.

### IRI prefixes

We have observed the following IRI prefixes, and thus they will be appropriately substituted wherever they occur in the generated graph documentation:

<details>
<summary>Click here to view the list of prefixes, along with notes about some of them</summary>

| prefix | IRI | notes |
| --- | --- | --- |
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

### Documentation triples for any object

For any class or predicate that your graph uses, you can add any of the following triples to it and they will be reflected in the documentation appropriately. All of the following example triples document an entity with the CURIE "example:myClass", and it is hoped that the example object values will help indicate what the triples are intended for.

In the following table, only one triple of each type will be reflected in the documentation. For example, if multiple "skos:definition" triples are defined for an object, only one of those "skos:definition" triples for that object will have its information shown.

| Subject | Predicate | Object | Notes |
| --- | --- | --- | --- |
| example:myClass | [dct:description](http://purl.org/dc/terms/description) | "Description of the class" | :white_check_mark: Required (either this or skos:definition) |
| example:myClass | [skos:definition](http://www.w3.org/2004/02/skos/core#definition) | "Description of the class" | :white_check_mark: Required (either this or dct:description) |
| example:myClass | [dct:title](http://purl.org/dc/terms/title) | "Title of the class" | :white_check_mark: Required (either this or rdfs:label) |
| example:myClass | [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label) | "Title of the class" | :white_check_mark: Required (either this or dct:title) |
| example:myClass | [owl:deprecated](http://www.w3.org/2002/07/owl#deprecated) | "This element has been deprecated since ... because ..." | |
| example:myClass | [rdfs:isDefinedBy](http://www.w3.org/2000/01/rdf-schema#isDefinedBy) | https://path.to/where/this/class/is/defined | Object must be a URI. |
| example:myClass | [dct:language](http://purl.org/dc/terms/language) | "English" | |
| example:myClass | [dct:isReplacedBy](http://purl.org/dc/terms/isReplacedBy) | https://path.to/the/class/which/replaces/myClass/if/myClass/is/deprecated | Object must be a URI. |
| example:myClass | [dct:creator](http://purl.org/dc/terms/creator) | http://github.com/frink-okn | Object must be a URI. |
| example:myClass | [dct:created](http://purl.org/dc/terms/created) | "2024-10-30T00:00:00Z"^^xsd:dateTime | |
| example:myClass | [dct:modified](http://purl.org/dc/terms/modified) | "2024-11-30T00:00:00Z"^^xsd:dateTime | |

In the following table, multiple triples of each type will be reflected in the documentation. For example, if multiple "dct:contributor" triples are defined for an object, all of them will have their information shown.

| Subject | Predicate | Object | Notes |
| --- | --- | --- | --- |
| example:myClass | [prov:todo](http://www.w3.org/ns/prov#todo) | "This class has this issue..." | |
| example:myClass | [skos:note](http://www.w3.org/2004/02/skos/core#note) | "Here's a general note about this class..." | [^1] |
| example:myClass | [skos:changeNote](http://www.w3.org/2004/02/skos/core#changeNote) | "Here's a note describing a change to this class..." | [^1] |
| example:myClass | [skos:editorialNote](http://www.w3.org/2004/02/skos/core#editorialNote) | "Here's an editorial note about this class..." | [^1] |
| example:myClass | [skos:historyNote](http://www.w3.org/2004/02/skos/core#historyNote) | "Here's a note about the history of this class..." | [^1] |
| example:myClass | [skos:scopeNote](http://www.w3.org/2004/02/skos/core#scopeNote) | "Here's a note about the scope of this class..." | [^1] |
| example:myClass | [rdfs:comment](http://www.w3.org/2000/01/rdf-schema#comment) | "Here's a comment about this class..." | [^1] |
| example:myClass | [rdfs:seeAlso](http://www.w3.org/2000/01/rdf-schema#seeAlso) | https://path.to/another/relevant/uri/of/some/kind |  |
| example:myClass | [skos:altLabel](http://www.w3.org/2004/02/skos/core#altLabel) | "Alternate name for this class" |  |
| example:myClass | [skos:mappingRelation](http://www.w3.org/2004/02/skos/core#altLabel) | https://path.to/uri/that/maps/to/myClass | Object must be a URI. |
| example:myClass | [skos:exactMatch](http://www.w3.org/2004/02/skos/core#exactMatch) | https://path.to/uri/that/exactly/matches/myClass | Object must be a URI. |
| example:myClass | [skos:closeMatch](http://www.w3.org/2004/02/skos/core#closeMatch) | https://path.to/uri/that/is/a/close/match/to/myClass | Object must be a URI. |
| example:myClass | [skos:relatedMatch](http://www.w3.org/2004/02/skos/core#relatedMatch) | https://path.to/uri/that/is/related/to/myClass | Object must be a URI. |
| example:myClass | [skos:narrowMatch](http://www.w3.org/2004/02/skos/core#narrowMatch) | https://path.to/uri/that/narrowly/matches/myClass | Object must be a URI. |
| example:myClass | [skos:broadMatch](http://www.w3.org/2004/02/skos/core#broadMatch) | https://path.to/uri/that/broadly/matches/myClass | Object must be a URI. |
| example:myClass | [dct:contributor](http://purl.org/dc/terms/contributor) | http://github.com/nsf-open | Object must be a URI. |
| example:myClass | [dct:contributor](http://purl.org/dc/terms/contributor) | http://github.com/nsf-open | Object must be a URI. |
| example:myClass | [dcat:theme](https://www.w3.org/ns/dcat#theme) | https://path.to/category/in/some/scheme | Object must be a URI. |
| example:myClass | [dcat:keyword](https://www.w3.org/ns/dcat#keyword) | "exemplary class" | |
| example:myClass | [schema:keywords](https://schema.org/keywords) | "exemplary class" | |

[^1]: LinkML specifies that notes be intended either for internal consumption (e.g. for other ontology developers) or for external consumption (e.g. for end-users of the ontology). At the moment all skos: note triples are treated as internal notes while rdfs:comment triples are treated as external notes; let [Mahir](mailto:mmorshed@scripps.edu) know if you think they should be treated in some other way.

### Ontology (owl:Ontology)

At the moment, since a single HDT file is assumed to represent a whole unit of data modeled in a particular way, it is also assumed that there is exactly one entity of type [owl:Ontology]( http://www.w3.org/2002/07/owl#Ontology) in your graph. Let us assume that the ontology entity has the CURIE "example:myOntology".

In addition to the triples described in the section "Documentation triples for any object" above, the following triples will have the following effects which it is hoped are understood from the examples given:

| Subject | Predicate | Object | Notes |
| --- | --- | --- | --- |
| example:myOntology | [dct:hasVersion](http://purl.org/dc/terms/title) | "0.0.1" | |

Please let [Mahir](mailto:mmorshed@scripps.edu) know if the graph documentation generator should be aware of any other triples that characterize an ontology entity.

### Classes (owl:Class or rdfs:Class)

Each entity type in your graph should be an [rdfs:Class](http://www.w3.org/2000/01/rdf-schema#Class) or an [owl:Class](http://www.w3.org/2002/07/owl#Class). Thus either of the following triples must be present for an entity type with the CURIE "example:myClass"--it is not necessary to have both:

| Subject | Predicate | Object |
| --- | --- | --- |
| example:myClass | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | rdfs:Class |
| example:myClass | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | owl:Class |

In addition to the triples described in the section "Documentation triples for any object" above, the following triples will have the following effects which it is hoped are understood from the examples given:

| Subject | Predicate | Object | Notes |
| --- | --- | --- | --- |
| example:myClass | [rdfs:subClassOf](http://www.w3.org/2000/01/rdf-schema#subClassOf) | example:mySuperClass | |

Please let [Mahir](mailto:mmorshed@scripps.edu) know if the graph documentation generator should be aware of any other triples that characterize an entity type.

### Predicates

Each predicate in your graph should be at least one of a number of possible types--that is, a predicate "example:myPredicate" should have at least one of the following triples defined as appropriate:

| Subject | Predicate | Object | Notes |
| --- | --- | --- | --- |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [rdf:Property](http://www.w3.org/1999/02/22-rdf-syntax-ns#Property) | |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [rdfs:ContainerMembershipProperty](http://www.w3.org/2000/01/rdf-schema#ContainerMembershipProperty) | |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:DatatypeProperty](http://www.w3.org/2002/07/owl#DatatypeProperty) | |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:AnnotationProperty](http://www.w3.org/2002/07/owl#AnnotationProperty) | |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:ObjectProperty](http://www.w3.org/2002/07/owl#ObjectProperty) | |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:SymmetricProperty](http://www.w3.org/2002/07/owl#SymmetricProperty) | [^2] |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:AsymmetricProperty](http://www.w3.org/2002/07/owl#AsymmetricProperty) | [^2] |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:IrreflexiveProperty](http://www.w3.org/2002/07/owl#IrreflexiveProperty) | [^2] |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:ReflexiveProperty](http://www.w3.org/2002/07/owl#ReflexiveProperty) | [^2] |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:TransitiveProperty](http://www.w3.org/2002/07/owl#TransitiveProperty) | [^2] |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:FunctionalProperty](http://www.w3.org/2002/07/owl#FunctionalProperty) | [^2] |

[^2]: The named characteristic of the predicate type will be reflected in the predicate documentation.

The following triples will have the following effects which it is hoped are understood from the examples given:

| Subject | Predicate | Object | Notes |
| --- | --- | --- | --- |
| example:myPredicate | [rdfs:domain](http://www.w3.org/2000/01/rdf-schema#domain) | example:oneDomainType | Multiple domain triples may be present to include multiple types. |
| example:myPredicate | [rdfs:range](http://www.w3.org/2000/01/rdf-schema#range) | example:RangeType | |
| example:myPredicate | [rdfs:subPropertyOf](http://www.w3.org/2000/01/rdf-schema#subPropertyOf) | example:mySuperClass | |

Please let [Mahir](mailto:mmorshed@scripps.edu) know if the graph documentation generator should be aware of any other triples that characterize a predicate.

## Importing information from external ontologies

At the moment only auxiliary information from schema.org is introduced when a type or predicate from that ontology is encountered, so it is not strictly necessary to re-describe such a type/predicate if you use it in your own graph. Introducing such information from other external ontologies (including from those hosted on w3.org and the OBO foundry) is planned to be supported soon.