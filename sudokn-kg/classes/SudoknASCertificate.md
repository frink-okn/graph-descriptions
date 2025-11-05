

# Class: AS certificate (sudokn_ASCertificate)





URI: [sudokn:ASCertificate](http://asu.edu/semantics/SUDOKN/ASCertificate)






```mermaid
 classDiagram
    class SudoknASCertificate
    click SudoknASCertificate href "../SudoknASCertificate"
      SudoknQualityCertificate <|-- SudoknASCertificate
        click SudoknQualityCertificate href "../SudoknQualityCertificate"
      

      SudoknASCertificate <|-- SudoknAS9000Certificate
        click SudoknAS9000Certificate href "../SudoknAS9000Certificate"
      SudoknASCertificate <|-- SudoknAS9003Certificate
        click SudoknAS9003Certificate href "../SudoknAS9003Certificate"
      SudoknASCertificate <|-- SudoknAS9100Certificate
        click SudoknAS9100Certificate href "../SudoknAS9100Certificate"
      SudoknASCertificate <|-- SudoknAS9102Certificate
        click SudoknAS9102Certificate href "../SudoknAS9102Certificate"
      SudoknASCertificate <|-- SudoknAS9120Certificate
        click SudoknAS9120Certificate href "../SudoknAS9120Certificate"
      
      
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * [SudoknCertificate](../classes/SudoknCertificate.md)
        * [SudoknQualityCertificate](../classes/SudoknQualityCertificate.md)
            * **SudoknASCertificate**
                * [SudoknAS9000Certificate](../classes/SudoknAS9000Certificate.md)
                * [SudoknAS9003Certificate](../classes/SudoknAS9003Certificate.md)
                * [SudoknAS9100Certificate](../classes/SudoknAS9100Certificate.md)
                * [SudoknAS9102Certificate](../classes/SudoknAS9102Certificate.md)
                * [SudoknAS9120Certificate](../classes/SudoknAS9120Certificate.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_ASCertificate
title: AS certificate
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_QualityCertificate
class_uri: sudokn:ASCertificate

```
</details>

### Induced

<details>

```yaml
name: sudokn_ASCertificate
title: AS certificate
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_QualityCertificate
class_uri: sudokn:ASCertificate

```
</details>