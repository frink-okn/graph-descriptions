

# Class: certificate (sudokn_Certificate)


_No type description provided_





URI: [sudokn:Certificate](http://asu.edu/semantics/SUDOKN/Certificate)






```mermaid
 classDiagram
    class SudoknCertificate
    click SudoknCertificate href "../SudoknCertificate"
      IoInformationContentEntity <|-- SudoknCertificate
        click IoInformationContentEntity href "../IoInformationContentEntity"
      

      SudoknCertificate <|-- SudoknQualityCertificate
        click SudoknQualityCertificate href "../SudoknQualityCertificate"
      
      
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * **SudoknCertificate**
        * [SudoknQualityCertificate](../classes/SudoknQualityCertificate.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SudoknAS9100Certificate](../classes/SudoknAS9100Certificate.md) | [sudokn_attestsTo](../slots/sudokn_attestsTo.md) | domain | [SudoknCertificate](../classes/SudoknCertificate.md) |
| [SudoknISO9000Certificate](../classes/SudoknISO9000Certificate.md) | [sudokn_attestsTo](../slots/sudokn_attestsTo.md) | domain | [SudoknCertificate](../classes/SudoknCertificate.md) |






## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sudokn-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sudokn:Certificate |
| native | sudokn-kg/:SudoknCertificate |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sudokn_Certificate
description: No type description provided
title: certificate
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
from_schema: sudokn-kg
rank: 1000
is_a: io_InformationContentEntity
class_uri: sudokn:Certificate

```
</details>

### Induced

<details>
```yaml
name: sudokn_Certificate
description: No type description provided
title: certificate
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
from_schema: sudokn-kg
rank: 1000
is_a: io_InformationContentEntity
class_uri: sudokn:Certificate

```
</details>