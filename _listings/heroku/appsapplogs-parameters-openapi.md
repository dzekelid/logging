---
swagger: "2.0"
x-collection-name: Heroku
x-complete: 0
info:
  title: Heroku Parameters Application Logs
  description: Parameters application logs.
  version: "1"
host: api.heroku.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apps/{app}/logs:
    parameters:
      summary: Parameters Application Logs
      description: Parameters application logs.
      operationId: parametersAppsAppLogs
      x-api-path-slug: appsapplogs-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Logs
    get:
      summary: Get Application Logs
      description: Get application logs.
      operationId: getAppsAppLogs
      x-api-path-slug: appsapplogs-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      - in: query
        name: logplex
        description: Use logplex to stream logs (always true)
      - in: query
        name: num
        description: The number of lines to display
      - in: query
        name: ps
        description: Only display logs from a given process
      - in: query
        name: source
        description: Only display logs from a given source
      - in: query
        name: tail
        description: '1: continually stream logs - : display only num logs'
      responses:
        200:
          description: OK
      tags:
      - Application
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