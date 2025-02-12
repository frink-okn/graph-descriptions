# Graph Descriptions

This repository holds information about individual Theme 1 graphs based on the data provided for those graphs in FRINK's LakeFS repository.

It is generated first by assembling a [LinkML schema](https://linkml.io/linkml/schemas/index.html), compiling information about the graph through iteration over its triples, and then using [a modification of](https://github.com/frink-okn/schema-gen) [LinkML's Markdown documentation generator](https://linkml.io/linkml/generators/markdown.html) to produce readable pages with class diagrams from that schema.

## Improving graph descriptions

If you wish to improve the descriptions of your graph's entity types and predicates, then you may introduce certain information (in the form of triples) to the data you submit to LakeFS. This information will then update any indicators of absent information that you may encounter in the generated graph documentation.

All [CURIEs](https://www.w3.org/TR/curie/) below are defined through the URLs of the hyperlinks when those CURIEs are first introduced.

### IRI prefixes

We have observed the following IRI prefixes, and thus they will be appropriately substituted wherever they occur in the generated graph documentation:

<details>
<summary>Click here to view the list of prefixes, along with notes about some of them</summary>

| prefix | IRI | notes |
| --- | --- | --- |
| dc: | http://purl.org/dc/elements/1.1/ |  |
| dct: | http://purl.org/dc/terms/ |  |
| geo: | http://www.opengis.net/ont/geosparql# |  |
| owl: | http://www.w3.org/2002/07/owl# |  |
| prov: | http://www.w3.org/ns/prov# |  |
| rdf: | http://www.w3.org/1999/02/22-rdf-syntax-ns# |  |
| rdfs: | http://www.w3.org/2000/01/rdf-schema# |  |
| schema: | https://schema.org/ |  |
| skos: | http://www.w3.org/2004/02/skos/core# |  |
| sosa: | http://www.w3.org/ns/sosa/ |  |
| xsd: | http://www.w3.org/2001/XMLSchema# |  |
| kwg: | https://stko-kwg.geog.ucsb.edu/lod/ontology | KnowWhereGraph |
| niem50: | http://release.niem.gov/niem/niem-core/5.0/ | NIEM Core 5.0 |
| jxdm72: | http://release.niem.gov/niem/domains/jxdm/7.2/# | NIEM Justice 7.2 |
| obo: | http://purl.obolibrary.org/obo/ | OBO Foundry (general) |
| cheminf: | http://purl.obolibrary.org/obo/CHEMINF_ | Chemical Information Ontology |
| bao: | http://www.bioassayontology.org/bao#BAO_ | Bioassay Ontology |
| edam: | http://edamontology.org/ | EDAM ontology |
| semsci: | http://semanticscience.org/resource/SIO_ | Semanticscience Integrated Ontology |
| niehs: | https://ice.ntp.niehs.nih.gov/property/ | Integrated Chemical Environment |
| umls: | https://identifiers.org/umls: | Unified Medical Language System |
| hyf: | https://www.opengis.net/def/schema/hy_features/hyf | OGC ontology |
| sf: | http://www.opengis.net/ont/sf | OGC ontology |
| gwml22: | http://www.opengis.net/gwml-main/2.2/ | OGC ontology |
| hyfo: | https://www.opengis.net/def/hy_features/ontology/hyf/ | OGC ontology |
| hyfa: | https://www.opengis.net/def/appschema/hy_features/hyf/ | OGC ontology |
| phila: | https://metadata.phila.gov/ | City of Philadelphia |
| qudt: | http://qudt.org/schema/qudt/ | QUDT ontology |
| wdp: | http://www.wikidata.org/prop/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdpq: | http://www.wikidata.org/prop/qualifier/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdpqn: | http://www.wikidata.org/prop/qualifier/value-normalized/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdpqv: | http://www.wikidata.org/prop/qualifier/value/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdpr: | http://www.wikidata.org/prop/reference/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdprn: | http://www.wikidata.org/prop/reference/value-normalized/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdprv: | http://www.wikidata.org/prop/reference/value/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdpsv: | http://www.wikidata.org/prop/statement/value/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdps: | http://www.wikidata.org/prop/statement/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdpsn: | http://www.wikidata.org/prop/statement/value-normalized/ | Wikidata-related (from https://w.wiki/4Byv) |
| wd: | http://www.wikidata.org/entity/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdata: | http://www.wikidata.org/wiki/Special:EntityData/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdno: | http://www.wikidata.org/prop/novalue/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdref: | http://www.wikidata.org/reference/ | Wikidata-related (from https://w.wiki/4Byv) |
| wds: | http://www.wikidata.org/entity/statement/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdt: | http://www.wikidata.org/prop/direct/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdtn: | http://www.wikidata.org/prop/direct-normalized/ | Wikidata-related (from https://w.wiki/4Byv) |
| wdv: | http://www.wikidata.org/value/ | Wikidata-related (from https://w.wiki/4Byv) |
| wikibase: | http://wikiba.se/ontology# | Wikidata-related (from https://w.wiki/4Byv) |
| hsdo: | http://schema.org/ | This prefix should be substituted with schema: wherever it occurs. |
| neo4j: | neo4j://graph.schema# | Not a real prefix; should be substituted wherever it occurs. |
| example: | http://example.org/ | Not a real prefix; should be substituted wherever it occurs. |
| attribute: | http://attribute.org/ | Not a real prefix; should be substituted wherever it occurs. |
| relation: | http://relation.org/ | Not a real prefix; should be substituted wherever it occurs. |
| badwdt: | https://www.wikidata.org/wiki/Property: | Not a real RDF prefix; should be substituted wherever it occurs. |
| dreamkg: | http://www.semanticweb.org/dreamkg/ijcai/ | from DREAM-KG; should be substituted with a working IRI prefix. |
| scales: | http://schemas.scales-okn.org/rdf/scales# | from SCALES; should be substituted with a working IRI prefix. |
| sockg: | http://www.semanticweb.org/zzy/ontologies/2024/0/soil-carbon-ontology/ | from SOC-KG; should be substituted with a working IRI prefix. |
| securechain: | https://w3id.org/secure-chain/ | from Secure Chain-KG |
| rural: | http://sail.ua.edu/ruralkg/ | from RURAL-KG; should be substituted with a working IRI prefix. |
| contaminoso: | http://sawgraph.spatialai.org/v1/contaminoso# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| usfrs: | http://sawgraph.spatialai.org/v1/us-frs# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| usfrsdata: | http://sawgraph.spatialai.org/v1/us-frs-data# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| naics: | http://sawgraph.spatialai.org/v1/fio/naics# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| ilisgs: | http://sawgraph.spatialai.org/v1/il-isgs# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| meegad: | http://sawgraph.spatialai.org/v1/me-egad# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| memgs: | http://sawgraph.spatialai.org/v1/me-mgs# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| memgs2: | http://sawgraph.spatialai.org/v1/me_mgs# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| ussdwis: | http://sawgraph.spatialai.org/v1/us-sdwis# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| pfas: | http://sawgraph.spatialai.org/v1/pfas# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| sawwater: | http://sawgraph.spatialai.org/v1/saw_water# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| fio: | http://sawgraph.spatialai.org/v1/fio# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| psys: | http://proton.semanticweb.org/protonsys# | from SAWGRAPH; should be substituted with a working IRI prefix. |
| io: | https://spec.industrialontologies.org/ontology/core/Core/ | Industrial Ontologies Foundry |
| iosc: | https://spec.industrialontologies.org/ontology/supplychain/SupplyChain/ | Industrial Ontologies Foundry |
| sudokn: | http://asu.edu/semantics/SUDOKN/ | from SUDOKN: should be substituted with a working IRI prefix. |
| sudokn2: | Utilities:communication/ | Not a real prefix; should be substituted wherever it occurs. |
| sudokn3: | Utilities:water/ | Not a real prefix; should be substituted wherever it occurs. |
</details>

Please let [Mahir](mailto:mmorshed@scripps.edu) know if you introduce any new IRI prefixes not in the above list that should also be substituted.

### Documentation triples for any object

For any class or predicate that your graph uses, you can add any of the following triples to it and they will be reflected in the documentation appropriately. All of the following example triples document an entity with the CURIE "example:myClass", and it is hoped that the example object values will help indicate what the triples are intended for.

In the following table, only one triple of each type will be reflected in the documentation. For example, if multiple "skos:definition" triples are defined for an object, only one of those "skos:definition" triples for that object will have its information shown.

| Subject | Predicate | Object | Notes |
| --- | --- | --- | --- |
| example:myClass | [dct:description](http://purl.org/dc/terms/description) | "Description of the class" | :white_check_mark: Required (either this, skos:definition, or rdfs:comment) |
| example:myClass | [skos:definition](http://www.w3.org/2004/02/skos/core#definition) | "Description of the class" | :white_check_mark: Required (either this, dct:description, or rdfs:comment) |
| example:myClass | [rdfs:comment](http://www.w3.org/2000/01/rdf-schema#comment) | "Description of the class" | :white_check_mark: Required (either this, dct:description, or skos:definition) |
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
| example:myClass | [rdfs:seeAlso](http://www.w3.org/2000/01/rdf-schema#seeAlso) | https://path.to/another/relevant/uri/of/some/kind |  |
| example:myClass | [skos:altLabel](http://www.w3.org/2004/02/skos/core#altLabel) | "Alternate name for this class" |  |
| example:myClass | [skos:mappingRelation](http://www.w3.org/2004/02/skos/core#altLabel) | https://path.to/uri/that/maps/to/myClass | Object must be a URI. |
| example:myClass | [skos:exactMatch](http://www.w3.org/2004/02/skos/core#exactMatch) | https://path.to/uri/that/exactly/matches/myClass | Object must be a URI. |
| example:myClass | [skos:closeMatch](http://www.w3.org/2004/02/skos/core#closeMatch) | https://path.to/uri/that/is/a/close/match/to/myClass | Object must be a URI. |
| example:myClass | [skos:relatedMatch](http://www.w3.org/2004/02/skos/core#relatedMatch) | https://path.to/uri/that/is/related/to/myClass | Object must be a URI. |
| example:myClass | [skos:narrowMatch](http://www.w3.org/2004/02/skos/core#narrowMatch) | https://path.to/uri/that/narrowly/matches/myClass | Object must be a URI. |
| example:myClass | [skos:broadMatch](http://www.w3.org/2004/02/skos/core#broadMatch) | https://path.to/uri/that/broadly/matches/myClass | Object must be a URI. |
| example:myClass | [dct:contributor](http://purl.org/dc/terms/contributor) | http://github.com/nsf-open | Object must be a URI. |
| example:myClass | [dcat:theme](https://www.w3.org/ns/dcat#theme) | https://path.to/category/in/some/scheme | Object must be a URI. |
| example:myClass | [dcat:keyword](https://www.w3.org/ns/dcat#keyword) | "exemplary class" | |
| example:myClass | [schema:keywords](https://schema.org/keywords) | "exemplary class" | |

[^1]: LinkML specifies that notes be intended either for internal consumption (e.g. for other ontology developers) or for external consumption (e.g. for end-users of the ontology). At the moment all skos: note triples are treated as internal notes; let [Mahir](mailto:mmorshed@scripps.edu) know if you think they should be treated in some other way.

### Ontology (owl:Ontology)

At the moment, since a single HDT file is assumed to represent a whole unit of data modeled in a particular way, it is also assumed that there is exactly one entity of type [owl:Ontology]( http://www.w3.org/2002/07/owl#Ontology) in your graph. Let us assume that the ontology entity has the CURIE "example:myOntology".

In addition to the triples described in the section "Documentation triples for any object" above, the following triples will have the following effects which it is hoped are understood from the examples given:

| Subject | Predicate | Object | Notes |
| --- | --- | --- | --- |
| example:myOntology | [dct:hasVersion](http://purl.org/dc/terms/title) | "0.0.1" | |

Please let [Mahir](mailto:mmorshed@scripps.edu) know if the graph documentation generator should be aware of any other triples that characterize an ontology entity.

### Classes (owl:Class or rdfs:Class)

Each entity type in your graph should have at least one of the following triples present. The example type in the following has the CURIE "example:myClass".

| Subject | Predicate | Object | Notes |
| --- | --- | --- | --- |
| example:myClass | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [rdfs:Class](http://www.w3.org/2000/01/rdf-schema#Class) | :white_check_mark: Required (either this or owl:Class) |
| example:myClass | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:Class](http://www.w3.org/2002/07/owl#Class) | :white_check_mark: Required (either this or rdfs:Class) |
| example:myClass | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:DeprecatedClass](http://www.w3.org/2002/07/owl#Class) | [^2] |

[^2]: The named characteristic of the class type will be reflected in the class documentation.

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
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:SymmetricProperty](http://www.w3.org/2002/07/owl#SymmetricProperty) | [^3] |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:AsymmetricProperty](http://www.w3.org/2002/07/owl#AsymmetricProperty) | [^3] |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:IrreflexiveProperty](http://www.w3.org/2002/07/owl#IrreflexiveProperty) | [^3] |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:ReflexiveProperty](http://www.w3.org/2002/07/owl#ReflexiveProperty) | [^3] |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:TransitiveProperty](http://www.w3.org/2002/07/owl#TransitiveProperty) | [^3] |
| example:myPredicate | [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type) | [owl:FunctionalProperty](http://www.w3.org/2002/07/owl#FunctionalProperty) | [^3] |

[^3]: The named characteristic of the predicate type will be reflected in the predicate documentation.

The following triples will have the following effects which it is hoped are understood from the examples given:

| Subject | Predicate | Object | Notes |
| --- | --- | --- | --- |
| example:myPredicate | [rdfs:domain](http://www.w3.org/2000/01/rdf-schema#domain) | example:oneDomainType | Multiple domain triples may be present to include multiple types. |
| example:myPredicate | [rdfs:range](http://www.w3.org/2000/01/rdf-schema#range) | example:RangeType | |
| example:myPredicate | [rdfs:subPropertyOf](http://www.w3.org/2000/01/rdf-schema#subPropertyOf) | example:mySuperClass | |

Please let [Mahir](mailto:mmorshed@scripps.edu) know if the graph documentation generator should be aware of any other triples that characterize a predicate.

## Importing information from external ontologies

At the moment only auxiliary information from schema.org is introduced when a type or predicate from that ontology is encountered, so it is not strictly necessary to re-describe such a type/predicate if you use it in your own graph. Introducing such information from other external ontologies (including from those hosted on w3.org and the OBO foundry) is planned to be supported soon.