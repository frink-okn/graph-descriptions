

# Class: Analysis Method (coso_AnalysisMethod)


_The analysis method used to identify the contaminant._







URI: [coso:AnalysisMethod](http://w3id.org/coso/v1/contaminoso#AnalysisMethod)






```mermaid
 classDiagram
    class CosoAnalysisMethod
    click CosoAnalysisMethod href "../CosoAnalysisMethod"
      SosaProcedure <|-- CosoAnalysisMethod
        click SosaProcedure href "../SosaProcedure"
      

      CosoAnalysisMethod <|-- HttpW3id.orgSawgraphV1Us-wqp#AnalyticalMethod
        click HttpW3id.orgSawgraphV1Us-wqp#AnalyticalMethod href "../HttpW3id.orgSawgraphV1Us-wqp#AnalyticalMethod"
      
      
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * [SosaProcedure](../classes/SosaProcedure.md)
        * **CosoAnalysisMethod**
            * [HttpW3id.orgSawgraphV1Us-wqp#AnalyticalMethod](../classes/HttpW3id.orgSawgraphV1Us-wqp#AnalyticalMethod.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_AnalysisMethod
description: The analysis method used to identify the contaminant.
title: Analysis Method
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_Procedure
class_uri: coso:AnalysisMethod

```
</details>

### Induced

<details>

```yaml
name: coso_AnalysisMethod
description: The analysis method used to identify the contaminant.
title: Analysis Method
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_Procedure
class_uri: coso:AnalysisMethod

```
</details>