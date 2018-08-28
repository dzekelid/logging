---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 0
info:
  title: Rebilly Retrieve a tracking subscription log with specified identifier string
  description: ""
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tracking/api/{id}:
    get:
      summary: Retrieve a tracking API log with specified identifier string
      description: ""
      operationId: ""
      x-api-path-slug: trackingapiid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Tracking
      - Log
      - Specified
      - Identifier
      - String
  /tracking/subscriptions/{id}:
    get:
      summary: Retrieve a tracking subscription log with specified identifier string
      description: ""
      operationId: ""
      x-api-path-slug: trackingsubscriptionsid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Tracking
      - Subscription
      - Log
      - Specified
      - Identifier
      - String
  /transactions/{id}/gateway-logs:
    get:
      summary: Retrieve a Transaction Gateway Logs
      description: Retrieve Gateway communication Logs for Transaction with specified
        identifier string
      operationId: transactions.id.gateway_logs.get
      x-api-path-slug: transactionsidgatewaylogs-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Transaction
      - Gateway
      - Logs
  /tracking/api:
    get:
      summary: Retrieve a list of tracking API logs
      description: ""
      operationId: ""
      x-api-path-slug: trackingapi-get
      parameters:
      - in: header
        name: Accept
        description: The response media type
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Tracking
      - Logs
  /tracking/subscriptions:
    get:
      summary: Retrieve a list of tracking subscription logs
      description: ""
      operationId: ""
      x-api-path-slug: trackingsubscriptions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Tracking
      - Subscription
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