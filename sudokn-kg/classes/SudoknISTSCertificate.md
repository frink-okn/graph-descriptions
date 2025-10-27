

# Class: ISTS certificate (sudokn_ISTSCertificate)





URI: [sudokn:ISTSCertificate](http://asu.edu/semantics/SUDOKN/ISTSCertificate)






```mermaid
 classDiagram
    class SudoknISTSCertificate
    click SudoknISTSCertificate href "../SudoknISTSCertificate"
      SudoknQualityCertificate <|-- SudoknISTSCertificate
        click SudoknQualityCertificate href "../SudoknQualityCertificate"
      

      SudoknISTSCertificate <|-- SudoknISTS16949Certificate
        click SudoknISTS16949Certificate href "../SudoknISTS16949Certificate"
      
      
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * [SudoknCertificate](../classes/SudoknCertificate.md)
        * [SudoknQualityCertificate](../classes/SudoknQualityCertificate.md)
            * **SudoknISTSCertificate**
                * [SudoknISTS16949Certificate](../classes/SudoknISTS16949Certificate.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_ISTSCertificate
title: ISTS certificate
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_QualityCertificate
class_uri: sudokn:ISTSCertificate

```
</details>

### Induced

<details>

```yaml
name: sudokn_ISTSCertificate
title: ISTS certificate
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_QualityCertificate
class_uri: sudokn:ISTSCertificate

```
</details>