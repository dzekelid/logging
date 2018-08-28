swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost
  version: 1.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /logs:
    post:
      summary: Add log message
      description: |-
        Add log messages to the server logs.
        ##### Permissions
        Users with `manage_system` permission can log ERROR or DEBUG messages.
        Logged in users can log ERROR or DEBUG messages when `ServiceSettings.EnableDeveloper` is `true` or just DEBUG messages when `false`.
        Non-logged in users can log ERROR or DEBUG messages when `ServiceSettings.EnableDeveloper` is `true` and cannot log when `false`.
      operationId: add-log-messages-to-the-server-logs-permissionsusers-with-manage-system-permission-can-log-error-or-
      x-api-path-slug: logs-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Log
      - Message
    get:
      summary: Get logs
      description: |-
        Get a page of server logs, selected with `page` and `logs_per_page` query parameters.
        ##### Permissions
        Must have `manage_system` permission.
      operationId: get-a-page-of-server-logs-selected-with-page-and-logs-per-page-query-parameters-permissionsmust-have
      x-api-path-slug: logs-get
      parameters:
      - in: query
        name: logs_per_page
        description: The number of logs per page
      - in: query
        name: page
        description: The page to select
      responses:
        200:
          description: OK
      tags:
      - Logs