{
  "info": {
    "name": "Predix Enterprise Connect Validate the EC service status",
    "_postman_id": "b475133f-e4d6-4671-ab70-65b8f0e1f859",
    "description": "Validate the EC API status",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "EC",
      "item": [
        {
          "id": "0d3ce38d-5fe9-4fbc-a9e2-2edc63bf9b19",
          "name": "get-your-ec-gateway-settings-details",
          "request": {
            "url": "http://ec-predix-service-osaka.run.aws-usw02-pr.ice.predix.io/v1/api/settings",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer *your_token",
                "disabled": false
              },
              {
                "key": "Predix-Zone-Id",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get your EC Gateway settings details"
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "ae3a7b25-873d-473a-afbb-01fe4c8f7edc"
            }
          ]
        }
      ]
    },
    {
      "name": "Validate",
      "item": [
        {
          "id": "2760c8e0-be50-47ed-ac0e-49247aa166d8",
          "name": "validate-the-oauth2-token-for-the-gateway-usage",
          "request": {
            "url": "http://ec-predix-service-osaka.run.aws-usw02-pr.ice.predix.io/v1/api/token/validate",
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer *your_token",
                "disabled": false
              },
              {
                "key": "Predix-Zone-Id",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Validate the oauth2 token for the gateway usage"
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "05e93bc3-e5e1-4dfb-a402-a27fdf9f3b0f"
            }
          ]
        },
        {
          "id": "c0f48f71-2a01-4d69-8710-3890eeb22c10",
          "name": "validate-the-ec-api-status",
          "request": {
            "url": "http://ec-predix-service-osaka.run.aws-usw02-pr.ice.predix.io/v1/health/check",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Validate the EC API status"
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "3d079bf4-42d1-41a7-9645-6fa852e8ed88"
            }
          ]
        }
      ]
    }
  ]
}