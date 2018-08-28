---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Batch Action Logconversion
  description: Add the data to the flavor asset conversion log, creates it if doesn't
    exists
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/batch/action/logConversion:
    get:
      summary: Get Service Batch Action Logconversion
      description: Add the data to the flavor asset conversion log, creates it if
        doesn't exists
      operationId: batch.logConversion
      x-api-path-slug: servicebatchactionlogconversion-get
      parameters:
      - in: query
        name: data
      - in: query
        name: flavorAssetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Batch
      - Action
      - LogConversion
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