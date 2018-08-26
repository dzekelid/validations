{
  "info": {
    "name": "Kentico Cloud Validate project content",
    "_postman_id": "c32fe74c-777c-49c5-be97-c2601e79e970",
    "description": "Check your project's content items for issues, such as:\r\n\r\n* Content elements are [referencing](https://developer.kenticocloud.com/v1/reference#content-management-api-reference-object) non-existing objects.\r\n* Values of certain content elements do not meet the limitations set in content types.\r\n\r\nUse the endpoint after successfully importing content to your project.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Validate",
      "item": [
        {
          "id": "6875d193-937d-4203-a5f2-916f8751b817",
          "name": "ValidatePost",
          "request": {
            "url": "http://deliver.kenticocloud.com/validate",
            "method": "POST",
            "header": [
              {
                "key": "Content-Type",
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
            "description": "Check your project's content items for issues, such as:\r\n\r\n* Content elements are [referencing](https://developer.kenticocloud.com/v1/reference#content-management-api-reference-object) non-existing objects.\r\n* Values of certain content elements do not meet the limitations set in content types.\r\n\r\nUse the endpoint after successfully importing content to your project."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db7f29c1-2fa2-4492-99dd-67cb9f450eca"
            }
          ]
        }
      ]
    }
  ]
}