---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation The logged in user is monitoring the
    current object or not (true / false)
  version: 1.0.0
  description: The logged in user is monitoring the current object or not (true /
    false).
basePath: /ctfrest/foundation/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /monitoring/users/myself/objects/{objectid}:
    get:
      summary: The logged in user is monitoring the current object or not (true /
        false)
      description: The logged in user is monitoring the current object or not (true
        / false).
      operationId: isObjectMonitored
      x-api-path-slug: monitoringusersmyselfobjectsobjectid-get
      parameters:
      - in: path
        name: objectid
        description: Object id
      responses:
        2:
          description: Successful response
        200:
          description: OK
      tags:
      - The
      - Logged
      - In
      - User
      - Is
      - Monitoring
      - Current
      - Object
      - Not
      - (true
      - ""
      - ""
      - False)
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