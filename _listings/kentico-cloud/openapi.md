---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 1
info:
  title: Kentico Cloud
  description: this-is-a-collection-of-resources-you-can-find-within-the-kentico-cloud-developer-hubhttpsdeveloper-kenticocloud-com--kentico-cloudhttpskenticocloud-com-is-a-cloudfirst-headless-cms-that-allows-you-to-distribute-content-to-any-channel-and-device-websites-mobile-devices-mixed-reality-devices-presentation-kiosks-etc--through-an-api-certain-apis-require-that-you-include-the-authorization-header--find-more-in-httpsdeveloper-kenticocloud-comreferenceauthentication-
  version: 1.0.0
host: deliver.kenticocloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /validate:
    post:
      summary: Validate project content
      description: "Check your project's content items for issues, such as:\r\n\r\n*
        Content elements are [referencing](https://developer.kenticocloud.com/v1/reference#content-management-api-reference-object)
        non-existing objects.\r\n* Values of certain content elements do not meet
        the limitations set in content types.\r\n\r\nUse the endpoint after successfully
        importing content to your project."
      operationId: ValidatePost
      x-api-path-slug: validate-post
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Validate
      - Project
      - Content
---