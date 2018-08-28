swagger: "2.0"
x-collection-name: Broadleaf Commerce
x-complete: 1
info:
  title: Broadleaf Commerce API
  description: the-default-broadleaf-commerce-apis
  version: 1.0.0
host: demo.broadleafcommerce.org
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /logfile:
    get:
      summary: Get Logfile
      description: Get logfile.
      operationId: getLogfile
      x-api-path-slug: logfile-get
      responses:
        200:
          description: OK
      tags:
      - Logfile
    head:
      summary: Head Logfile
      description: Head logfile.
      operationId: headLogfile
      x-api-path-slug: logfile-head
      responses:
        200:
          description: OK
      tags:
      - Head
      - Logfile
  /logfile.json:
    get:
      summary: Get Logfile
      description: Get logfile.
      operationId: getLogfile.json
      x-api-path-slug: logfile-json-get
      responses:
        200:
          description: OK
      tags:
      - Logfile
    head:
      summary: Head Logfile
      description: Head logfile.
      operationId: headLogfile.json
      x-api-path-slug: logfile-json-head
      responses:
        200:
          description: OK
      tags:
      - Head
      - Logfile
  /loggers:
    get:
      summary: Get Loggers
      description: Get loggers.
      operationId: getLoggers
      x-api-path-slug: loggers-get
      responses:
        200:
          description: OK
      tags:
      - Loggers
  /loggers.json:
    get:
      summary: Get Loggers
      description: Get loggers.
      operationId: getLoggers.json
      x-api-path-slug: loggers-json-get
      responses:
        200:
          description: OK
      tags:
      - Loggers
  /loggers/{name}:
    get:
      summary: Get Loggers Name
      description: Get loggers name.
      operationId: getLoggersName
      x-api-path-slug: loggersname-get
      parameters:
      - in: path
        name: name
        description: name
      responses:
        200:
          description: OK
      tags:
      - Loggers
      - Name
    post:
      summary: Post Loggers Name
      description: Post loggers name.
      operationId: postLoggersName
      x-api-path-slug: loggersname-post
      parameters:
      - in: body
        name: configuration
        description: configuration
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: name
      responses:
        200:
          description: OK
      tags:
      - Loggers
      - Name