{
  "info": {
    "name": "AWS Data Pipeline API Activate Pipeline",
    "_postman_id": "211f2ee7-6c6a-4acd-93e4-8dca5f17a1cd",
    "description": "Validates the specified pipeline and starts processing pipeline tasks.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Pipeline",
      "item": [
        {
          "id": "ed4a49fd-546b-4c1f-a27c-f3bd83fa3f7d",
          "name": "activatePipeline",
          "request": {
            "url": "http://example.com/api/?Action=ActivatePipeline?parameterValues=parameterValues&pipelineId=pipelineId&startTimestamp=startTimestamp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Validates the specified pipeline and starts processing pipeline tasks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a84eb87-e912-450e-826a-b1d10b5763a8"
            }
          ]
        }
      ]
    }
  ]
}