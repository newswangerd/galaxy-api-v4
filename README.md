## Resources

Note: The API specs listed here are not complete specs. In most cases they are missing authentication, parameters, and return types. These are mostly to demonstrate what new endpoints might look like (such as the new search endpoints) and to demonstrate the layout of the API.

### V4
[Proposed V4 API Spec](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/newswangerd/galaxy-api-v4/master/openapi%3A%20galaxy_ng_v4.yml).

[V4 Proposal and discussion](https://hackmd.io/x0NmCvqPSM6DBVW-6qIfsQ)

### V3

[Proposed refactored V3](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/newswangerd/galaxy-api-v4/master/refactored_v3.yaml).

This proposal:
- Merges the new endpoints proposed in V4 into V3
- Deprecates the top level collection endpoints (/collections, /artifacts, /imports etc)
- Redirects or proxies the old top level collection endpoints to their `/plugin/ansible/` counterparts.