# dcat2-metadata-model
WIP repository for a dcat2 based FDP metadata model.

- Model written in [SHACL](https://www.w3.org/TR/shacl/), based on the [DCAT2 spec](https://www.w3.org/TR/vocab-dcat-2/).
- Cardinalities are a rough draft, by no means final.
- External shapes (`odrl:Policy`, `dct:Standard`, etc) are referred to by `sh:class` and not by `sh:node`.
- Text based literals are defined as `sh:Literal` instead of `xsd:string`.
- `dcat:Relationship` could be [used](https://www.w3.org/TR/vocab-dcat-2/#qualified-relationship) to define the relation between the (to be defined) `:RepositoryShape` resource and a `dcat:Catalog`.
- Can we call this a [DCAT Profile](https://www.w3.org/TR/vocab-dcat-2/#profiles)?
