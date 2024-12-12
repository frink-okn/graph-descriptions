

# Class: TODO -- what's a good name for this class (type)? (cheminf_000446)


_No type description provided_





URI: [cheminf:000446](http://purl.obolibrary.org/obo/CHEMINF_000446)






```mermaid
 classDiagram
    class Cheminf000446
    click Cheminf000446 href "../Cheminf000446"
      Cheminf000446 : dc_source
        
          
    
    
    Cheminf000446 --> "0..1" String : dc_source
    click String href "../String"

        
      Cheminf000446 : rdfs_label
        
          
    
    
    Cheminf000446 --> "0..1" String : rdfs_label
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [dc_source](../slots/dc_source.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Cheminf000000](../classes/Cheminf000000.md) | [edam_has_identifier](../slots/edam_has_identifier.md) | any_of[range] | [Cheminf000446](../classes/Cheminf000446.md) |






## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: biobricks-ice-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | cheminf:000446 |
| native | biobricks-ice-kg/:Cheminf000446 |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: cheminf_000446
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 538147 occurences.
from_schema: biobricks-ice-kg
rank: 1000
slots:
- dc_source
- rdfs_label
class_uri: cheminf:000446

```
</details>

### Induced

<details>
```yaml
name: cheminf_000446
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 538147 occurences.
from_schema: biobricks-ice-kg
rank: 1000
attributes:
  dc_source:
    name: dc_source
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 538147 occurrences with subject type cheminf_000446 and object type string.
    - 538131 occurrences with subject type cheminf_000568 and object type string.
    - 3990 occurrences with subject type bao_0000015 and object type string.
    examples:
    - value: http://identifiers.org/cas/10-00-4 dc:source CAS
    - value: https://comptox.epa.gov/dashboard/chemical/details/DTXSID001002091 dc:source
        CompTox
    - value: https://comptox.epa.gov/dashboard/assay-endpoints/ACEA_AR_agonist_80hr
        dc:source ICE
    from_schema: biobricks-ice-kg
    rank: 1000
    slot_uri: dc:source
    alias: dc_source
    owner: cheminf_000446
    domain_of:
    - bao_0000015
    - cheminf_000446
    - cheminf_000568
    range: string
  rdfs_label:
    name: rdfs_label
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 197214 occurrences with subject type cheminf_000000 and object type string.
    - 413168 occurrences with subject type bao_0000179 and object type string.
    - 542470 occurrences with subject type cheminf_000446 and object type string.
    - 542456 occurrences with subject type cheminf_000568 and object type string.
    - 2063 occurrences with subject type bao_0000015 and object type string.
    examples:
    - value: http://example.com/ice/ADME_Parameters_Data.parquet/dtxsid/DTXSID001009966/Chemical_Entity
        rdfs:label Tegafur
    - value: http://example.com/ice/ADME_Parameters_Data.parquet/record_id/httk2.2.2_DTXSID001009966/dtxsid/DTXSID001009966/endpoint/Fu/Endpoint
        rdfs:label Fu
    - value: http://identifiers.org/cas/10-00-4 rdfs:label Uliginosin B
    - value: https://comptox.epa.gov/dashboard/chemical/details/DTXSID001002091 rdfs:label
        N-[3-(Dimethylamino)propyl]octadeca-9,12-dienimidic acid
    - value: http://example.com/ice/ADME_Parameters_Data.parquet/assay/httk%2C%20Human%20Hepatic%20Intrinsic%20Clearance/Assay
        rdfs:label httk, Human Hepatic Intrinsic Clearance
    from_schema: biobricks-ice-kg
    rank: 1000
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: cheminf_000446
    domain_of:
    - bao_0000015
    - bao_0000179
    - cheminf_000000
    - cheminf_000446
    - cheminf_000568
    range: string
class_uri: cheminf:000446

```
</details>