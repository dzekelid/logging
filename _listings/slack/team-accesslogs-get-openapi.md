---
swagger: "2.0"
x-collection-name: Slack
x-complete: 0
info:
  title: Slack Get Logs
  description: Gets the access logs for the current team.
  version: 1.0.3
host: slack.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /team.accessLogs:
    get:
      summary: Get Logs
      description: Gets the access logs for the current team.
      operationId: team_accessLogs
      x-api-path-slug: team-accesslogs-get
      parameters:
      - in: query
        name: before
        description: End of time range of logs to include in results (inclusive)
      - in: query
        name: count
      - in: query
        name: page
      - in: query
        name: token
        description: Authentication token
      responses:
        200:
          description: OK
      tags:
      - Messaging
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