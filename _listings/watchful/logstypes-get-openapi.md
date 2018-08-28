---
swagger: "2.0"
x-collection-name: Watchful
x-complete: 0
info:
  title: Watchful Get The List Of Log Types
  description: Returns a list of log types
  version: 1.0.0
host: watchful.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /logs:
    get:
      summary: Get A List Of Logs
      description: Returns a list of logs
      operationId: logs.get
      x-api-path-slug: logs-get
      parameters:
      - in: query
        name: fields
        description: 'Fields to return separate by comas: name,id'
      - in: query
        name: from
        description: Logs after this date, format YYYY-MM-DD HH:MM:SS
      - in: query
        name: limit
        description: Number of object to return (max 100, default 25)
      - in: query
        name: limitstart
        description: Start of the return (default 0)
      - in: query
        name: log_entry
        description: Do a LIKE search, you can also use %
      - in: query
        name: log_type
        description: Type of the log
      - in: query
        name: order
        description: ORDER by this field separete by comas
      - in: query
        name: to
        description: Logs before this date, format YYYY-MM-DD HH:MM:SS
      responses:
        200:
          description: OK
      tags:
      - Logs
  /logs/export:
    get:
      summary: Get A CSV Or PDF File Contain The List Of Logs
      description: Returns a file contain the list of logs
      operationId: getExportLogs
      x-api-path-slug: logsexport-get
      parameters:
      - in: query
        name: enddate
        description: Logs before this date, format YYYY-MM-DD HH:MM:SS
      - in: query
        name: filter_type
        description: Type of the log
      - in: query
        name: format
        description: Format of exported file (PDF or CSV)
      - in: query
        name: limit
        description: Number of object to return (max 100, default 25)
      - in: query
        name: search
        description: Do a LIKE search, you can also use %
      - in: query
        name: site
        description: Site id of the log
      - in: query
        name: startdate
        description: Logs after this date, format YYYY-MM-DD HH:MM:SS
      - in: query
        name: startid
        description: Start of the return (default 0)
      responses:
        200:
          description: OK
      tags:
      - Logs
      - Export
  /logs/metadata:
    get:
      summary: Get The List Of Fields
      description: Returns a list of fields
      operationId: getFieldsLogs
      x-api-path-slug: logsmetadata-get
      responses:
        200:
          description: OK
      tags:
      - Logs
      - Metadata
  /logs/types:
    get:
      summary: Get The List Of Log Types
      description: Returns a list of log types
      operationId: getTypesLogs
      x-api-path-slug: logstypes-get
      responses:
        200:
          description: OK
      tags:
      - Logs
      - Types
  /logs/{id}:
    delete:
      summary: Delete A Specific Log
      description: Delete a specific log
      operationId: deleteLogById
      x-api-path-slug: logsid-delete
      parameters:
      - in: path
        name: id
        description: ID of log that needs to be deleted
      responses:
        200:
          description: OK
      tags:
      - Logs
      - Id
  /sites/{id}/logs:
    get:
      summary: Return Logs For A Specific Website
      description: Return logs for a specific website
      operationId: sites.id.logs.get
      x-api-path-slug: sitesidlogs-get
      parameters:
      - in: query
        name: fields
        description: 'Fields to return separate by comas: name,id'
      - in: query
        name: from
        description: Logs after this date, format YYYY-MM-DD HH:MM:SS
      - in: path
        name: id
        description: ID of the website
      - in: query
        name: limit
        description: Number of object to return (max 100, default 25)
      - in: query
        name: limitstart
        description: Start of the return (default 0)
      - in: query
        name: log_entry
        description: Do a LIKE search, you can also use %
      - in: query
        name: log_type
        description: Type of the log
      - in: query
        name: order
        description: ORDER by this field separete by comas
      - in: query
        name: to
        description: Logs before this date, format YYYY-MM-DD HH:MM:SS
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Id
      - Logs
    post:
      summary: Create A Custom Log For A Specific Website
      description: Create a custom log for a specific website
      operationId: CreateLog
      x-api-path-slug: sitesidlogs-post
      parameters:
      - in: body
        name: body
        description: JSON object Log (only type custom)
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID of the website
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Id
      - Logs
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