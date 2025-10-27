

# Class: IATF certificate (sudokn_IATFCertificate)





URI: [sudokn:IATFCertificate](http://asu.edu/semantics/SUDOKN/IATFCertificate)






```mermaid
 classDiagram
    class SudoknIATFCertificate
    click SudoknIATFCertificate href "../SudoknIATFCertificate"
      SudoknQualityCertificate <|-- SudoknIATFCertificate
        click SudoknQualityCertificate href "../SudoknQualityCertificate"
      

      SudoknIATFCertificate <|-- SudoknIATF16949Certificate
        click SudoknIATF16949Certificate href "../SudoknIATF16949Certificate"
      
      
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * [SudoknCertificate](../classes/SudoknCertificate.md)
        * [SudoknQualityCertificate](../classes/SudoknQualityCertificate.md)
            * **SudoknIATFCertificate**
                * [SudoknIATF16949Certificate](../classes/SudoknIATF16949Certificate.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_IATFCertificate
title: IATF certificate
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_QualityCertificate
class_uri: sudokn:IATFCertificate

```
</details>

### Induced

<details>

```yaml
name: sudokn_IATFCertificate
title: IATF certificate
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_QualityCertificate
class_uri: sudokn:IATFCertificate

```
</details>