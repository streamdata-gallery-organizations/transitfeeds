{
  "info": {
    "name": "TransitFeeds Retrieve a list of locations.",
    "_postman_id": "7269055a-8354-4088-a171-eafbabb76548",
    "description": "Retrieve a list of locations. Each location (except for the root) has a parent location, and each\nlocation has zero or more child locations. This hierarchy is generally structured so countries contain\nstates, states contain cities (although this typically depends on the country).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Retrieve",
      "item": [
        {
          "id": "d26a3ab2-9eaf-4930-9102-47f8b3990d7b",
          "name": "getLocations",
          "request": {
            "url": "http://api.transitfeeds.com/v1/getLocations?key=%7B%7D",
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
            "description": "Retrieve a list of locations. Each location (except for the root) has a parent location, and each\nlocation has zero or more child locations. This hierarchy is generally structured so countries contain\nstates, states contain cities (although this typically depends on the country)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7cf0de23-c537-4db5-8207-27ca49e1865a"
            }
          ]
        }
      ]
    }
  ]
}