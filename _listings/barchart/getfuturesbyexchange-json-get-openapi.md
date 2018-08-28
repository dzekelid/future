---
swagger: "2.0"
x-collection-name: Barchart
x-complete: 0
info:
  title: Barchart API Get Futures by Exchange
  description: Receive all real-time or delayed, or end-of-day Futures data by exchange
    through a single onDemand query.
  version: 1.0.0
host: marketdata.websol.barchart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /getFuturesByExchange.json:
    get:
      summary: Get Futures by Exchange
      description: Receive all real-time or delayed, or end-of-day Futures data by
        exchange through a single onDemand query.
      operationId: getFuturesByExchange
      x-api-path-slug: getfuturesbyexchange-json-get
      responses:
        200:
          description: OK
      tags:
      - Futures
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