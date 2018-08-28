---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get Admin Parser Logs
  version: 1.0.0
  description: Get admin parser logs.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/admin/parser/log/error:
    post:
      summary: Post Admin Parser Log Error
      description: Post admin parser log error.
      operationId: postApiV1AdminParserLogError
      x-api-path-slug: apiv1adminparserlogerror-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Parser
      - Log
      - Error
  /api/v1/admin/parser/logs:
    get:
      summary: Get Admin Parser Logs
      description: Get admin parser logs.
      operationId: getApiV1AdminParserLogs
      x-api-path-slug: apiv1adminparserlogs-get
      parameters:
      - in: header
        name: Authorization
      - in: query
        name: request.from
      - in: query
        name: request.query
      - in: query
        name: request.to
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Parser
      - Logs
  /api/v1/request/requests/{requestId}/logs:
    get:
      summary: Get Request Requests Requestid Logs
      description: Get request requests requestid logs.
      operationId: getApiV1RequestRequestsRequestLogs
      x-api-path-slug: apiv1requestrequestsrequestidlogs-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: requestId
      responses:
        200:
          description: OK
      tags:
      - Request
      - Requests
      - Requestid
      - Logs
  /api/v1/account/logout:
    post:
      summary: Post Account Logout
      description: Post account logout.
      operationId: postApiV1AccountLogout
      x-api-path-slug: apiv1accountlogout-post
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Account
      - Logout
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