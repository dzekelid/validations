{
  "info": {
    "name": "Predix Enterprise Connect Validate the oauth2 token",
    "_postman_id": "92ee1f4b-bd1d-4381-b695-311cc330c386",
    "description": "Validate the oauth2 token for the gateway usage",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "EC",
      "item": [
        {
          "id": "e9647ec5-c579-4e30-b757-2aec94c0e26f",
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
              "id": "dd32d902-6dbb-4ca5-a548-8d3af29709cb"
            }
          ]
        }
      ]
    },
    {
      "name": "Validate",
      "item": [
        {
          "id": "fdf7656c-bd85-4652-bebe-a81d8891f426",
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
              "id": "fce195d7-0c10-4694-a2df-43a2e17d91a6"
            }
          ]
        }
      ]
    }
  ]
}