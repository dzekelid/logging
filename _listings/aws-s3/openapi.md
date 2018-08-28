swagger: "2.0"
x-collection-name: AWS S3
x-complete: 1
info:
  title: No Title
  version: 1.0.0
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