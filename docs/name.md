

# Slot: name 



URI: [ex:name](https://example.org/name)
Alias: name

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
| self | ex:name |
| native | ex:name |




## LinkML Source

<details>
```yaml
name: name
from_schema: https://example.org/derived_schema
rank: 1000
alias: name
owner: Person
domain_of:
- Person
range: string
required: true

```
</details>