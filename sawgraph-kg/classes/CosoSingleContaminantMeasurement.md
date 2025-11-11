

# Class: Single Contaminant Measurement (coso_SingleContaminantMeasurement)


_The result of an observation about a contaminant that is a single measurement, i.e. a single contaminant at one location from one sample._







URI: [coso:SingleContaminantMeasurement](http://w3id.org/coso/v1/contaminoso#SingleContaminantMeasurement)






```mermaid
 classDiagram
    class CosoSingleContaminantMeasurement
    click CosoSingleContaminantMeasurement href "../CosoSingleContaminantMeasurement"
      SosaResult <|-- CosoSingleContaminantMeasurement
        click SosaResult href "../SosaResult"
      

      CosoSingleContaminantMeasurement <|-- HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration
        click HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration href "../HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration"
      
      
      
```





## Inheritance
* [SosaResult](../classes/SosaResult.md)
    * **CosoSingleContaminantMeasurement**
        * [HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_SingleContaminantMeasurement
description: The result of an observation about a contaminant that is a single measurement,
  i.e. a single contaminant at one location from one sample.
title: Single Contaminant Measurement
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_Result
class_uri: coso:SingleContaminantMeasurement

```
</details>

### Induced

<details>

```yaml
name: coso_SingleContaminantMeasurement
description: The result of an observation about a contaminant that is a single measurement,
  i.e. a single contaminant at one location from one sample.
title: Single Contaminant Measurement
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_Result
class_uri: coso:SingleContaminantMeasurement

```
</details>