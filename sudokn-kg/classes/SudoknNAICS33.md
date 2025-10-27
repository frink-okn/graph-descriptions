

# Class: NAICS sector 33 (sudokn_NAICS33)





URI: [sudokn:NAICS33](http://asu.edu/semantics/SUDOKN/NAICS33)






```mermaid
 classDiagram
    class SudoknNAICS33
    click SudoknNAICS33 href "../SudoknNAICS33"
      SudoknNAICSClassifier <|-- SudoknNAICS33
        click SudoknNAICSClassifier href "../SudoknNAICSClassifier"
      

      SudoknNAICS33 <|-- SudoknNAICS331
        click SudoknNAICS331 href "../SudoknNAICS331"
      SudoknNAICS33 <|-- SudoknNAICS332
        click SudoknNAICS332 href "../SudoknNAICS332"
      SudoknNAICS33 <|-- SudoknNAICS333
        click SudoknNAICS333 href "../SudoknNAICS333"
      SudoknNAICS33 <|-- SudoknNAICS334
        click SudoknNAICS334 href "../SudoknNAICS334"
      SudoknNAICS33 <|-- SudoknNAICS335
        click SudoknNAICS335 href "../SudoknNAICS335"
      SudoknNAICS33 <|-- SudoknNAICS336
        click SudoknNAICS336 href "../SudoknNAICS336"
      SudoknNAICS33 <|-- SudoknNAICS337
        click SudoknNAICS337 href "../SudoknNAICS337"
      SudoknNAICS33 <|-- SudoknNAICS339
        click SudoknNAICS339 href "../SudoknNAICS339"
      
      
      SudoknNAICS33 : sudokn_hasNAICSCodeValue
        
          
    
    
    SudoknNAICS33 --> "0..1" Integer : sudokn_hasNAICSCodeValue
    click Integer href "../Integer"

        
      SudoknNAICS33 : sudokn_hasNAICSTextValue
        
          
    
    
    SudoknNAICS33 --> "0..1" String : sudokn_hasNAICSTextValue
    click String href "../String"

        
      
```





## Inheritance
* [IoInformationContentEntity](../classes/IoInformationContentEntity.md)
    * [SudoknClassifier](../classes/SudoknClassifier.md)
        * [SudoknNAICSClassifier](../classes/SudoknNAICSClassifier.md)
            * **SudoknNAICS33**
                * [SudoknNAICS331](../classes/SudoknNAICS331.md)
                * [SudoknNAICS332](../classes/SudoknNAICS332.md)
                * [SudoknNAICS333](../classes/SudoknNAICS333.md)
                * [SudoknNAICS334](../classes/SudoknNAICS334.md)
                * [SudoknNAICS335](../classes/SudoknNAICS335.md)
                * [SudoknNAICS336](../classes/SudoknNAICS336.md)
                * [SudoknNAICS337](../classes/SudoknNAICS337.md)
                * [SudoknNAICS339](../classes/SudoknNAICS339.md)



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
name: sudokn_NAICS33
title: NAICS sector 33
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_NAICSClassifier
class_uri: sudokn:NAICS33

```
</details>

### Induced

<details>

```yaml
name: sudokn_NAICS33
title: NAICS sector 33
from_schema: okns:sudokn-kg
rank: 1000
is_a: sudokn_NAICSClassifier
attributes:
  sudokn_hasNAICSTextValue:
    name: sudokn_hasNAICSTextValue
    title: has NAICS text value
    from_schema: okns:sudokn-kg
    rank: 1000
    domain: sudokn_NAICSClassifier
    slot_uri: sudokn:hasNAICSTextValue
    alias: sudokn_hasNAICSTextValue
    owner: sudokn_NAICS33
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
    owner: sudokn_NAICS33
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
class_uri: sudokn:NAICS33

```
</details>