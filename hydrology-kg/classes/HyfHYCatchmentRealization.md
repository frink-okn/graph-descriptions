

# Class: HyfHYCatchmentRealization





URI: [hyf:/HY_CatchmentRealization](https://www.opengis.net/def/schema/hy_features/hyf/HY_CatchmentRealization)






```mermaid
 classDiagram
    class HyfHYCatchmentRealization
    click HyfHYCatchmentRealization href "../HyfHYCatchmentRealization"
      OwlThing <|-- HyfHYCatchmentRealization
        click OwlThing href "../OwlThing"
      

      HyfHYCatchmentRealization <|-- HyfHYFlowPath
        click HyfHYFlowPath href "../HyfHYFlowPath"
      
      
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * **HyfHYCatchmentRealization**
        * [HyfHYFlowPath](../classes/HyfHYFlowPath.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) | [hyf__downstreamFlowPathTC](../slots/hyf__downstreamFlowPathTC.md) | any_of[range] | [HyfHYCatchmentRealization](../classes/HyfHYCatchmentRealization.md) |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) | [hyf__downstreamFlowPath](../slots/hyf__downstreamFlowPath.md) | any_of[range] | [HyfHYCatchmentRealization](../classes/HyfHYCatchmentRealization.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: hyf__HY_CatchmentRealization
from_schema: okns:hydrology-kg
exact_mappings:
- https://www.opengis.net/def/schema/hy_features/hyf/HY_CatchmentRealization
rank: 1000
is_a: owl_Thing
class_uri: hyf:/HY_CatchmentRealization

```
</details>

### Induced

<details>

```yaml
name: hyf__HY_CatchmentRealization
from_schema: okns:hydrology-kg
exact_mappings:
- https://www.opengis.net/def/schema/hy_features/hyf/HY_CatchmentRealization
rank: 1000
is_a: owl_Thing
class_uri: hyf:/HY_CatchmentRealization

```
</details>