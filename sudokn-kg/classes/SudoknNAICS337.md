

# Class: furniture and related product manufacturing (sudokn_NAICS337)





URI: [sudokn:NAICS337](http://asu.edu/semantics/SUDOKN/NAICS337)






```mermaid
 classDiagram
    class SudoknNAICS337
    click SudoknNAICS337 href "../SudoknNAICS337"
      SudoknNAICS33 <|-- SudoknNAICS337
        click SudoknNAICS33 href "../SudoknNAICS33"
      

      SudoknNAICS337 <|-- SudoknNAICS337110
        click SudoknNAICS337110 href "../SudoknNAICS337110"
      SudoknNAICS337 <|-- SudoknNAICS337121
        click SudoknNAICS337121 href "../SudoknNAICS337121"
      SudoknNAICS337 <|-- SudoknNAICS337122
        click SudoknNAICS337122 href "../SudoknNAICS337122"
      SudoknNAICS337 <|-- SudoknNAICS337126
        click SudoknNAICS337126 href "../SudoknNAICS337126"
      SudoknNAICS337 <|-- SudoknNAICS337127
        click SudoknNAICS337127 href "../SudoknNAICS337127"
      SudoknNAICS337 <|-- SudoknNAICS337211
        click SudoknNAICS337211 href "../SudoknNAICS337211"
      SudoknNAICS337 <|-- SudoknNAICS337212
        click SudoknNAICS337212 href "../SudoknNAICS337212"
      SudoknNAICS337 <|-- SudoknNAICS337214
        click SudoknNAICS337214 href "../SudoknNAICS337214"
      SudoknNAICS337 <|-- SudoknNAICS337215
        click SudoknNAICS337215 href "../SudoknNAICS337215"
      SudoknNAICS337 <|-- SudoknNAICS337910
        click SudoknNAICS337910 href "../SudoknNAICS337910"
      SudoknNAICS337 <|-- SudoknNAICS337920
        click SudoknNAICS337920 href "../SudoknNAICS337920"
      
      
      SudoknNAICS337 : sudokn_hasNAICSCodeValue
        
          
    
    
    SudoknNAICS337 --> "0..1" Integer : sudokn_hasNAICSCodeValue
    click Integer href "../Integer"

        
      SudoknNAICS337 : sudokn_hasNAICSTextValue
        
          
    
    
    SudoknNAICS337 --> "0..1" String : sudokn_hasNAICSTextValue
    click String href "../String"

        
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * [SudoknClassifier](../classes/SudoknClassifier.md)
        * [SudoknNAICSClassifier](../classes/SudoknNAICSClassifier.md)
            * [SudoknNAICS33](../classes/SudoknNAICS33.md)
                * **SudoknNAICS337**
                    * [SudoknNAICS337110](../classes/SudoknNAICS337110.md)
                    * [SudoknNAICS337121](../classes/SudoknNAICS337121.md)
                    * [SudoknNAICS337122](../classes/SudoknNAICS337122.md)
                    * [SudoknNAICS337126](../classes/SudoknNAICS337126.md)
                    * [SudoknNAICS337127](../classes/SudoknNAICS337127.md)
                    * [SudoknNAICS337211](../classes/SudoknNAICS337211.md)
                    * [SudoknNAICS337212](../classes/SudoknNAICS337212.md)
                    * [SudoknNAICS337214](../classes/SudoknNAICS337214.md)
                    * [SudoknNAICS337215](../classes/SudoknNAICS337215.md)
                    * [SudoknNAICS337910](../classes/SudoknNAICS337910.md)
                    * [SudoknNAICS337920](../classes/SudoknNAICS337920.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [sudokn_hasNAICSTextValue](../slots/sudokn_hasNAICSTextValue.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  | [SudoknNAICSClassifier](../classes/SudoknNAICSClassifier.md) |  |
| [sudokn_hasNAICSCodeValue](../slots/sudokn_hasNAICSCodeValue.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) |  | [SudoknNAICSClassifier](../classes/SudoknNAICSClassifier.md) |  |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: sudokn_NAICS337
title: furniture and related product manufacturing
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_NAICS33
class_uri: sudokn:NAICS337

```
</details>

### Induced

<details>

```yaml
name: sudokn_NAICS337
title: furniture and related product manufacturing
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_NAICS33
attributes:
  sudokn_hasNAICSTextValue:
    name: sudokn_hasNAICSTextValue
    title: has NAICS text value
    from_schema: okns:sudokn-kg
    rank: 1000
    domain: sudokn_NAICSClassifier
    slot_uri: sudokn:hasNAICSTextValue
    alias: sudokn_hasNAICSTextValue
    owner: sudokn_NAICS337
    domain_of:
    - sudokn_NAICS332111
    - sudokn_NAICS332112
    - sudokn_NAICS332114
    - sudokn_NAICS332115
    - sudokn_NAICS332116
    - sudokn_NAICS332117
    - sudokn_NAICS332211
    - sudokn_NAICS332212
    - sudokn_NAICS332213
    - sudokn_NAICS332214
    - sudokn_NAICS332311
    - sudokn_NAICS332312
    - sudokn_NAICS332313
    - sudokn_NAICS332321
    - sudokn_NAICS332322
    - sudokn_NAICS332323
    - sudokn_NAICS332410
    - sudokn_NAICS332420
    - sudokn_NAICS332431
    - sudokn_NAICS332439
    - sudokn_NAICS332510
    - sudokn_NAICS332611
    - sudokn_NAICS332612
    - sudokn_NAICS332618
    - sudokn_NAICS332710
    - sudokn_NAICS332721
    - sudokn_NAICS332722
    - sudokn_NAICS332811
    - sudokn_NAICS332812
    - sudokn_NAICS332813
    - sudokn_NAICS332911
    - sudokn_NAICS332912
    - sudokn_NAICS332913
    - sudokn_NAICS332919
    - sudokn_NAICS332991
    - sudokn_NAICS332992
    - sudokn_NAICS332994
    - sudokn_NAICS332995
    - sudokn_NAICS332996
    - sudokn_NAICS332997
    - sudokn_NAICS332998
    - sudokn_NAICS332999
    - sudokn_NAICSClassifier
    subproperty_of: iosc_hasTextValue
    range: string
  sudokn_hasNAICSCodeValue:
    name: sudokn_hasNAICSCodeValue
    title: has NAICS code value
    from_schema: okns:sudokn-kg
    rank: 1000
    domain: sudokn_NAICSClassifier
    slot_uri: sudokn:hasNAICSCodeValue
    alias: sudokn_hasNAICSCodeValue
    owner: sudokn_NAICS337
    domain_of:
    - sudokn_NAICS332111
    - sudokn_NAICS332112
    - sudokn_NAICS332114
    - sudokn_NAICS332115
    - sudokn_NAICS332116
    - sudokn_NAICS332117
    - sudokn_NAICS332211
    - sudokn_NAICS332212
    - sudokn_NAICS332213
    - sudokn_NAICS332214
    - sudokn_NAICS332311
    - sudokn_NAICS332312
    - sudokn_NAICS332313
    - sudokn_NAICS332321
    - sudokn_NAICS332322
    - sudokn_NAICS332323
    - sudokn_NAICS332410
    - sudokn_NAICS332420
    - sudokn_NAICS332431
    - sudokn_NAICS332439
    - sudokn_NAICS332510
    - sudokn_NAICS332611
    - sudokn_NAICS332612
    - sudokn_NAICS332618
    - sudokn_NAICS332710
    - sudokn_NAICS332721
    - sudokn_NAICS332722
    - sudokn_NAICS332811
    - sudokn_NAICS332812
    - sudokn_NAICS332813
    - sudokn_NAICS332911
    - sudokn_NAICS332912
    - sudokn_NAICS332913
    - sudokn_NAICS332919
    - sudokn_NAICS332991
    - sudokn_NAICS332992
    - sudokn_NAICS332994
    - sudokn_NAICS332995
    - sudokn_NAICS332996
    - sudokn_NAICS332997
    - sudokn_NAICS332998
    - sudokn_NAICS332999
    - sudokn_NAICSClassifier
    range: integer
class_uri: sudokn:NAICS337

```
</details>