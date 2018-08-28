swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/catalog/analytics/{id}/logs:
    get:
      summary: Get the analytic recent logs
      description: Return the recent analytic logs
      operationId: retrieveAnalyticLog
      x-api-path-slug: apiv1cataloganalyticsidlogs-get
      parameters:
      - in: path
        name: id
        description: analytic id
      responses:
        2:
          description: Successful response
      tags:
      - Analytic
      - Recent
      - Logs
  /instances/{instanceId}/containers/{containerId}/logs/{logName}:
    get:
      summary: Get Instances Instanceid Containers Containerid Logs Logname
      description: Get instances instanceid containers containerid logs logname.
      operationId: getInstanceContainerLogContentsUsingGET
      x-api-path-slug: instancesinstanceidcontainerscontaineridlogslogname-get
      parameters:
      - in: path
        name: containerId
        description: containerId
      - in: path
        name: instanceId
        description: instanceId
      - in: query
        name: length
        description: length
      - in: path
        name: logName
        description: logName
      - in: query
        name: offset
        description: offset
      responses:
        2:
          description: Successful response
        200:
          description: Successful response
      tags:
      - Instances
      - Instanceid
      - Containers
      - Containerid
      - Logs
      - Logname
  /instances/{instanceId}/containers/{containerId}/logs:
    get:
      summary: Get Instances Instanceid Containers Containerid Logs
      description: Get instances instanceid containers containerid logs.
      operationId: getInstanceContainerLogsUsingGET
      x-api-path-slug: instancesinstanceidcontainerscontaineridlogs-get
      parameters:
      - in: path
        name: containerId
        description: containerId
      - in: path
        name: instanceId
        description: instanceId
      responses:
        2:
          description: Successful response
        200:
          description: Successful response
      tags:
      - Instances
      - Instanceid
      - Containers
      - Containerid
      - Logs
  /instances/{instanceId}/submit-logs:
    get:
      summary: Get Instances Instanceid Submit Logs
      description: Get instances instanceid submit logs.
      operationId: getSparkSubmitLogsUsingGET
      x-api-path-slug: instancesinstanceidsubmitlogs-get
      parameters:
      - in: path
        name: instanceId
        description: instanceId
      - in: query
        name: length
        description: length
      - in: query
        name: offset
        description: offset
      responses:
        2:
          description: Successful response
        200:
          description: Successful response
      tags:
      - Instances
      - Instanceid
      - Submit
      - Logs