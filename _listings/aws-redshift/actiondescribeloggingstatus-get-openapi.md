---
swagger: "2.0"
x-collection-name: AWS Redshift
x-complete: 0
info:
  title: Amazon Redshift API Describe Logging Status
  version: 1.0.0
  description: |-
    Describes whether information, such as queries and connection attempts, is being
                logged for the specified Amazon Redshift cluster.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeLoggingStatus:
    get:
      summary: Describe Logging Status
      description: |-
        Describes whether information, such as queries and connection attempts, is being
                    logged for the specified Amazon Redshift cluster.
      operationId: describeLoggingStatus
      x-api-path-slug: actiondescribeloggingstatus-get
      parameters:
      - in: query
        name: ClusterIdentifier
        description: The identifier of the cluster from which to get the logging status
        type: string
      responses:
        200:
          description: OK
      tags:
      - Logging
  /?Action=DisableLogging:
    get:
      summary: Disable Logging
      description: |-
        Stops logging information, such as queries and connection attempts, for the
                    specified Amazon Redshift cluster.
      operationId: disableLogging
      x-api-path-slug: actiondisablelogging-get
      parameters:
      - in: query
        name: ClusterIdentifier
        description: The identifier of the cluster on which logging is to be stopped
        type: string
      responses:
        200:
          description: OK
      tags:
      - Logging
  /?Action=EnableLogging:
    get:
      summary: Enable Logging
      description: |-
        Starts logging information, such as queries and connection attempts, for the
                    specified Amazon Redshift cluster.
      operationId: enableLogging
      x-api-path-slug: actionenablelogging-get
      parameters:
      - in: query
        name: BucketName
        description: The name of an existing S3 bucket where the log files are to
          be stored
        type: string
      - in: query
        name: ClusterIdentifier
        description: The identifier of the cluster on which logging is to be started
        type: string
      - in: query
        name: S3KeyPrefix
        description: The prefix applied to the log file names
        type: string
      responses:
        200:
          description: OK
      tags:
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