---
swagger: "2.0"
x-collection-name: Azure Service Bus
x-complete: 0
info:
  title: Azure Service Bus API Namespaces Delete
  description: Deletes an existing namespace. This operation also removes all associated
    resources under the namespace.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /providers/Microsoft.ServiceBus/operations:
    get:
      summary: Operations List
      description: Lists all of the available ServiceBus REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoftservicebusoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
  /subscriptions/{subscriptionId}/providers/Microsoft.ServiceBus/CheckNameAvailability:
    post:
      summary: Namespaces Check Name Availability
      description: Check the give namespace name availability.
      operationId: Namespaces_CheckNameAvailability
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftservicebuschecknameavailability-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters to check availability of the given namespace name
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Namespaces Name Availability
  /subscriptions/{subscriptionId}/providers/Microsoft.ServiceBus/namespaces:
    get:
      summary: Namespaces List By Subscription
      description: Gets all the available namespaces within the subscription, irrespective
        of the resource groups.
      operationId: Namespaces_ListBySubscription
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftservicebusnamespaces-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Namespaces Subscription
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces:
    get:
      summary: Namespaces List By Resource Group
      description: Gets the available namespaces within a resource group.
      operationId: Namespaces_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicebusnamespaces-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Namespaces Resource Group
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}:
    put:
      summary: Namespaces Create Or Update
      description: Creates or updates a service namespace. Once created, this namespace's
        resource manifest is immutable. This operation is idempotent.
      operationId: Namespaces_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicebusnamespacesnamespacename-put
      parameters:
      - in: path
        name: namespaceName
        description: The namespace name
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to create a namespace resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Namespaces
    delete:
      summary: Namespaces Delete
      description: Deletes an existing namespace. This operation also removes all
        associated resources under the namespace.
      operationId: Namespaces_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftservicebusnamespacesnamespacename-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Namespaces
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