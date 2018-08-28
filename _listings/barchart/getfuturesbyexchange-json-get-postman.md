{
  "info": {
    "name": "Barchart API Get Futures by Exchange",
    "_postman_id": "21a11719-21b4-48bd-866e-7716c48e9951",
    "description": "Receive all real-time or delayed, or end-of-day Futures data by exchange through a single onDemand query.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Futures",
      "item": [
        {
          "id": "42814448-7755-4ca5-acb3-c1e9bacc5b4b",
          "name": "getFuturesByExchange",
          "request": {
            "url": "http://marketdata.websol.barchart.com/getFuturesByExchange.json",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Receive all real-time or delayed, or end-of-day Futures data by exchange through a single onDemand query."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afb68f7b-aa9a-4b06-9974-16cd9017c8ce"
            }
          ]
        }
      ]
    }
  ]
}