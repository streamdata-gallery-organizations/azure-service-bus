{
  "info": {
    "name": "Azure Service Bus API Queues Get",
    "_postman_id": "93b81032-b66c-406b-b869-32b2311d6f8f",
    "description": "Returns a description for the specified queue.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "queues",
      "item": [
        {
          "id": "9d728da6-d494-4813-8b13-c27f37849793",
          "name": "Queues_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ServiceBus/namespaces/:namespaceName/queues/:queueName"
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
                },
                {
                  "id": "queueName",
                  "value": "queueName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description for the specified queue"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fcc29abf-dbef-4b04-b128-9e4841977e29"
            }
          ]
        }
      ]
    }
  ]
}