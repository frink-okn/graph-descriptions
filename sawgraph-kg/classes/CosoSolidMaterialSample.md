

# Class: Solid Material Sample (coso_SolidMaterialSample)





URI: [coso:SolidMaterialSample](http://w3id.org/coso/v1/contaminoso#SolidMaterialSample)






```mermaid
 classDiagram
    class CosoSolidMaterialSample
    click CosoSolidMaterialSample href "../CosoSolidMaterialSample"
      CosoMaterialSample <|-- CosoSolidMaterialSample
        click CosoMaterialSample href "../CosoMaterialSample"
      

      CosoSolidMaterialSample <|-- CosoSedimentSample
        click CosoSedimentSample href "../CosoSedimentSample"
      CosoSolidMaterialSample <|-- CosoSolidWasteSample
        click CosoSolidWasteSample href "../CosoSolidWasteSample"
      
      
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * [SosaSample](../classes/SosaSample.md)
        * [CosoMaterialSample](../classes/CosoMaterialSample.md)
            * **CosoSolidMaterialSample**
                * [CosoSedimentSample](../classes/CosoSedimentSample.md)
                * [CosoSolidWasteSample](../classes/CosoSolidWasteSample.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_SolidMaterialSample
title: Solid Material Sample
from_schema: okns:sawgraph-kg
rank: 1000
is_a: coso_MaterialSample
class_uri: coso:SolidMaterialSample

```
</details>

### Induced

<details>

```yaml
name: coso_SolidMaterialSample
title: Solid Material Sample
from_schema: okns:sawgraph-kg
rank: 1000
is_a: coso_MaterialSample
class_uri: coso:SolidMaterialSample

```
</details>