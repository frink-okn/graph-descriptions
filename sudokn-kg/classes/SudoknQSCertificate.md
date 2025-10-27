

# Class: QS certificate (sudokn_QSCertificate)





URI: [sudokn:QSCertificate](http://asu.edu/semantics/SUDOKN/QSCertificate)






```mermaid
 classDiagram
    class SudoknQSCertificate
    click SudoknQSCertificate href "../SudoknQSCertificate"
      SudoknQualityCertificate <|-- SudoknQSCertificate
        click SudoknQualityCertificate href "../SudoknQualityCertificate"
      

      SudoknQSCertificate <|-- SudoknQS9000Certificate
        click SudoknQS9000Certificate href "../SudoknQS9000Certificate"
      
      
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * [SudoknCertificate](../classes/SudoknCertificate.md)
        * [SudoknQualityCertificate](../classes/SudoknQualityCertificate.md)
            * **SudoknQSCertificate**
                * [SudoknQS9000Certificate](../classes/SudoknQS9000Certificate.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_QSCertificate
title: QS certificate
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_QualityCertificate
class_uri: sudokn:QSCertificate

```
</details>

### Induced

<details>

```yaml
name: sudokn_QSCertificate
title: QS certificate
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_QualityCertificate
class_uri: sudokn:QSCertificate

```
</details>