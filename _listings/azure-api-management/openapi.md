swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 1
info:
  title: ApiManagementClient
  description: use-these-rest-apis-for-performing-operations-on-user-entity-in-azure-api-management-deployment--the-user-entity-in-api-management-represents-the-developers-that-call-the-apis-of-the-products-to-which-they-are-subscribed-
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers
  : get:
      summary: Loggers ListByService
      description: Lists a collection of loggers in the specified service instance.
      operationId: Loggers_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggers-get
      parameters:
      - in: query
        name: $filter
        description: '| Field | Supported operators    | Supported functions                         ||-------|------------------------|---------------------------------------------||
          id    | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith
          || type  | eq                     |                                             |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Loggers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/loggers/{loggerid}
  : get:
      summary: Loggers Get
      description: Gets the details of the logger specified by its identifier.
      operationId: Loggers_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Loggers
    put:
      summary: Loggers CreateOrUpdate
      description: Creates or Updates a logger.
      operationId: Loggers_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Loggers
    patch:
      summary: Loggers Update
      description: Updates an existing logger.
      operationId: Loggers_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-patch
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the logger to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Loggers
    delete:
      summary: Loggers Delete
      description: Deletes the specified logger.
      operationId: Loggers_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameloggersloggerid-delete
      parameters:
      - in: header
        name: If-Match
        description: The entity state (Etag) version of the logger to delete
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Loggers