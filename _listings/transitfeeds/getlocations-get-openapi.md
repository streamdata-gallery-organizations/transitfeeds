---
swagger: "2.0"
x-collection-name: TransitFeeds
x-complete: 0
info:
  title: TransitFeeds Retrieve a list of locations.
  description: |-
    Retrieve a list of locations. Each location (except for the root) has a parent location, and each
    location has zero or more child locations. This hierarchy is generally structured so countries contain
    states, states contain cities (although this typically depends on the country).
  contact:
    name: TransitFeeds.com
    url: https://transitfeeds.com/issues
    email: support@transitfeeds.com
  version: 1.0.0
host: api.transitfeeds.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /getLocations:
    get:
      summary: Retrieve a list of locations.
      description: |-
        Retrieve a list of locations. Each location (except for the root) has a parent location, and each
        location has zero or more child locations. This hierarchy is generally structured so countries contain
        states, states contain cities (although this typically depends on the country).
      operationId: getLocations
      x-api-path-slug: getlocations-get
      parameters:
      - in: query
        name: key
        description: Your personal API key, used for authentication
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Locations
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---