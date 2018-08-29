---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 1
info:
  title: Compute Engine
  description: creates-and-runs-virtual-machines-on-google-cloud-platform-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /compute/v1/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/global/urlMaps/{urlMap}/validate:
    post:
      summary: Run Static Validation
      description: Runs static validation for the UrlMap. In particular, the tests
        of the provided UrlMap will be run. Calling this method does NOT create the
        UrlMap.
      operationId: compute.urlMaps.validate
      x-api-path-slug: projectglobalurlmapsurlmapvalidate-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: urlMap
        description: Name of the UrlMap resource to be validated as
      responses:
        200:
          description: OK
      tags:
      - Validation
---