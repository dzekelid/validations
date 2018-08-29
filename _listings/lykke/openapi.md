---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/PubkeyAddressValidation:
    get:
      summary: Get API Pubkeyaddressvalation
      description: Get api pubkeyaddressvalation.
      operationId: ApiPubkeyAddressValidationGet
      x-api-path-slug: apipubkeyaddressvalidation-get
      parameters:
      - in: query
        name: pubkeyAddress
      responses:
        200:
          description: OK
      tags:
      - Pubkeyaddressvalation
---