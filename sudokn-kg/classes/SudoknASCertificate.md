

# Class: AS certificate (sudokn_ASCertificate)


_TODO -- tell the world what this class (type) describes._





URI: [sudokn:ASCertificate](http://asu.edu/semantics/SUDOKN/ASCertificate)






```mermaid
 classDiagram
    class SudoknASCertificate
    click SudoknASCertificate href "../SudoknASCertificate"
      SudoknQualityCertificate <|-- SudoknASCertificate
        click SudoknQualityCertificate href "../SudoknQualityCertificate"
      

      SudoknASCertificate <|-- SudoknAS9003Certificate
        click SudoknAS9003Certificate href "../SudoknAS9003Certificate"
      SudoknASCertificate <|-- SudoknAS9100Certificate
        click SudoknAS9100Certificate href "../SudoknAS9100Certificate"
      SudoknASCertificate <|-- SudoknAS9102Certificate
        click SudoknAS9102Certificate href "../SudoknAS9102Certificate"
      
      
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * [SudoknCertificate](../classes/SudoknCertificate.md)
        * [SudoknQualityCertificate](../classes/SudoknQualityCertificate.md)
            * **SudoknASCertificate**
                * [SudoknAS9003Certificate](../classes/SudoknAS9003Certificate.md)
                * [SudoknAS9100Certificate](../classes/SudoknAS9100Certificate.md)
                * [SudoknAS9102Certificate](../classes/SudoknAS9102Certificate.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |









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
| self | sudokn:ASCertificate |
| native | sudokn-kg/:SudoknASCertificate |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sudokn_ASCertificate
description: TODO -- tell the world what this class (type) describes.
title: AS certificate
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
from_schema: sudokn-kg
is_a: sudokn_QualityCertificate
class_uri: sudokn:ASCertificate

```
</details>

### Induced

<details>
```yaml
name: sudokn_ASCertificate
description: TODO -- tell the world what this class (type) describes.
title: AS certificate
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
from_schema: sudokn-kg
is_a: sudokn_QualityCertificate
class_uri: sudokn:ASCertificate

```
</details>