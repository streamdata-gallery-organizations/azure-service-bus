{
  "info": {
    "name": "Azure Service Bus API Operations List",
    "_postman_id": "dd6c3258-e3bf-4319-9081-b60d83afc4db",
    "description": "Lists all of the available ServiceBus REST API operations.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "operations",
      "item": [
        {
          "id": "9996cd3f-6654-4bfb-ad9c-a0417f9847a6",
          "name": "Operations_List",
          "request": {
            "url": "http://management.azure.com/providers/Microsoft.ServiceBus/operations?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the available ServiceBus REST API operations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f730a23-e29c-47b6-b2c9-9787a292e2f0"
            }
          ]
        }
      ]
    }
  ]
}