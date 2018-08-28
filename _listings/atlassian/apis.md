---
name: Atlassian
x-slug: atlassian
description: Millions of users globally rely on Atlassian products every day for improving
  software development, project management, collaboration, and code quality.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
x-kinRank: "8"
x-alexaRank: "1656"
tags: Logging
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/apis.md
specificationVersion: "0.14"
apis:
- name: Jira Cloud REST API - Get change logs
  x-api-slug: api2issueissueidorkeychangelog-get
  description: Returns a [paginated](#pagination) list of all updates of an issue,
    sorted by date, starting from the oldest.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeychangelog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeychangelog-get-openapi.md
- name: Jira Cloud REST API - Get issue worklog
  x-api-slug: api2issueissueidorkeyworklog-get
  description: "Returns all work logs for an issue. The response is [paginated](#pagination)
    \ \n**Note:** Work logs won't be returned if the Log work field is hidden for
    the project."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeyworklog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeyworklog-get-openapi.md
- name: Jira Cloud REST API - Get worklog
  x-api-slug: api2issueissueidorkeyworklogid-get
  description: "Returns a specific worklog.  \n**Note:** The work log won't be returned
    if the Log work field is hidden for the project."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeyworklogid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeyworklogid-get-openapi.md
- name: Jira Cloud REST API - Get change logs
  x-api-slug: api2issueissueidorkeychangelog-get
  description: Returns a [paginated](#pagination) list of all updates of an issue,
    sorted by date, starting from the oldest.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeychangelog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeychangelog-get-openapi.md
- name: Jira Cloud REST API - Get issue worklog
  x-api-slug: api2issueissueidorkeyworklog-get
  description: "Returns all work logs for an issue. The response is [paginated](#pagination)
    \ \n**Note:** Work logs won't be returned if the Log work field is hidden for
    the project."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeyworklog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeyworklog-get-openapi.md
- name: Jira Cloud REST API - Get IDs of deleted worklogs
  x-api-slug: api2worklogdeleted-get
  description: "Returns a list of IDs and delete timestamps for worklogs deleted after
    a date and time.  \n  \nThis resource is paginated, with a limit of 1000 worklogs
    per page. Each page lists worklogs from oldest to youngest. If the number of items
    in the date range exceeds 1000, `until` indicates the timestamp of the youngest
    item on the page. Also, `nextPage` provides the URL for the next page of worklogs.
    The `lastPage` parameter is set to true on the last page of worklogs.  \n  \nThis
    resource does not return worklogs deleted during the minute preceding the request.
    \ \n  \n**[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**
    Permission to access Jira."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2worklogdeleted-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2worklogdeleted-get-openapi.md
- name: Jira Cloud REST API - Get worklogs
  x-api-slug: api2workloglist-post
  description: "Returns worklog details for a list of worklog IDs.  \n  \nWorklogs
    can be set as viewable by:\n\n*   all users\n*   members of a project role or
    group\n\nFor a worklog to be returned, it must be set as _Viewable by All Users_
    or the calling user must be a member of the project role or group with permission
    to view the worklog.  \n  \nThe returned list of worklogs is limited to 1000 items.
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission
    to access Jira."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2workloglist-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2workloglist-post-openapi.md
- name: Jira Cloud REST API - Get IDs of updated worklogs
  x-api-slug: api2worklogupdated-get
  description: "Returns a list of IDs and update timestamps for worklogs updated after
    a date and time.  \n  \nThis resource is paginated, with a limit of 1000 worklogs
    per page. Each page lists worklogs from oldest to youngest. If the number of items
    in the date range exceeds 1000, `until` indicates the timestamp of the youngest
    item on the page. Also, `nextPage` provides the URL for the next page of worklogs.
    The `lastPage` parameter is set to true on the last page of worklogs.  \n  \nThis
    resource does not return worklogs updated during the minute preceding the request.
    \ \n  \n**[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**
    Permission to access Jira."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2worklogupdated-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2worklogupdated-get-openapi.md
- name: Jira Cloud REST API - Get change logs
  x-api-slug: api2issueissueidorkeychangelog-get
  description: Returns a [paginated](#pagination) list of all updates of an issue,
    sorted by date, starting from the oldest.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeychangelog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeychangelog-get-openapi.md
- name: Jira Cloud REST API - Get change logs
  x-api-slug: api2issueissueidorkeychangelog-get
  description: Returns a [paginated](#pagination) list of all updates of an issue,
    sorted by date, starting from the oldest.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeychangelog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/atlassian/api2issueissueidorkeychangelog-get-openapi.md
x-common:
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/platform/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/confluence/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/software/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/service-desk/swagger.v3.json
- type: x-website
  url: http://atlassian.com/
- type: x-website
  url: http://www.atlassian.com
- type: x-api-gallery
  url: http://att.dev.program.api.gallery.streamdata.io
- type: x-api-stack
  url: http://atlassian.stack.network
- type: x-blog
  url: http://blogs.atlassian.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/atlassian
- type: x-crunchbase
  url: http://www.crunchbase.com/company/atlassian
- type: x-email
  url: copyright@atlassian.com
- type: x-email
  url: trademarks@atlassian.com
- type: x-email
  url: sales@atlassian.com
- type: x-email
  url: ar_enterprise@atlassian.com
- type: x-email
  url: privacy@atlassian.com
- type: x-email
  url: eudatarep@atlassian.com
- type: x-email
  url: experts@atlassian.com
- type: x-email
  url: remittance@atlassian.com
- type: x-email
  url: ap@atlassian.com
- type: x-email
  url: procurement@atlassian.com
- type: x-github
  url: https://github.com/atlassian
- type: x-privacy-policy
  url: https://www.atlassian.com/legal/privacy-policy?_ga=2.188884514.868776184.1519225620-845241124.1519225620
- type: x-twitter
  url: https://twitter.com/atlassian
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---