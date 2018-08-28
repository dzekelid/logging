---
swagger: "2.0"
x-collection-name: AWS S3
x-complete: 0
info:
  title: AWS S3 GET Bucket logging
  version: 1.0.0
  description: This implementation of the GET operation uses thelogging subresource
    to return the logging status of a bucketand the permissions users have to view
    and modify that status
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?logging:
    get:
      summary: GET Bucket logging
      description: This implementation of the GET operation uses thelogging subresource
        to return the logging status of a bucketand the permissions users have to
        view and modify that status
      operationId: get-bucket-logging
      x-api-path-slug: logging-get
      responses:
        200:
          description: OK
      tags:
      - Bucket
      - Logging
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