

# Class: ISO quality certificate (sudokn_ISOQualityCertificate)





URI: [sudokn:ISOQualityCertificate](http://asu.edu/semantics/SUDOKN/ISOQualityCertificate)






```mermaid
 classDiagram
    class SudoknISOQualityCertificate
    click SudoknISOQualityCertificate href "../SudoknISOQualityCertificate"
      SudoknQualityCertificate <|-- SudoknISOQualityCertificate
        click SudoknQualityCertificate href "../SudoknQualityCertificate"
      

      SudoknISOQualityCertificate <|-- SudoknISO13485Certificate
        click SudoknISO13485Certificate href "../SudoknISO13485Certificate"
      SudoknISOQualityCertificate <|-- SudoknISO14000Certificate
        click SudoknISO14000Certificate href "../SudoknISO14000Certificate"
      SudoknISOQualityCertificate <|-- SudoknISO14001Certificate
        click SudoknISO14001Certificate href "../SudoknISO14001Certificate"
      SudoknISOQualityCertificate <|-- SudoknISO17265Certificate
        click SudoknISO17265Certificate href "../SudoknISO17265Certificate"
      SudoknISOQualityCertificate <|-- SudoknISO27001Certificate
        click SudoknISO27001Certificate href "../SudoknISO27001Certificate"
      SudoknISOQualityCertificate <|-- SudoknISO9000Certificate
        click SudoknISO9000Certificate href "../SudoknISO9000Certificate"
      SudoknISOQualityCertificate <|-- SudoknISO9001Certificate
        click SudoknISO9001Certificate href "../SudoknISO9001Certificate"
      
      
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * [SudoknCertificate](../classes/SudoknCertificate.md)
        * [SudoknQualityCertificate](../classes/SudoknQualityCertificate.md)
            * **SudoknISOQualityCertificate**
                * [SudoknISO13485Certificate](../classes/SudoknISO13485Certificate.md)
                * [SudoknISO14000Certificate](../classes/SudoknISO14000Certificate.md)
                * [SudoknISO14001Certificate](../classes/SudoknISO14001Certificate.md)
                * [SudoknISO17265Certificate](../classes/SudoknISO17265Certificate.md)
                * [SudoknISO27001Certificate](../classes/SudoknISO27001Certificate.md)
                * [SudoknISO9000Certificate](../classes/SudoknISO9000Certificate.md)
                * [SudoknISO9001Certificate](../classes/SudoknISO9001Certificate.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |







## Aliases


* International Organization for Standardization Certificate








## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_ISOQualityCertificate
title: ISO quality certificate
from_schema: okns:sudokn-kg
aliases:
- International Organization for Standardization Certificate
rank: 1000
is_a: sudokn_QualityCertificate
class_uri: sudokn:ISOQualityCertificate

```
</details>

### Induced

<details>

```yaml
name: sudokn_ISOQualityCertificate
title: ISO quality certificate
from_schema: okns:sudokn-kg
aliases:
- International Organization for Standardization Certificate
rank: 1000
is_a: sudokn_QualityCertificate
class_uri: sudokn:ISOQualityCertificate

```
</details>