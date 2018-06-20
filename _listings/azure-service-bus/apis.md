---
name: Azure Service Bus
x-slug: azure-service-bus
description: Depend on Azure Service Bus when you need highly-reliable cloud messaging
  service between applications and services, even when one or more is offline. Available
  in every Azure region, this fully-managed service eliminates the burdens of server
  management and licensing. Asynchronous operations give you flexible, brokered messaging
  between client and server, along with structured first-in, first-out (FIFO) messaging,
  and publish/subscribe capabilities&mdash;excellent for tasks like order processing.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure Service Bus
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Service Bus API Operations List
  x-api-slug: azure-service-bus-api
  description: Lists all of the available ServiceBus REST API operations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////providers/Microsoft.ServiceBus/operations
  tags: Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/providersmicrosoft-servicebusoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/providersmicrosoft-servicebusoperations-get-openapi.md
- name: Azure Service Bus API Namespaces Check Name Availability
  x-api-slug: azure-service-bus-api
  description: Check the give namespace name availability.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.ServiceBus/CheckNameAvailability
  tags: Namespaces Name Availability
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidprovidersmicrosoft-servicebuschecknameavailability-post-openapi.md
- name: Azure Service Bus API Namespaces List By Subscription
  x-api-slug: azure-service-bus-api
  description: Gets all the available namespaces within the subscription, irrespective
    of the resource groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.ServiceBus/namespaces
  tags: Namespaces Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidprovidersmicrosoft-servicebusnamespaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidprovidersmicrosoft-servicebusnamespaces-get-openapi.md
- name: Azure Service Bus API Namespaces List By Resource Group
  x-api-slug: azure-service-bus-api
  description: Gets the available namespaces within a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces
  tags: Namespaces Resource Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespaces-get-openapi.md
- name: Azure Service Bus API Namespaces Create Or Update
  x-api-slug: azure-service-bus-api
  description: Creates or updates a service namespace. Once created, this namespace's
    resource manifest is immutable. This operation is idempotent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacename-put-openapi.md
- name: Azure Service Bus API Namespaces Delete
  x-api-slug: azure-service-bus-api
  description: Deletes an existing namespace. This operation also removes all associated
    resources under the namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacename-delete-openapi.md
- name: Azure Service Bus API Namespaces Get
  x-api-slug: azure-service-bus-api
  description: Gets a description for the specified namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacename-get-openapi.md
- name: Azure Service Bus API Namespaces Update
  x-api-slug: azure-service-bus-api
  description: Updates a service namespace. Once created, this namespace's resource
    manifest is immutable. This operation is idempotent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}
  tags: Namespaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacename-patch-openapi.md
- name: Azure Service Bus API Namespaces List Authorization Rules
  x-api-slug: azure-service-bus-api
  description: Gets the authorization rules for a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/AuthorizationRules
  tags: Namespaces Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrules-get-openapi.md
- name: Azure Service Bus API Namespaces Create Or Update Authorization Rule
  x-api-slug: azure-service-bus-api
  description: Creates or updates an authorization rule for a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}
  tags: Namespaces Authorization Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-put-openapi.md
- name: Azure Service Bus API Namespaces Delete Authorization Rule
  x-api-slug: azure-service-bus-api
  description: Deletes a namespace authorization rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}
  tags: Namespaces Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: Azure Service Bus API Namespaces Get Authorization Rule
  x-api-slug: azure-service-bus-api
  description: Gets an authorization rule for a namespace by rule name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}
  tags: Namespaces Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-get-openapi.md
- name: Azure Service Bus API Namespaces List Keys
  x-api-slug: azure-service-bus-api
  description: Gets the primary and secondary connection strings for the namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}/listKeys
  tags: Namespaces Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulenamelistkeys-post-openapi.md
- name: Azure Service Bus API Namespaces Regenerate Keys
  x-api-slug: azure-service-bus-api
  description: Regenerates the primary or secondary connection strings for the namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}/regenerateKeys
  tags: Namespaces Regenerate Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulenameregeneratekeys-post-openapi.md
- name: Azure Service Bus API Queues List All
  x-api-slug: azure-service-bus-api
  description: Gets the queues within a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeues-get-openapi.md
- name: Azure Service Bus API Queues Create Or Update
  x-api-slug: azure-service-bus-api
  description: Creates or updates a Service Bus queue. This operation is idempotent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues/{queueName}
  tags: Queues
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuename-put-openapi.md
- name: Azure Service Bus API Queues Delete
  x-api-slug: azure-service-bus-api
  description: Deletes a queue from the specified namespace in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues/{queueName}
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuename-delete-openapi.md
- name: Azure Service Bus API Queues Get
  x-api-slug: azure-service-bus-api
  description: Returns a description for the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues/{queueName}
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuename-get-openapi.md
- name: Azure Service Bus API Queues List Authorization Rules
  x-api-slug: azure-service-bus-api
  description: Gets all authorization rules for a queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues/{queueName}/authorizationRules
  tags: Queues Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrules-get-openapi.md
- name: Azure Service Bus API Queues Create Or Update Authorization Rule
  x-api-slug: azure-service-bus-api
  description: Creates an authorization rule for a queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues/{queueName}/authorizationRules/{authorizationRuleName}
  tags: Queues Authorization Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrulesauthorizationrulename-put-openapi.md
- name: Azure Service Bus API Queues Delete Authorization Rule
  x-api-slug: azure-service-bus-api
  description: Deletes a queue authorization rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues/{queueName}/authorizationRules/{authorizationRuleName}
  tags: Queues Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: Azure Service Bus API Queues Get Authorization Rule
  x-api-slug: azure-service-bus-api
  description: Gets an authorization rule for a queue by rule name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues/{queueName}/authorizationRules/{authorizationRuleName}
  tags: Queues Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrulesauthorizationrulename-get-openapi.md
- name: Azure Service Bus API Queues List Keys
  x-api-slug: azure-service-bus-api
  description: Primary and secondary connection strings to the queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues/{queueName}/authorizationRules/{authorizationRuleName}/ListKeys
  tags: Queues Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrulesauthorizationrulenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrulesauthorizationrulenamelistkeys-post-openapi.md
- name: Azure Service Bus API Queues Regenerate Keys
  x-api-slug: azure-service-bus-api
  description: Regenerates the primary or secondary connection strings to the queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues/{queueName}/authorizationRules/{authorizationRuleName}/regenerateKeys
  tags: Queues Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrulesauthorizationrulenameregeneratekeys-post-openapi.md
- name: Azure Service Bus API Topics List All
  x-api-slug: azure-service-bus-api
  description: Gets all the topics in a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics
  tags: Topics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopics-get-openapi.md
- name: Azure Service Bus API Topics Create Or Update
  x-api-slug: azure-service-bus-api
  description: Creates a topic in the specified namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}
  tags: Topics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicname-put-openapi.md
- name: Azure Service Bus API Topics Delete
  x-api-slug: azure-service-bus-api
  description: Deletes a topic from the specified namespace and resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}
  tags: Topics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicname-delete-openapi.md
- name: Azure Service Bus API Topics Get
  x-api-slug: azure-service-bus-api
  description: Returns a description for the specified topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}
  tags: Topics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicname-get-openapi.md
- name: Azure Service Bus API Topics List Authorization Rules
  x-api-slug: azure-service-bus-api
  description: Gets authorization rules for a topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/authorizationRules
  tags: Topics Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrules-get-openapi.md
- name: Azure Service Bus API Topics Create Or Update Authorization Rule
  x-api-slug: azure-service-bus-api
  description: Creates an authorizatio rule for the specified topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/authorizationRules/{authorizationRuleName}
  tags: Topics Authorization Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrulesauthorizationrulename-put-openapi.md
- name: Azure Service Bus API Topics Get Authorization Rule
  x-api-slug: azure-service-bus-api
  description: Returns the specified authorization rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/authorizationRules/{authorizationRuleName}
  tags: Topics Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrulesauthorizationrulename-get-openapi.md
- name: Azure Service Bus API Topics Delete Authorization Rule
  x-api-slug: azure-service-bus-api
  description: Deletes a topic authorization rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/authorizationRules/{authorizationRuleName}
  tags: Topics Authorization Rule
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: Azure Service Bus API Topics List Keys
  x-api-slug: azure-service-bus-api
  description: Gets the primary and secondary connection strings for the topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/authorizationRules/{authorizationRuleName}/ListKeys
  tags: Topics Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrulesauthorizationrulenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrulesauthorizationrulenamelistkeys-post-openapi.md
- name: Azure Service Bus API Topics Regenerate Keys
  x-api-slug: azure-service-bus-api
  description: Regenerates primary or secondary connection strings for the topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/authorizationRules/{authorizationRuleName}/regenerateKeys
  tags: Topics Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrulesauthorizationrulenameregeneratekeys-post-openapi.md
- name: Azure Service Bus API Subscriptions List All
  x-api-slug: azure-service-bus-api
  description: List all the subscriptions under a specified topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/subscriptions
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnamesubscriptions-get-openapi.md
- name: Azure Service Bus API Subscriptions Create Or Update
  x-api-slug: azure-service-bus-api
  description: Creates a topic subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/subscriptions/{subscriptionName}
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnamesubscriptionssubscriptionname-put-openapi.md
- name: Azure Service Bus API Subscriptions Delete
  x-api-slug: azure-service-bus-api
  description: Deletes a subscription from the specified topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/subscriptions/{subscriptionName}
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnamesubscriptionssubscriptionname-delete-openapi.md
- name: Azure Service Bus API Subscriptions Get
  x-api-slug: azure-service-bus-api
  description: Returns a subscription description for the specified topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/subscriptions/{subscriptionName}
  tags: Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnamesubscriptionssubscriptionname-get-openapi.md
- name: Azure Service Bus API
  x-api-slug: azure-service-bus-api
  description: Depend on Azure Service Bus when you need highly-reliable cloud messaging
    service between applications and services, even when one or more is offline. Available
    in every Azure region, this fully-managed service eliminates the burdens of server
    management and licensing. Asynchronous operations give you flexible, brokered
    messaging between client and server, along with structured first-in, first-out
    (FIFO) messaging, and publish/subscribe capabilities&mdash;excellent for tasks
    like order processing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com//
  tags: Azure Service Bus
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-service-bus/master/_listings/azure-service-bus/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/service-bus/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/service-bus/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/service-bus/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/service-bus/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---