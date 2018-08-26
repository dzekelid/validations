---
swagger: "2.0"
x-collection-name: NetLicensing
x-complete: 1
info:
  title: NetLicensing
  description: the-labs64-netlicensing-restful-api-gives-you-access-to-netlicensings-core-features--you-authenticate-to-the-netlicensing-api-by-providing-your-account-credentials-or-simply-use-our-demo-account--find-out-more-about-labs64-netlicensing-at-netlicensing-io-
  termsOfService: https://www.labs64.com/legal/terms-of-service/netlicensing
  version: 2.x
host: go.netlicensing.io
basePath: /core/v2/rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /licensee/{licenseeNumber}/validate:
    post:
      summary: Validate licensee
      description: Validates active licenses of the licensee
      operationId: validateLicensee
      x-api-path-slug: licenseelicenseenumbervalidate-post
      parameters:
      - in: formData
        name: licenseeName
        description: Human-readable name for the auto-created licensee (will be set
          as custom Licensee property)
      - in: path
        name: licenseeNumber
        description: Licensee number with a maximum length of 1000 characters
      - in: formData
        name: licenseeSecret
        description: Licensee Secret key for licensee
      - in: formData
        name: productNumber
        description: Product number, must be provided when licensee auto-create is
          enabled (see also Product JavaDoc)
      responses:
        200:
          description: OK
      tags:
      - Licensee
      - LicenseeNumber
      - Validate
    get:
      summary: Validate licensee
      description: Validates active licenses of the licensee
      operationId: validateLicensee
      x-api-path-slug: licenseelicenseenumbervalidate-get
      parameters:
      - in: query
        name: licenseeName
        description: Human-readable name for the auto-created licensee (will be set
          as custom Licensee property)
      - in: path
        name: licenseeNumber
        description: Licensee number with a maximum length of 1000 characters
      - in: query
        name: productNumber
        description: Product number, must be provided when licensee auto-create is
          enabled (see also Product JavaDoc)
      responses:
        200:
          description: OK
      tags:
      - Licensee
      - LicenseeNumber
      - Validate
---