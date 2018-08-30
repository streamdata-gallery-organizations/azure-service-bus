{
  "info": {
    "name": "Azure Service Bus API Topics Delete",
    "_postman_id": "293ea1ae-cfa2-4afc-8006-006f8457101e",
    "description": "Deletes a topic from the specified namespace and resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "topics",
      "item": [
        {
          "id": "fb91024a-28af-4924-9c75-f63fd4aed87d",
          "name": "Topics_Delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ServiceBus/namespaces/:namespaceName/topics/:topicName"
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
                  "id": "topicName",
                  "value": "topicName",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a topic from the specified namespace and resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d0cf313-e9a7-456a-9ebc-3c2605159c17"
            }
          ]
        }
      ]
    }
  ]
}