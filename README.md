## Resources

Note: The API specs listed here are not complete specs. In most cases they are missing authentication, parameters, and return types. These are mostly to demonstrate what new endpoints might look like (such as the new search endpoints) and to demonstrate the layout of the API.

### V4
Proposed V4 API spec:
* [yaml](https://raw.githubusercontent.com/newswangerd/galaxy-api-v4/master/openapi%3A%20galaxy_ng_v4.yml)
* [swaggerui](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/newswangerd/galaxy-api-v4/master/openapi%3A%20galaxy_ng_v4.yml)
* [redoc](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/newswangerd/galaxy-api-v4/master/openapi%3A%20galaxy_ng_v4.yml)
* [koumoul](https://koumoul.com/openapi-viewer/?url=https://raw.githubusercontent.com/newswangerd/galaxy-api-v4/master/openapi%3A%20galaxy_ng_v4.yml)
* [mirindoc](https://mrin9.github.io/OpenAPI-Viewer/#/load/https%3A%2F%2Fraw.githubusercontent.com%2Falikins%2Fgalaxy_ng%2Fsync_model_46%2Fopenapi%2Fui_openapi.yaml)

[V4 Proposal and discussion](https://hackmd.io/x0NmCvqPSM6DBVW-6qIfsQ)

### V3

[Proposed refactored V3]:
* [yaml](https://raw.githubusercontent.com/newswangerd/galaxy-api-v4/master/refactored_v3.yaml)
* [swaggerui](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/newswangerd/galaxy-api-v4/master/refactored_v3.yaml)
* [redoc](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/newswangerd/galaxy-api-v4/master/refactored_v3.yaml)
* [koumoul](https://koumoul.com/openapi-viewer/?url=https://raw.githubusercontent.com/newswangerd/galaxy-api-v4/master/refactored_v3.yaml)
* [mirindoc](https://mrin9.github.io/OpenAPI-Viewer/#/load/https%3A%2F%2Fraw.githubusercontent.com%2newswangerd%2galaxy-api-v4%2master%2refactored_v3.yaml)

This proposal:
- Merges the new endpoints proposed in V4 into V3
- Deprecates the top level collection endpoints (/collections, /artifacts, /imports etc)
- Redirects or proxies the old top level collection endpoints to their `/plugin/ansible/` counterparts.
