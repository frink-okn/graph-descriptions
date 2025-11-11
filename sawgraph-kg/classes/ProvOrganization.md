

# Class: Organization (prov_Organization)


_An organization is a social or legal institution such as a company, society, etc._






This class occurs 77 times.


URI: [prov:Organization](http://www.w3.org/ns/prov#Organization)






```mermaid
 classDiagram
    class ProvOrganization
    click ProvOrganization href "../ProvOrganization"
      ProvAgent <|-- ProvOrganization
        click ProvAgent href "../ProvAgent"
      

      ProvOrganization <|-- HttpW3id.orgSawgraphV1Us-wqp#Organization
        click HttpW3id.orgSawgraphV1Us-wqp#Organization href "../HttpW3id.orgSawgraphV1Us-wqp#Organization"
      
      
      
```





## Inheritance
* [ProvAgent](../classes/ProvAgent.md)
    * **ProvOrganization**
        * [HttpW3id.orgSawgraphV1Us-wqp#Organization](../classes/HttpW3id.orgSawgraphV1Us-wqp#Organization.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: prov_Organization
description: An organization is a social or legal institution such as a company, society,
  etc.
title: Organization
from_schema: okns:prov
source: http://www.w3.org/ns/prov-o#
is_a: prov_Agent
class_uri: prov:Organization

```
</details>

### Induced

<details>

```yaml
name: prov_Organization
description: An organization is a social or legal institution such as a company, society,
  etc.
title: Organization
from_schema: okns:prov
source: http://www.w3.org/ns/prov-o#
is_a: prov_Agent
class_uri: prov:Organization

```
</details>