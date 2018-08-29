---
swagger: "2.0"
x-collection-name: EVRYTHNG
x-complete: 1
info:
  title: EVRYTHNG
  description: the-evrythng-platform-is-a-cloud-platformasaservice-paas-for-storing-sharing-and-analyzing-data-generated-by-physical-objects--the-platform-gives-a-unique-and-permanent-digital-identity-also-known-as-adis-to-each-individual-object-and-allows-authorized-applications-and-users-to-access-it-via-rest-and-pubsub-mqtt-apis--visualisations-in-the-evrythng-dashboard-analytics-conditional-redirections-and-the-reactor-rules-engine-provide-means-to-add-intelligent-behavior-and-features-on-top-of-your-data-to-add-value-
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
  /auth/evrythng/users/{USER_ID}/validate:
    post:
      summary: /user/{id}/validate (A)
      description: APP validates a user (which can then login & out).
      operationId: AuthEvrythngUsersValidateByUSERIDPost
      x-api-path-slug: authevrythngusersuser-idvalidate-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: USER_ID
      responses:
        200:
          description: OK
      tags:
      - Auth
      - Evrythng
      - Users
      - USER
      - ID
      - Validate
---