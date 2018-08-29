---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get valid project name
  description: Validates a project name. If the name is invalid, an attempt is made
    to produce a valid name based on the supplied one. If no such valid name can be
    found, an empty string is returned.
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/licenseValidator:
    post:
      summary: Validate license
      description: |-
        Validates a Jira license.

        Typically used by the setup phase of the Jira application. Returns an object with a list of errors as key, value pairs if the license is not valid.
      operationId: com.atlassian.jira.rest.v2.license.LicenceValidator.validateLicense_post
      x-api-path-slug: api2licensevalidator-post
      responses:
        200:
          description: OK
      tags:
      - Validate
      - License
  /api/2/projectvalidate/key:
    get:
      summary: Validate project key
      description: Validates a project key.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectValidateResource.validateProjectKey_get
      x-api-path-slug: api2projectvalidatekey-get
      parameters:
      - in: query
        name: key
        description: the project key
      responses:
        200:
          description: OK
      tags:
      - Validate
      - Project
      - Key
  /api/2/projectvalidate/validProjectKey:
    get:
      summary: Get valid project key
      description: Validates the project key and generated a valid project key if
        the supplied key is invalid.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectValidateResource.getValidProjectKey_get
      x-api-path-slug: api2projectvalidatevalidprojectkey-get
      parameters:
      - in: query
        name: key
        description: the project key
      responses:
        200:
          description: OK
      tags:
      - Valid
      - Project
      - Key
  /api/2/projectvalidate/validProjectName:
    get:
      summary: Get valid project name
      description: Validates a project name. If the name is invalid, an attempt is
        made to produce a valid name based on the supplied one. If no such valid name
        can be found, an empty string is returned.
      operationId: com.atlassian.jira.rest.v2.issue.ProjectValidateResource.getValidProjectName_get
      x-api-path-slug: api2projectvalidatevalidprojectname-get
      parameters:
      - in: query
        name: name
        description: the project name
      responses:
        200:
          description: OK
      tags:
      - Valid
      - Project
      - Name
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