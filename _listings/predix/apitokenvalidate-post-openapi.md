---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Enterprise Connect Validate the oauth2 token
  description: Validate the oauth2 token for the gateway usage
  version: 1.0.0
host: ec-predix-service-osaka.run.aws-usw02-pr.ice.predix.io
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/token/validate:
    post:
      summary: Validate the oauth2 token
      description: Validate the oauth2 token for the gateway usage
      operationId: validate-the-oauth2-token-for-the-gateway-usage
      x-api-path-slug: apitokenvalidate-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer *your_token
      - in: header
        name: Predix-Zone-Id
      responses:
        200:
          description: Successful response
      tags:
      - Validate
      - Oauth2
      - Token
  /health/check:
    get:
      summary: Validate the EC service status
      description: Validate the EC API status
      operationId: validate-the-ec-api-status
      x-api-path-slug: healthcheck-get
      responses:
        200:
          description: Successful response
      tags:
      - Validate
      - EC
      - Service
      - Status
  /health/memory:
    get:
      summary: Validate the EC service memory usage
      description: Validate the EC gateway memory usage
      operationId: validate-the-ec-gateway-memory-usage
      x-api-path-slug: healthmemory-get
      responses:
        200:
          description: Successful response
      tags:
      - Validate
      - EC
      - Service
      - Memory
      - Usage
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