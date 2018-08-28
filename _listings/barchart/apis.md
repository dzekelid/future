---
name: Barchart
x-slug: barchart
description: Barchart.com is the leading provider of intraday stock and commodities
  real-time or delayed charts with powerful indicators and technical analysis.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21632-www-barchart-com.jpg
x-kinRank: "7"
x-alexaRank: "15739"
tags: Future
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/future/master/_listings/barchart/apis.md
specificationVersion: "0.14"
apis:
- name: Barchart API Get Futures by Exchange
  x-api-slug: barchart-api
  description: Receive all real-time or delayed, or end-of-day Futures data by exchange
    through a single onDemand query.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21632-www-barchart-com.jpg
  humanURL: https://www.barchart.com
  baseURL: https://marketdata.websol.barchart.com////getFuturesByExchange.json
  tags: Futures
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/future/master/_listings/barchart/getfuturesbyexchange-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/future/master/_listings/barchart/getfuturesbyexchange-json-get-openapi.md
- name: Barchart API
  x-api-slug: barchart-api
  description: Barchart.com is the leading provider of intraday stock and commodities
    real-time or delayed charts with powerful indicators and technical analysis.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21632-www-barchart-com.jpg
  humanURL: https://www.barchart.com
  baseURL: https://marketdata.websol.barchart.com//
  tags: Future
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/future/master/_listings/barchart/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/barchart-com
- type: x-email
  url: solutions@barchart.com
- type: x-email
  url: careers@barchart.com
- type: x-email
  url: colleen.sheeren@barchart.com
- type: x-github
  url: https://github.com/barchart
- type: x-twitter
  url: https://twitter.com/Barchart
- type: x-website
  url: https://www.barchart.com
- type: x-websockets
  url: https://github.com/barchart/barchart-ondemand-client-js
- type: x-website
  url: http://www.barchart.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---