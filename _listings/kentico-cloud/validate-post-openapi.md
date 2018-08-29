---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 0
info:
  title: Kentico Cloud Validate project content
  description: "Check your project's content items for issues, such as:\r\n\r\n* Content
    elements are [referencing](https://developer.kenticocloud.com/v1/reference#content-management-api-reference-object)
    non-existing objects.\r\n* Values of certain content elements do not meet the
    limitations set in content types.\r\n\r\nUse the endpoint after successfully importing
    content to your project."
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---