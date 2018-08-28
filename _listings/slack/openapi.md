swagger: "2.0"
x-collection-name: Slack
x-complete: 1
info:
  title: Slack
  description: one-way-to-interact-with-the-slack-platform-is-its-http-rpcbased-web-api-a-collection-of-methods-requiring-oauth-2-0based-user-bot-or-workspace-tokens-blessed-with-related-oauth-scopes-
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