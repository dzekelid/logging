swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
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