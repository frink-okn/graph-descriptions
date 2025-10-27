

# Class: professional certificate (sudokn_ProfessionalCertificate)





URI: [sudokn:ProfessionalCertificate](http://asu.edu/semantics/SUDOKN/ProfessionalCertificate)






```mermaid
 classDiagram
    class SudoknProfessionalCertificate
    click SudoknProfessionalCertificate href "../SudoknProfessionalCertificate"
      SudoknCertificate <|-- SudoknProfessionalCertificate
        click SudoknCertificate href "../SudoknCertificate"
      

      SudoknProfessionalCertificate <|-- SudoknAWSWelderCertificate
        click SudoknAWSWelderCertificate href "../SudoknAWSWelderCertificate"
      
      
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * [SudoknCertificate](../classes/SudoknCertificate.md)
        * **SudoknProfessionalCertificate**
            * [SudoknAWSWelderCertificate](../classes/SudoknAWSWelderCertificate.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_ProfessionalCertificate
title: professional certificate
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_Certificate
class_uri: sudokn:ProfessionalCertificate

```
</details>

### Induced

<details>

```yaml
name: sudokn_ProfessionalCertificate
title: professional certificate
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_Certificate
class_uri: sudokn:ProfessionalCertificate

```
</details>