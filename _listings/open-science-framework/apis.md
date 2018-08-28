---
name: Open Science Framework
x-slug: open-science-framework
description: OSF provides free and open source project management support for researchers
  across the entire research lifecycle. As a collaboration tool, OSF helps researchers
  work on projects privately with a limited number of collaborators and make parts
  of their projects public, or make all the project publicly accessible for broader
  dissemination. As a workflow system, OSF enables connections to the many services
  researchers already use to streamline their process and increase efficiency. As
  a flexible repository, it can store and archive research data, protocols, and materials.
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Logging
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/apis.md
specificationVersion: "0.14"
apis:
- name: Open Science Framework - Retrieve a log
  x-api-slug: logslog-id-get
  description: |-
    Retrieves the details of a log.
    A log is permanent immutable record of a node's history. A log is created when a user performs one of many actions. See the [actions](#Logs_logs_actions) section for more details.
    ####Returns
    Returns a JSON object with a `data` key containing the representation of the requested log, if the request was successful.

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/logslog-id-get-openapi.md
- name: Open Science Framework - Retrieve a log
  x-api-slug: logslog-id-get
  description: |-
    Retrieves the details of a log.
    A log is permanent immutable record of a node's history. A log is created when a user performs one of many actions. See the [actions](#Logs_logs_actions) section for more details.
    ####Returns
    Returns a JSON object with a `data` key containing the representation of the requested log, if the request was successful.

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/logslog-id-get-openapi.md
- name: Open Science Framework - List all logs
  x-api-slug: nodesnode-idlogs-get
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
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/nodesnode-idlogs-get-openapi.md
- name: Open Science Framework - List all logs
  x-api-slug: registrationsregistration-idlogs-get
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
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/registrationsregistration-idlogs-get-openapi.md
- name: Open Science Framework - Retrieve a log
  x-api-slug: logslog-id-get
  description: |-
    Retrieves the details of a log.
    A log is permanent immutable record of a node's history. A log is created when a user performs one of many actions. See the [actions](#Logs_logs_actions) section for more details.
    ####Returns
    Returns a JSON object with a `data` key containing the representation of the requested log, if the request was successful.

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/logslog-id-get-openapi.md
- name: Open Science Framework - Retrieve a log
  x-api-slug: logslog-id-get
  description: |-
    Retrieves the details of a log.
    A log is permanent immutable record of a node's history. A log is created when a user performs one of many actions. See the [actions](#Logs_logs_actions) section for more details.
    ####Returns
    Returns a JSON object with a `data` key containing the representation of the requested log, if the request was successful.

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/logslog-id-get-openapi.md
- name: Open Science Framework - List all logs
  x-api-slug: nodesnode-idlogs-get
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
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/nodesnode-idlogs-get-openapi.md
- name: Open Science Framework - List all logs
  x-api-slug: registrationsregistration-idlogs-get
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
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/registrationsregistration-idlogs-get-openapi.md
- name: Open Science Framework - Root
  x-api-slug: get
  description: |-
    Welcome to the Open Science Framework API. With this API you can access users, projects, components, logs, and files from the [Open Science Framework](https://osf.io/). The Open Science Framework (OSF) is a free, open-source service maintained by the [Center for Open Science](http://cos.io/).

    #### Returns
    A JSON object with `meta` and `links` keys.

    The `meta` key contains information such as a welcome message from the API, the specified version of the request, and the full representation of the current user, if authentication credentials were provided in the request.

    The `links` key contains links to the following entity collections: [addons](), [collections](), [institutions](#Institutions_institutions_list), [licenses](#Licenses_license_list), [metaschemas](), [nodes](#Nodes_nodes_list), [registrations](), [users](#Users_users_list)
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/get-openapi.md
- name: Open Science Framework - Retrieve a log
  x-api-slug: logslog-id-get
  description: |-
    Retrieves the details of a log.
    A log is permanent immutable record of a node's history. A log is created when a user performs one of many actions. See the [actions](#Logs_logs_actions) section for more details.
    ####Returns
    Returns a JSON object with a `data` key containing the representation of the requested log, if the request was successful.

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/logslog-id-get-openapi.md
- name: Open Science Framework - List all logs
  x-api-slug: registrationsregistration-idlogs-get
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
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/registrationsregistration-idlogs-get-openapi.md
- name: Open Science Framework - List all logs
  x-api-slug: nodesnode-idlogs-get
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
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/nodesnode-idlogs-get-openapi.md
- name: Open Science Framework - Retrieve a log
  x-api-slug: logslog-id-get
  description: |-
    Retrieves the details of a log.
    A log is permanent immutable record of a node's history. A log is created when a user performs one of many actions. See the [actions](#Logs_logs_actions) section for more details.
    ####Returns
    Returns a JSON object with a `data` key containing the representation of the requested log, if the request was successful.

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/logslog-id-get-openapi.md
- name: Open Science Framework - Root
  x-api-slug: get
  description: |-
    Welcome to the Open Science Framework API. With this API you can access users, projects, components, logs, and files from the [Open Science Framework](https://osf.io/). The Open Science Framework (OSF) is a free, open-source service maintained by the [Center for Open Science](http://cos.io/).

    #### Returns
    A JSON object with `meta` and `links` keys.

    The `meta` key contains information such as a welcome message from the API, the specified version of the request, and the full representation of the current user, if authentication credentials were provided in the request.

    The `links` key contains links to the following entity collections: [addons](), [collections](), [institutions](#Institutions_institutions_list), [licenses](#Licenses_license_list), [metaschemas](), [nodes](#Nodes_nodes_list), [registrations](), [users](#Users_users_list)
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/open-science-framework/get-openapi.md
x-common:
- type: x-website
  url: https://cos.io
- type: x-api-gallery
  url: http://open.fintech.api.gallery.streamdata.io
- type: x-api-stack
  url: http://open.science.framework.stack.network
- type: x-github
  url: https://github.com/OSFramework
- type: x-twitter
  url: https://twitter.com/OSFramework
- type: x-website
  url: http://osf.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---