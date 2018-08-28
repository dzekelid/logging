---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Create a log entry.
  description: Create a log entry..
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/delete_log:
    get:
      summary: Search the delete log
      description: Searches the delete log.
      operationId: getRestDeleteLog
      x-api-path-slug: restdelete-log-get
      parameters:
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: referenceType
        description: The type of deleted record
      - in: query
        name: updatedBetween
        description: Filter restricts the list of results to deleteLogs updated during
          the specified period
      - in: query
        name: userId
        description: The ID of the user who deleted the record
      responses:
        200:
          description: OK
      tags:
      - Search
      - Delete
      - Log
  /rest/logs:
    post:
      summary: Create a log entry.
      description: Create a log entry..
      operationId: postRestLogs
      x-api-path-slug: restlogs-post
      parameters:
      - in: body
        name: /rest/logs
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Log
      - Entry
  /rest/logs/{id}:
    get:
      summary: Get Log entry by ID.
      description: Get log entry by id..
      operationId: getRestLogs
      x-api-path-slug: restlogsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Log
      - Entry
      - By
      - ID
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