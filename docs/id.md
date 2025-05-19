

# Slot: id 



URI: [ex:id](https://example.org/id)
Alias: id

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Employee](Employee.md) | A person employed by an organization |  no  |
| [Person](Person.md) | A human being |  no  |







## Properties

* Range: [String](String.md)

* Required: True





## Identifier and Mapping Information







### Schema Source


* from schema: https://example.org/derived_schema




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | ex:id |
| native | ex:id |




## LinkML Source

<details>
```yaml
name: id
from_schema: https://example.org/derived_schema
rank: 1000
identifier: true
alias: id
owner: Person
domain_of:
- Person
range: string
required: true

```
</details>