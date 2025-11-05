

# Class: classifier (sudokn_Classifier)





URI: [sudokn:Classifier](http://asu.edu/semantics/SUDOKN/Classifier)






```mermaid
 classDiagram
    class SudoknClassifier
    click SudoknClassifier href "../SudoknClassifier"
      IoInformationContentEntity <|-- SudoknClassifier
        click IoInformationContentEntity href "../IoInformationContentEntity"
      

      SudoknClassifier <|-- SudoknNAICSClassifier
        click SudoknNAICSClassifier href "../SudoknNAICSClassifier"
      SudoknClassifier <|-- SudoknSpecialBusinessStatusClassifier
        click SudoknSpecialBusinessStatusClassifier href "../SudoknSpecialBusinessStatusClassifier"
      
      
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * **SudoknClassifier**
        * [SudoknNAICSClassifier](../classes/SudoknNAICSClassifier.md)
        * [SudoknSpecialBusinessStatusClassifier](../classes/SudoknSpecialBusinessStatusClassifier.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_Classifier
title: classifier
from_schema: okns:sudokn-kg
rank: 1000
is_a: io_InformationContentEntity
class_uri: sudokn:Classifier

```
</details>

### Induced

<details>

```yaml
name: sudokn_Classifier
title: classifier
from_schema: okns:sudokn-kg
rank: 1000
is_a: io_InformationContentEntity
class_uri: sudokn:Classifier

```
</details>