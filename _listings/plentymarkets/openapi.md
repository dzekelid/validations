---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/accounts/contacts/{contactId}/options/validate:
    get:
      summary: Validate a contact option by a given value
      description: validates a contact option by a given value
      operationId: getRestAccountsContactsContactOptionsValate
      x-api-path-slug: restaccountscontactscontactidoptionsvalidate-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Validate
      - Contact
      - Option
      - By
      - Given
      - Value
  /rest/orders/coupons/codes/{coupon}:
    post:
      summary: Validate a coupon
      description: Validates if a coupon code can be used for the specified items,
        contact ID, etc. The code must be specified. If the coupon code is invalid,
        a ValidationException will be thrown. If the coupon code is valid, a CouponCodeValidation
        object will be returned.
      operationId: postRestOrdersCouponsCodesCoupon
      x-api-path-slug: restorderscouponscodescoupon-post
      parameters:
      - in: body
        name: /rest/orders/coupons/codes/{coupon}
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: callFromScheduler
        description: Flag that indicates whether the validation is requested by a
          subscription order or not
      - in: query
        name: contactClass
        description: The contact class
      - in: query
        name: contactType
        description: The contact type
      - in: path
        name: coupon
      - in: query
        name: plentyId
        description: The plenty id
      - in: query
        name: shipToCountry
        description: The country of delivery
      - in: query
        name: taxIdNumber
        description: The tax id number
      responses:
        200:
          description: OK
      tags:
      - Validate
      - Coupon
---