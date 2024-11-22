

# Class: classifier (sudokn_Classifier)


_TODO -- tell the world what this class (type) describes._





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
| self | sudokn:Classifier |
| native | sudokn-kg/:SudoknClassifier |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sudokn_Classifier
description: TODO -- tell the world what this class (type) describes.
title: classifier
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
from_schema: sudokn-kg
is_a: io_InformationContentEntity
class_uri: sudokn:Classifier

```
</details>

### Induced

<details>
```yaml
name: sudokn_Classifier
description: TODO -- tell the world what this class (type) describes.
title: classifier
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
from_schema: sudokn-kg
is_a: io_InformationContentEntity
class_uri: sudokn:Classifier

```
</details>