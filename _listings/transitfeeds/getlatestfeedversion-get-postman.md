{
  "info": {
    "name": "TransitFeeds Retrieve the download URL for the latest version of a feed.",
    "_postman_id": "c0f2ea5f-6c0f-458d-8b02-c6599a1bf113",
    "description": "Once you have used `/getFeeds` to discover a feed's URL, you can use this endpoint to download its latest version from TranstiFeeds.\nIt will be unmodified in the original format from the provider.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Retrieve",
      "item": [
        {
          "id": "57f6fe13-1012-4a6f-9fe1-f906842dc819",
          "name": "getLatestFeedVersion",
          "request": {
            "url": "http://api.transitfeeds.com/v1/getLatestFeedVersion?feed=%7B%7D&key=%7B%7D",
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
            "description": "Once you have used `/getFeeds` to discover a feed's URL, you can use this endpoint to download its latest version from TranstiFeeds.\nIt will be unmodified in the original format from the provider."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac429566-9a20-4fc0-8fb3-788c062ede79"
            }
          ]
        }
      ]
    }
  ]
}