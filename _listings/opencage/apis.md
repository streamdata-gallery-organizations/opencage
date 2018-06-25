---
name: OpenCage
x-slug: opencage
description: An easy-to-use forward and reverse geocoding API. Worldwide coverage.
  Affordable, predictable pricing. Open data.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2956-opencage.jpg
x-kinRank: "9"
x-alexaRank: "1026215"
tags: OpenCage
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencage/master/_listings/opencage/apis.md
specificationVersion: "0.14"
apis:
- name: Open Cage Geocoder Geocode
  x-api-slug: open-cage-geocoder
  description: geocode a query
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2956-opencage.jpg
  humanURL: http://opencagedata.com
  baseURL: https://api.opencagedata.com//geocode//v{version}/{format}
  tags: Geocode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencage/master/_listings/opencage/vversionformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencage/master/_listings/opencage/vversionformat-get-openapi.md
- name: Open Cage Geocoder
  x-api-slug: open-cage-geocoder
  description: An easy-to-use forward and reverse geocoding API. Worldwide coverage.
    Affordable, predictable pricing. Open data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2956-opencage.jpg
  humanURL: http://opencagedata.com
  baseURL: https://api.opencagedata.com//geocode
  tags: OpenCage
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencage/master/_listings/opencage/openapi.md
- name: OpenCage Geocode Query
  x-api-slug: opencage
  description: Geocode a query
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2956-opencage.jpg
  humanURL: http://opencagedata.com
  baseURL: https://api.opencagedata.com/v1///v{version}/{format}
  tags: Geo, Encoding, Query
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencage/master/_listings/opencage/vversionformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencage/master/_listings/opencage/vversionformat-get-openapi.md
- name: OpenCage
  x-api-slug: opencage
  description: An easy-to-use forward and reverse geocoding API. Worldwide coverage.
    Affordable, predictable pricing. Open data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2956-opencage.jpg
  humanURL: http://opencagedata.com
  baseURL: https://api.opencagedata.com/v1/
  tags: OpenCage
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencage/master/_listings/opencage/openapi.md
x-common:
- type: x-base
  url: http://api.opencagedata.com/
- type: x-blog
  url: http://blog.opencagedata.com/
- type: x-blog-rss
  url: http://blog.opencagedata.com/rss
- type: x-github
  url: https://github.com/opencagedata
- type: x-pricing
  url: https://geocoder.opencagedata.com/pricing
- type: x-twitter
  url: https://twitter.com/opencagedata
- type: x-website
  url: http://opencagedata.com
- type: x-website
  url: http://www.opencagedata.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---