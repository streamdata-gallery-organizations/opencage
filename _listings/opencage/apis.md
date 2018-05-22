---
name: OpenCage
x-slug: opencage
description: OpenCage Geocoder. Easy, Open, Worldwide, Affordable. An API to convert
  coordinates to and from places.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCage-Geocoder.png
x-kinRank: "9"
x-alexaRank: ""
tags: OpenCage
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencage/master/_listings/opencage/apis.md
specificationVersion: "0.14"
apis:
- name: OpenCage Geocode Query
  x-api-slug: opencage
  description: Geocode a query
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCage-Geocoder.png
  humanURL: http://www.opencagedata.com/
  baseURL: https://api.opencagedata.com/v1///v{version}/{format}
  tags: Geo, Encoding, Query
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencage/master/_listings/opencage/vversionformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencage/master/_listings/opencage/vversionformat-get-openapi.md
- name: OpenCage
  x-api-slug: opencage
  description: OpenCage Geocoder. Easy, Open, Worldwide, Affordable. An API to convert
    coordinates to and from places.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCage-Geocoder.png
  humanURL: http://www.opencagedata.com/
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
  url: http://www.opencagedata.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---