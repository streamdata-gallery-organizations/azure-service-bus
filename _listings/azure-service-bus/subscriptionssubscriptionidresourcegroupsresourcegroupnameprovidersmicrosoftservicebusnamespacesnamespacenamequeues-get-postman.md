{
  "info": {
    "name": "Azure Service Bus API Queues List All",
    "_postman_id": "929d9e0c-0af2-417a-9047-2c9e98090bcc",
    "description": "Gets the queues within a namespace.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "queues",
      "item": [
        {
          "id": "0e2db82d-bb2a-4fb7-804d-56f823c99e45",
          "name": "Queues_ListAll",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ServiceBus/namespaces/:namespaceName/queues"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                },
                {
                  "id": "namespaceName",
                  "value": "namespaceName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the queues within a namespace"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f099260c-ec8d-4cd4-9eb5-e5f816213f12"
            }
          ]
        }
      ]
    }
  ]
}