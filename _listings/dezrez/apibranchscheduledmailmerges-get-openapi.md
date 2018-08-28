---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Get all scheduled mail merges for the logged in branch.
  version: 1.0.0
  description: Get all scheduled mail merges for the logged in branch..
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/branch/scheduledmailmerges:
    get:
      summary: Get all scheduled mail merges for the logged in branch.
      description: Get all scheduled mail merges for the logged in branch..
      operationId: Branch_GetScheduledMailMergesBypageSizeBypageNumber
      x-api-path-slug: apibranchscheduledmailmerges-get
      parameters:
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Scheduled
      - Mail
      - Mergesthe
      - Logged
      - In
      - Branch
  /api/identity/Get:
    get:
      summary: Gets all of the identities for the logged in person
      description: Gets all of the identities for the logged in person.
      operationId: Identity_GetLoggedInPersonIdentities
      x-api-path-slug: apiidentityget-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - ""
      - Of
      - Identitiesthe
      - Logged
      - In
      - Person
  /api/negotiator/my/groups/favourite:
    get:
      summary: Returns a list of the logged in negotiators favourite groups.
      description: Returns a list of the logged in negotiators favourite groups..
      operationId: Negotiator_FavouriteGroupsBypageSizeBypageNumber
      x-api-path-slug: apinegotiatormygroupsfavourite-get
      parameters:
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Returns
      - List
      - Of
      - Logged
      - In
      - Negotiators
      - Favourite
      - Groups
  /api/negotiator/me/setstatus:
    post:
      summary: Set the online/offline status of the logged in negotiator
      description: Set the online/offline status of the logged in negotiator.
      operationId: Negotiator_SetStatusBystatus
      x-api-path-slug: apinegotiatormesetstatus-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: status
      responses:
        200:
          description: OK
      tags:
      - Set
      - Online
      - Offline
      - Status
      - Of
      - Logged
      - In
      - Negotiator
  /api/negotiator/my/responsibilities:
    get:
      summary: Gets a list of the logged in users responsibilities
      description: Gets a list of the logged in users responsibilities.
      operationId: Negotiator_GetResponsibilities
      x-api-path-slug: apinegotiatormyresponsibilities-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - List
      - Of
      - Logged
      - In
      - Users
      - Responsibilities
  /api/people/{id}/redact:
    post:
      summary: "Redact a Person by PersonId\r\nFirst request is just logged as an
        event \r\nSecond request must be by a branch admin and actually redacts the
        person"
      description: "Redact a person by personid\r\nfirst request is just logged as
        an event \r\nsecond request must be by a branch admin and actually redacts
        the person."
      operationId: People_RedactByidBynote
      x-api-path-slug: apipeopleidredact-post
      parameters:
      - in: path
        name: id
      - in: query
        name: note
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Redact
      - Person
      - By
      - "PersonId\r\nFirst"
      - Request
      - Is
      - Just
      - Logged
      - As
      - Event
      - Second
      - Request
      - Must
      - Be
      - By
      - Branch
      - Admin
      - Actually
      - Redacts
      - Person
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