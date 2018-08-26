---
name: TransitFeeds
x-slug: transitfeeds
description: The best source of open official public transit data. Maintained by @qzervaas
  + others
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26209-rta-service-alerts.jpg
x-kinRank: "7"
x-alexaRank: "558301"
tags: TransitFeeds
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transitfeeds/master/_listings/transitfeeds/apis.md
specificationVersion: "0.14"
apis:
- name: TransitFeeds API - Retrieve a list of locations.
  x-api-slug: getlocations-get
  description: |-
    Retrieve a list of locations. Each location (except for the root) has a parent location, and each
    location has zero or more child locations. This hierarchy is generally structured so countries contain
    states, states contain cities (although this typically depends on the country).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26209-rta-service-alerts.jpg
  humanURL: https://transitfeeds.com
  baseURL: https://api.transitfeeds.com//v1
  tags: Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transitfeeds/master/_listings/transitfeeds/getlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transitfeeds/master/_listings/transitfeeds/getlocations-get-openapi.md
- name: TransitFeeds API - Retrieve a list of feeds.
  x-api-slug: getfeeds-get
  description: |-
    Used this API to retrieve a list of feeds in the system. Doing so can be usedful to discover feed IDs that
    can be used in other API calls.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26209-rta-service-alerts.jpg
  humanURL: https://transitfeeds.com
  baseURL: https://api.transitfeeds.com//v1
  tags: Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transitfeeds/master/_listings/transitfeeds/getfeeds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transitfeeds/master/_listings/transitfeeds/getfeeds-get-openapi.md
- name: TransitFeeds API - Retrieve the download URL for the latest version of a feed.
  x-api-slug: getlatestfeedversion-get
  description: |-
    Once you have used `/getFeeds` to discover a feed's URL, you can use this endpoint to download its latest version from TranstiFeeds.
    It will be unmodified in the original format from the provider.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26209-rta-service-alerts.jpg
  humanURL: https://transitfeeds.com
  baseURL: https://api.transitfeeds.com//v1
  tags: Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transitfeeds/master/_listings/transitfeeds/getlatestfeedversion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transitfeeds/master/_listings/transitfeeds/getlatestfeedversion-get-openapi.md
- name: TransitFeeds API - Retrieve a list of versions of specified (or all) feeds.
  x-api-slug: getfeedversions-get
  description: |-
    This API call allows you to easily see every single feed update in the TranstiFeeds.com system. Since this can be quite
    long, it's also possible to filter this list by a single feed ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26209-rta-service-alerts.jpg
  humanURL: https://transitfeeds.com
  baseURL: https://api.transitfeeds.com//v1
  tags: Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transitfeeds/master/_listings/transitfeeds/getfeedversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transitfeeds/master/_listings/transitfeeds/getfeedversions-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://transavia.api.gallery.streamdata.io
- type: x-twitter
  url: https://twitter.com/TransitFeeds
- type: x-website
  url: https://transitfeeds.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---