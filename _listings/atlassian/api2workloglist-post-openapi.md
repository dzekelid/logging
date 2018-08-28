---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get worklogs
  description: "Returns worklog details for a list of worklog IDs.  \n  \nWorklogs
    can be set as viewable by:\n\n*   all users\n*   members of a project role or
    group\n\nFor a worklog to be returned, it must be set as _Viewable by All Users_
    or the calling user must be a member of the project role or group with permission
    to view the worklog.  \n  \nThe returned list of worklogs is limited to 1000 items.
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission
    to access Jira."
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/issue/{issueIdOrKey}/changelog:
    get:
      summary: Get change logs
      description: Returns a [paginated](#pagination) list of all updates of an issue,
        sorted by date, starting from the oldest.
      operationId: com.atlassian.jira.rest.v2.issue.IssueChangelogResource.getChangeLogs_get
      x-api-path-slug: api2issueissueidorkeychangelog-get
      parameters:
      - in: path
        name: issueIdOrKey
        description: ID or key of the issue
      - in: query
        name: maxResults
        description: Maximum number of items to return per page
      - in: query
        name: startAt
        description: Page offset, ie
      responses:
        200:
          description: OK
      tags:
      - Change
      - Logs
  /api/2/issue/{issueIdOrKey}/worklog:
    get:
      summary: Get issue worklog
      description: "Returns all work logs for an issue. The response is [paginated](#pagination)
        \ \n**Note:** Work logs won't be returned if the Log work field is hidden
        for the project."
      operationId: com.atlassian.jira.rest.v2.issue.IssueWorklogsResource.getIssueWorklog_get
      x-api-path-slug: api2issueissueidorkeyworklog-get
      parameters:
      - in: query
        name: expand
        description: 'Optional comma separated list of parameters to expand: properties
          (provides worklog properties)'
      - in: path
        name: issueIdOrKey
        description: The worklogs belongs to
      - in: query
        name: maxResults
        description: Maximum number of items to return per page
      - in: query
        name: startAt
        description: Page offset, ie
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Worklog
  /api/2/issue/{issueIdOrKey}/worklog/{id}:
    get:
      summary: Get worklog
      description: "Returns a specific worklog.  \n**Note:** The work log won't be
        returned if the Log work field is hidden for the project."
      operationId: com.atlassian.jira.rest.v2.issue.IssueWorklogsResource.getWorklog_get
      x-api-path-slug: api2issueissueidorkeyworklogid-get
      parameters:
      - in: query
        name: expand
        description: 'optional comma separated list of parameters to expand: properties
          (provides worklog properties)'
      - in: path
        name: id
        description: a String containing the work log id
      - in: path
        name: issueIdOrKey
        description: a string containing the issue id or key the worklog belongs to
      responses:
        200:
          description: OK
      tags:
      - Worklog
  /api/2/worklog/deleted:
    get:
      summary: Get IDs of deleted worklogs
      description: "Returns a list of IDs and delete timestamps for worklogs deleted
        after a date and time.  \n  \nThis resource is paginated, with a limit of
        1000 worklogs per page. Each page lists worklogs from oldest to youngest.
        If the number of items in the date range exceeds 1000, `until` indicates the
        timestamp of the youngest item on the page. Also, `nextPage` provides the
        URL for the next page of worklogs. The `lastPage` parameter is set to true
        on the last page of worklogs.  \n  \nThis resource does not return worklogs
        deleted during the minute preceding the request.  \n  \n**[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** Permission to access Jira."
      operationId: com.atlassian.jira.rest.v2.issue.worklog.WorklogResource.getIdsOfWorklogsDeletedSince_get
      x-api-path-slug: api2worklogdeleted-get
      parameters:
      - in: query
        name: since
        description: The date and time, in UNIX timestamp format, after which deleted
          worklogs are returned
      responses:
        200:
          description: OK
      tags:
      - IDs
      - Of
      - Deleted
      - Worklogs
  /api/2/worklog/list:
    post:
      summary: Get worklogs
      description: "Returns worklog details for a list of worklog IDs.  \n  \nWorklogs
        can be set as viewable by:\n\n*   all users\n*   members of a project role
        or group\n\nFor a worklog to be returned, it must be set as _Viewable by All
        Users_ or the calling user must be a member of the project role or group with
        permission to view the worklog.  \n  \nThe returned list of worklogs is limited
        to 1000 items. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** Permission to access Jira."
      operationId: com.atlassian.jira.rest.v2.issue.worklog.WorklogResource.getWorklogsForIds_post
      x-api-path-slug: api2workloglist-post
      parameters:
      - in: query
        name: expand
        description: Use [expand](https://developer
      responses:
        200:
          description: OK
      tags:
      - Worklogs
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