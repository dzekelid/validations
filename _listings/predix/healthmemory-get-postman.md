{
  "info": {
    "name": "Predix Enterprise Connect Validate the EC service memory usage",
    "_postman_id": "ecf7e19b-4d8a-4e55-b399-ffcad0b77f23",
    "description": "Validate the EC gateway memory usage",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "EC",
      "item": [
        {
          "id": "f774ace6-7c00-40b8-80fd-297cd2537b8d",
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
              "id": "d5811fb7-db19-4a6d-a946-98e1513e9246"
            }
          ]
        }
      ]
    },
    {
      "name": "Validate",
      "item": [
        {
          "id": "2b30c3ce-4382-4ec3-beba-5f6d8c4c4735",
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
              "id": "e1c76b9e-13f8-4044-afc1-8bdcbf2ca8b3"
            }
          ]
        },
        {
          "id": "f696d1ca-1f65-4f2a-ac3d-5e52ef464e85",
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
              "id": "2dcb5fca-9294-44a7-b2f1-76c2d31b27a5"
            }
          ]
        },
        {
          "id": "1d26affa-0e07-4c3c-9a25-b857fa7e61b5",
          "name": "validate-the-ec-gateway-memory-usage",
          "request": {
            "url": "http://ec-predix-service-osaka.run.aws-usw02-pr.ice.predix.io/v1/health/memory",
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
            "description": "Validate the EC gateway memory usage"
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "1dc70723-fcf7-47cf-8950-ed72679e4ec7"
            }
          ]
        }
      ]
    }
  ]
}