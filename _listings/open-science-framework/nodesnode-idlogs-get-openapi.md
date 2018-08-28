---
swagger: "2.0"
x-collection-name: Open Science Framework
x-complete: 0
info:
  title: Open Science Framework List all logs
  description: |-
    A paginated list of all logs associated with a given node.

    The returned logs are sorted by their `date`, with the most recents logs appearing first.

    This list includes the logs of the specified node as well as the logs of that node's children to which the current user has read-only access.

    ####Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of up to 10 logs. Each resource in the array is a separate logs object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).
    ####Filtering
    You can optionally request that the response only include logs that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/nodes/ezcuj/logs/?filter[action]=made_private.

    Nodes may be filtered by their `action`, and `date`.
  contact:
    name: OSF
    url: https://osf.io/support
    email: support@osf.io
  version: "2.0"
host: test-api.osf.io
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /logs/{log_id}/:
    get:
      summary: Retrieve a log
      description: |-
        Retrieves the details of a log.
        A log is permanent immutable record of a node's history. A log is created when a user performs one of many actions. See the [actions](#Logs_logs_actions) section for more details.
        ####Returns
        Returns a JSON object with a `data` key containing the representation of the requested log, if the request was successful.

        If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
      operationId: logs_read
      x-api-path-slug: logslog-id-get
      parameters:
      - in: path
        name: log_id
        description: The unique identifier of the log you wish to retrieve
      responses:
        200:
          description: OK
      tags:
      - Logs
      - Log
  /nodes/{node_id}/logs/:
    get:
      summary: List all logs
      description: |-
        A paginated list of all logs associated with a given node.

        The returned logs are sorted by their `date`, with the most recents logs appearing first.

        This list includes the logs of the specified node as well as the logs of that node's children to which the current user has read-only access.

        ####Returns
        Returns a JSON object containing `data` and `links` keys.

        The `data` key contains an array of up to 10 logs. Each resource in the array is a separate logs object.

        The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).
        ####Filtering
        You can optionally request that the response only include logs that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/nodes/ezcuj/logs/?filter[action]=made_private.

        Nodes may be filtered by their `action`, and `date`.
      operationId: nodes_logs_list
      x-api-path-slug: nodesnode-idlogs-get
      parameters:
      - in: path
        name: node_id
        description: The unique identifier of the node
      responses:
        200:
          description: OK
      tags:
      - Nodes
      - Node
      - Logs
  /registrations/{registration_id}/logs/:
    get:
      summary: List all logs
      description: |-
        A paginated list of the registration's logs.

        The returned logs are sorted by their `date`, with the most recents logs appearing first.

        ####Returns
        Returns a JSON object containing `data` and `links` keys.

        The `data` key contains an array of up to 10 logs. Each resource in the array is a separate logs object.

        The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).
        ####Filtering
        You can optionally request that the response only include logs that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/registrations/wucr8/logs/?filter[action]=made_private.

        Logs may be filtered by their `action`, and `date`.
      operationId: registrations_logs_list
      x-api-path-slug: registrationsregistration-idlogs-get
      parameters:
      - in: path
        name: registration_id
        description: The unique identifier of the registration
      responses:
        200:
          description: OK
      tags:
      - Registrations
      - Registration
      - Logs
  /:
    get:
      summary: Root
      description: |-
        Welcome to the Open Science Framework API. With this API you can access users, projects, components, logs, and files from the [Open Science Framework](https://osf.io/). The Open Science Framework (OSF) is a free, open-source service maintained by the [Center for Open Science](http://cos.io/).

        #### Returns
        A JSON object with `meta` and `links` keys.

        The `meta` key contains information such as a welcome message from the API, the specified version of the request, and the full representation of the current user, if authentication credentials were provided in the request.

        The `links` key contains links to the following entity collections: [addons](), [collections](), [institutions](#Institutions_institutions_list), [licenses](#Licenses_license_list), [metaschemas](), [nodes](#Nodes_nodes_list), [registrations](), [users](#Users_users_list)
      operationId: base_read
      x-api-path-slug: get
      responses:
        200:
          description: OK
      tags:
      - Root
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