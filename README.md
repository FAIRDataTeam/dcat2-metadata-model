# dcat2-metadata-model
WIP repository for a dcat2 based FDP metadata model.

## [`fair-ap`](fair-ap.ttl)
- Application [profile](https://www.w3.org/TR/dx-prof/) for FAIR metadata.
- Extends [DCAT](https://www.w3.org/TR/vocab-dcat-2/).
- Links to the 'core' `SHACL` model for constraints.

## [`minimal-dataset-example`](minimal-dataset-example.ttl)
- Example instance data for the `fair-ap` profile.
- Hierarchy traversel using `dct:hasPart` through inferencing over the dcat subproperties `dcat:dataset`, `dcat:distribution`.

## [`wf-ext-ap`](wf-ext-ap.ttl)
- Application profile for a 'workflow extension'.
- Extends the `fair-ap` profile.
- Links to the extension `SHACL` model for constraints.

## [`minimal-workflow-example`](minimal-workflow-example.ttl)
- Example instance data for the `wf-ext-ap` profile.
- Hierarchy traversal using `dct:hasPart` through inferencing over the extension subproperties `wfx:hasWorkflow` and `wfx:hasSubcomponent`.
