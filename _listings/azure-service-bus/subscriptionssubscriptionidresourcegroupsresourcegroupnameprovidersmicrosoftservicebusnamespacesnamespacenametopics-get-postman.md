{
  "info": {
    "name": "Azure Service Bus API Topics List All",
    "_postman_id": "2c717078-b0fe-432b-b2f1-d602dfc34428",
    "description": "Gets all the topics in a namespace.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "topics",
      "item": [
        {
          "id": "47c20b23-1311-41a1-bbda-feaa81300128",
          "name": "Topics_ListAll",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ServiceBus/namespaces/:namespaceName/topics"
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
            "description": "Gets all the topics in a namespace"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7deaba1-5bf0-4d33-85e4-894c92b9f80a"
            }
          ]
        }
      ]
    }
  ]
}