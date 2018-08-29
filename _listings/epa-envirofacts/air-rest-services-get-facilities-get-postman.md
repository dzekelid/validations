{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Clean Air Act Clean Air Act Facility Search",
    "_postman_id": "53449ad0-6340-420c-bee1-5ba11b494b59",
    "description": "Validates query search parameters and returns query identifier.  Use the responseset parameter to set the page size",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "3f83b76b-1f12-4980-9a0e-eeda13ebfb14",
      "name": "based-on-the-qid-obtained-from-a-get-facilities-or-get-facility-info-query-return-a-comma-sepated-va",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/air_rest_services.get_download?No Name=%7B%7D&output=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Based on the QID obtained from a get_facilities or get_facility_info query, return a comma sepated vaule (CSV) file of the facilities found."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "3921f26b-9b56-4b49-a8b2-4ab409f11a4b"
        }
      ]
    },
    {
      "id": "b39ccbfa-5eda-4430-864b-62b71b02ec17",
      "name": "validates-query-search-parameters-and-returns-query-identifier---use-the-responseset-parameter-to-se",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/air_rest_services.get_facilities?No Name=%7B%7D&output=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Validates query search parameters and returns query identifier.  Use the responseset parameter to set the page size"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "63ccd1c8-4a4b-4552-85af-d0a885e7676b"
        }
      ]
    }
  ]
}