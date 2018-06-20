---
swagger: "2.0"
x-collection-name: Barchart
x-complete: 1
info:
  title: Barchart API
  description: stock-futures-and-forex-quotes-and-historical-data-
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
---