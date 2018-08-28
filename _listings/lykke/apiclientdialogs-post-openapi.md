---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Client Dialogs
  version: 1.0.0
  description: Add api client dialogs.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/Auth/LogOut:
    post:
      summary: Add API Auth Logout
      description: Add api auth logout.
      operationId: ApiAuthLogOutPost
      x-api-path-slug: apiauthlogout-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Auth
      - Logout
  /api/ClientLog:
    post:
      summary: Add API Clientlog
      description: Add api clientlog.
      operationId: ApiClientLogPost
      x-api-path-slug: apiclientlog-post
      parameters:
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Clientlog
  /api/client/Dialogs:
    get:
      summary: Get API Client Dialogs
      description: Get api client dialogs.
      operationId: ApiClientDialogsGet
      x-api-path-slug: apiclientdialogs-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Client
      - Dialogs
    post:
      summary: Add API Client Dialogs
      description: Add api client dialogs.
      operationId: ApiClientDialogsPost
      x-api-path-slug: apiclientdialogs-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Client
      - Dialogs
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