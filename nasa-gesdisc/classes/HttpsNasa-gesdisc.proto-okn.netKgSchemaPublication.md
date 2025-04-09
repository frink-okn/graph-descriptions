

# Class: No class (type) name specified (https___nasa-gesdisc.proto-okn.net_kg_schema_Publication)


_No class (type) description specified_






This class occurs 135352 times.


URI: [https://nasa-gesdisc.proto-okn.net/kg/schema/Publication](https://nasa-gesdisc.proto-okn.net/kg/schema/Publication)






```mermaid
 classDiagram
    class HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication
    click HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication href "../HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication"
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : dct_identifier
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication --> "0..1" String : dct_identifier
    click String href "../String"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : http___www.w3.org_2006_time#year
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication --> "0..1" Integer : http___www.w3.org_2006_time#year
    click Integer href "../Integer"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : https___nasa_gesdisc.proto_okn.net_kg_schema_CITES
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication --> "0..1" HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : https___nasa_gesdisc.proto_okn.net_kg_schema_CITES
    click HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication href "../HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : https___nasa_gesdisc.proto_okn.net_kg_schema_globalId
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication --> "0..1" String : https___nasa_gesdisc.proto_okn.net_kg_schema_globalId
    click String href "../String"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication --> "0..1" HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword : https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA
    click HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword href "../HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : https___nasa_gesdisc.proto_okn.net_kg_schema_pagerank_publication_dataset
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication --> "0..1" Float : https___nasa_gesdisc.proto_okn.net_kg_schema_pagerank_publication_dataset
    click Float href "../Float"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : https___nasa_gesdisc.proto_okn.net_kg_schema_USES_DATASET
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication --> "0..1" HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset : https___nasa_gesdisc.proto_okn.net_kg_schema_USES_DATASET
    click HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset href "../HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : schema_abstract
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication --> "0..1" String : schema_abstract
    click String href "../String"

        
      HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication : schema_title
        
          
    
    
    HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication --> "0..1" String : schema_title
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_globalId](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_globalId.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 135352 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_pagerank_publication_dataset](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_pagerank_publication_dataset.md) | 0..1 <br/> [xsd:float](http://www.w3.org/2001/XMLSchema#float) | No slot (predicate) description specified <br/>  | direct | 135352 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA.md) | 0..1 <br/> [HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaScienceKeyword.md) | No slot (predicate) description specified <br/>  | direct | 119695 |
| [schema_abstract](../slots/schema_abstract.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | An abstract is a short description that summarizes a [[CreativeWork]] <br/>  | direct | 134641 |
| [dct_identifier](../slots/dct_identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 135352 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_CITES](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_CITES.md) | 0..1 <br/> [HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication.md) | No slot (predicate) description specified <br/>  | direct | 208429 |
| [https___nasa_gesdisc.proto_okn.net_kg_schema_USES_DATASET](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_USES_DATASET.md) | 0..1 <br/> [HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaDataset.md) | No slot (predicate) description specified <br/>  | direct | 25861 |
| [http___www.w3.org_2006_time#year](../slots/http___www.w3.org_2006_time#year.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 135348 |
| [schema_title](../slots/schema_title.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | The title of the job <br/>  | direct | 135343 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication.md) | [https___nasa_gesdisc.proto_okn.net_kg_schema_CITES](../slots/https___nasa_gesdisc.proto_okn.net_kg_schema_CITES.md) | range | [HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication.md) |
| [RdfStatement](../classes/RdfStatement.md) | [rdf_subject](../slots/rdf_subject.md) | any_of[range] | [HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication.md) |
| [RdfStatement](../classes/RdfStatement.md) | [rdf_object](../slots/rdf_object.md) | any_of[range] | [HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication](../classes/HttpsNasa-gesdisc.proto-okn.netKgSchemaPublication.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 135352
description: No class (type) description specified
title: No class (type) name specified
from_schema: nasa-gesdisc
rank: 1000
slots:
- https___nasa-gesdisc.proto-okn.net_kg_schema_globalId
- https___nasa-gesdisc.proto-okn.net_kg_schema_pagerank_publication_dataset
- https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA
- schema_abstract
- dct_identifier
- https___nasa-gesdisc.proto-okn.net_kg_schema_CITES
- https___nasa-gesdisc.proto-okn.net_kg_schema_USES_DATASET
- http___www.w3.org_2006_time#year
- schema_title
slot_usage:
  dct_identifier:
    name: dct_identifier
    annotations:
      string:
        tag: string
        value: 135352
  http___www.w3.org_2006_time#year:
    name: http___www.w3.org_2006_time#year
    annotations:
      integer:
        tag: integer
        value: 135348
  https___nasa-gesdisc.proto-okn.net_kg_schema_CITES:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_CITES
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_Publication:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
        value: 208429
  https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
        value: 119695
  https___nasa-gesdisc.proto-okn.net_kg_schema_USES_DATASET:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_USES_DATASET
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
        value: 25861
  https___nasa-gesdisc.proto-okn.net_kg_schema_globalId:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_globalId
    annotations:
      string:
        tag: string
        value: 135352
  https___nasa-gesdisc.proto-okn.net_kg_schema_pagerank_publication_dataset:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_pagerank_publication_dataset
    annotations:
      float:
        tag: float
        value: 135352
  schema_abstract:
    name: schema_abstract
    annotations:
      string:
        tag: string
        value: 134641
  schema_title:
    name: schema_title
    annotations:
      string:
        tag: string
        value: 135343
class_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/Publication

```
</details>

### Induced

<details>

```yaml
name: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 135352
description: No class (type) description specified
title: No class (type) name specified
from_schema: nasa-gesdisc
rank: 1000
slot_usage:
  dct_identifier:
    name: dct_identifier
    annotations:
      string:
        tag: string
        value: 135352
  http___www.w3.org_2006_time#year:
    name: http___www.w3.org_2006_time#year
    annotations:
      integer:
        tag: integer
        value: 135348
  https___nasa-gesdisc.proto-okn.net_kg_schema_CITES:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_CITES
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_Publication:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
        value: 208429
  https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
        value: 119695
  https___nasa-gesdisc.proto-okn.net_kg_schema_USES_DATASET:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_USES_DATASET
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
        value: 25861
  https___nasa-gesdisc.proto-okn.net_kg_schema_globalId:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_globalId
    annotations:
      string:
        tag: string
        value: 135352
  https___nasa-gesdisc.proto-okn.net_kg_schema_pagerank_publication_dataset:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_pagerank_publication_dataset
    annotations:
      float:
        tag: float
        value: 135352
  schema_abstract:
    name: schema_abstract
    annotations:
      string:
        tag: string
        value: 134641
  schema_title:
    name: schema_title
    annotations:
      string:
        tag: string
        value: 135343
attributes:
  https___nasa-gesdisc.proto-okn.net_kg_schema_globalId:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_globalId
    annotations:
      string:
        tag: string
        value: 135352
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: dcf602c1-0e51-55f1-97fb-dbfb8a704c0f
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/0
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - object:
        example_object: dd0ff369-99bb-5ea4-87e8-769ead7dd7c2
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/10000
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    - object:
        example_object: 3133f2fc-268e-50c1-ba3d-ded48c82484b
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/34483
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
    - object:
        example_object: 46b38de5-bd0d-5055-a829-27b9bd736e7a
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/6821
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    - object:
        example_object: 7540d35b-6334-52e4-a566-a6b56529bef1
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7018
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    - object:
        example_object: 5a0c4d6a-8696-5c21-a821-63301ab32ffa
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7369
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    - object:
        example_object: f4d62d70-809d-5264-97c2-9fee6f7e54c0
        example_object_type: string
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/7820
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/globalId
    alias: https___nasa_gesdisc.proto_okn.net_kg_schema_globalId
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_DataCenter
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Instrument
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Platform
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Project
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    - https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
    range: string
  https___nasa-gesdisc.proto-okn.net_kg_schema_pagerank_publication_dataset:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_pagerank_publication_dataset
    annotations:
      float:
        tag: float
        value: 135352
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.15000000000000002'
        example_object_type: float
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/pagerank_publication_dataset
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/0
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - object:
        example_object: '2.0837499999999998'
        example_object_type: float
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/pagerank_publication_dataset
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/10000
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/pagerank_publication_dataset
    alias: https___nasa_gesdisc.proto_okn.net_kg_schema_pagerank_publication_dataset
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    range: float
  https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
        value: 119695
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: https://nasa-gesdisc.proto-okn.net/kg/node/35220
        example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/HAS_APPLIEDRESEARCHAREA
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/10000
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/HAS_APPLIEDRESEARCHAREA
    alias: https___nasa_gesdisc.proto_okn.net_kg_schema_HAS_APPLIEDRESEARCHAREA
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    range: https___nasa-gesdisc.proto-okn.net_kg_schema_ScienceKeyword
  schema_abstract:
    name: schema_abstract
    annotations:
      string:
        tag: string
        value: 134641
    description: An abstract is a short description that summarizes a [[CreativeWork]].
    title: abstract
    examples:
    - object:
        example_object: 'This European Remote Sensing (ERS) Sigma-0 dataset is generated
          by the Scatterometer Climate Record Pathfinder (SCP) project at Brigham
          Young University (BYU) and is generated using a Scatterometer Image Reconstruction
          (SIR) technique developed by Dr. David Long at BYU. The dataset provides
          SIR processed Sigma-0 data from the ERS-1 C-band scatterometer, which is
          also known as the Active Microwave Instrument (AMI). AMI is a multimode
          radar operating at a frequency of 5.3 GHz (C-band), using vertically polarized
          antennas for both transmission and reception. The SIR technique results
          in an enhanced resolution image reconstruction and gridded on an equal-area
          grid (for non-polar regions) at 8.9 km pixel resolution stored in SIR files;
          polar regions are gridded at the same resolution using a polar-stereographic
          technique. A non-enhanced version is provided at 44.5 km pixel resolution
          in a format known as GRD (i.e., gridded) files. All files are produced in
          IEEE formatted binary. All data files are separated and organized by region,
          parameter, and sampling technique (i.e., SIR vs. GRD). The regions of China
          and Japan are combined into a single region. In addition to Sigma-0, various
          statistical parameters are provided for added guidance, including but not
          limited to: standard deviation, measurement counts, pixel time, Sigma-0
          error, and average incidence angle. This dataset was once distributed on
          tape, but has been made available on FTP thanks to the BYU SCP.'
        example_object_type: string
        example_predicate: schema:abstract
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/0
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - object:
        example_object: 'The prosperity and well-being of human societies relies on
          healthy ecosystems and the services they provide. However, the biodiversity
          crisis is undermining ecosystems services and functions. Vultures are among
          the most imperiled taxonomic groups on Earth, yet they have a fundamental
          ecosystem function. These obligate scavengers rapidly consume large amounts
          of carrion and human waste, a service that may aid in both disease prevention
          and control of mammalian scavengers, including feral dogs, which in turn
          threaten humans. We combined information about the distribution of all 15
          vulture species found in Europe, Asia, and Africa with their threats and
          used detailed expert knowledge on threat intensity to prioritize critical
          areas for conserving vultures in Africa and Eurasia. Threats we identified
          included poisoning, mortality due to collision with wind energy infrastructures,
          and other anthropogenic activities related to human land use and influence.
          Areas important for vulture conservation were concentrated in southern and
          eastern Africa, South Asia, and the Iberian Peninsula, and over 80% of these
          areas were unprotected. Some vulture species required larger areas for protection
          than others. Finally, countries that had the largest share of all identified
          important priority areas for vulture conservation were those with the largest
          expenditures related to rabies burden (e.g., India, China, and Myanmar).
          Vulture populations have declined markedly in most of these countries. Restoring
          healthy vulture populations through targeted actions in the priority areas
          we identified may help restore the ecosystem services vultures provide,
          including sanitation and potentially prevention of diseases, such as rabies,
          a heavy burden afflicting fragile societies. Our findings may guide stakeholders
          to prioritize actions where they are needed most in order to achieve international
          goals for biodiversity conservation and sustainable development.Areas Prioritarias
          para la Conservacion de Buitres del Viejo MundoResumenLa prosperidad y el
          bienestar de la sociedad humana dependen de ecosistemas sanos y de los servicios
          ambientales que estos proporcionan. Sin embargo, la crisis de biodiversidad
          esta afectando a los servicios ambientales y sus funciones. Los buitres
          se encuentran entre los grupos taxonomicos con mayor amenaza sobre el planeta,
          a pesar de tener una funcion fundamental en los ecosistemas. Estos carroneros
          obligados consumen rapidamente grandes cantidades de carrona y desechos
          humanos, un servicio que puede ayudar en la prevencion de enfermedades y
          en el control de mamiferos carroneros, incluyendo a los perros ferales,
          los cuales pueden ser un peligro para los humanos. Combinamos la informacion
          sobre la distribucion de las 15 especies de buitres en Europa, Asia y Africa
          con las amenazas que presentan y usamos el conocimiento detallado de expertos
          sobre la intensidad de las amenazas para priorizar las areas criticas para
          la conservacion de buitres en Africa y en Eurasia. Las amenazas que identificamos
          incluyeron el envenenamiento, la mortalidad por colisiones con infraestructura
          eolica y otras actividades antropogenicas relacionadas con el uso de suelo
          y la influencia humana. Las areas importantes para la conservacion de buitres
          estuvieron concentradas en el sur y el este de Africa, el sur de Asia y
          la Peninsula Iberica, y mas del 80% de estas areas no contaban con proteccion.
          Algunas especies de buitres requirieron areas mas grandes para su proteccion
          que otras especies. Finalmente, los paises que tuvieron la mayor porcion
          de todas las areas prioritarias importantes e identificadas para la conservacion
          de buitres tambien fueron aquellos con los mayores gastos relacionados con
          la carga de la rabia (por ejemplo, India, China y Myanmar). Las poblaciones
          de buitres han declinado marcadamente en la mayoria de estos paises. La
          restauracion de poblaciones sanas de buitres por medio de acciones enfocadas
          en las areas prioritarias que identificamos puede ayudar a restaurar los
          servicios ambientales que proporcionan los buitres, incluyendo el saneamiento
          y la prevencion potencial de enfermedades, como la rabia, una carga pesada
          que aflige a las sociedades fragiles. Nuestros resultados pueden guiar a
          los interesados hacia la priorizacion de acciones en donde mas se necesitan
          para poder alcanzar los objetivos internacionales para la conservacion de
          la biodiversidad y el desarrollo sustentable., , , , , , , , ,  80% , ,
          (), , , , , : ; : Article impact statement: Eighty percent of areas important
          for Old World vulture conservation are unprotected and in southern and eastern
          Africa, South Asia, and Iberia.'
        example_object_type: string
        example_predicate: schema:abstract
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/10000
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: schema:abstract
    alias: schema_abstract
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    range: string
  dct_identifier:
    name: dct_identifier
    annotations:
      string:
        tag: string
        value: 135352
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 10.5067/ERS1B-SNEN0
        example_object_type: string
        example_predicate: dct:identifier
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/0
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - object:
        example_object: 10.1111/COBI.13282
        example_object_type: string
        example_predicate: dct:identifier
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/10000
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: dct:identifier
    alias: dct_identifier
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    range: string
  https___nasa-gesdisc.proto-okn.net_kg_schema_CITES:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_CITES
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_Publication:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
        value: 208429
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: https://nasa-gesdisc.proto-okn.net/kg/node/23747
        example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/CITES
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/100000
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/CITES
    alias: https___nasa_gesdisc.proto_okn.net_kg_schema_CITES
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    range: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
  https___nasa-gesdisc.proto-okn.net_kg_schema_USES_DATASET:
    name: https___nasa-gesdisc.proto-okn.net_kg_schema_USES_DATASET
    annotations:
      https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset:
        tag: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
        value: 25861
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: https://nasa-gesdisc.proto-okn.net/kg/node/161
        example_object_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
        example_predicate: https://nasa-gesdisc.proto-okn.net/kg/schema/USES_DATASET
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/10004
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/USES_DATASET
    alias: https___nasa_gesdisc.proto_okn.net_kg_schema_USES_DATASET
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    range: https___nasa-gesdisc.proto-okn.net_kg_schema_Dataset
  http___www.w3.org_2006_time#year:
    name: http___www.w3.org_2006_time#year
    annotations:
      integer:
        tag: integer
        value: 135348
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2019'
        example_object_type: integer
        example_predicate: http://www.w3.org/2006/time#year
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/10000
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: http://www.w3.org/2006/time#year
    alias: http___www.w3.org_2006_time#year
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    range: integer
  schema_title:
    name: schema_title
    annotations:
      string:
        tag: string
        value: 135343
    description: The title of the job.
    title: title
    examples:
    - object:
        example_object: Priority areas for conservation of Old World vultures
        example_object_type: string
        example_predicate: schema:title
        example_subject: https://nasa-gesdisc.proto-okn.net/kg/node/10000
        example_subject_type: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    from_schema: nasa-gesdisc
    rank: 1000
    slot_uri: schema:title
    alias: schema_title
    owner: https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    domain_of:
    - https___nasa-gesdisc.proto-okn.net_kg_schema_Publication
    range: string
class_uri: https://nasa-gesdisc.proto-okn.net/kg/schema/Publication

```
</details>