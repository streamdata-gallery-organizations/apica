---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Groups API Groups Users
  version: 1.0.0
  description: ""
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/groups ':
    ' get ':
      summary: Groups
      description: Gets a hierarchy of all monitor groups that are visible to you
        as a user or a customer depending on the request context.
      operationId: -groups-
      x-api-path-slug: groups-get
      responses:
        200:
          description: OK
      tags:
      - Groups
    ' post ':
      summary: Groups
      description: Creates a new monitor group.
      operationId: -groups-
      x-api-path-slug: groups-post
      responses:
        200:
          description: OK
      tags:
      - Groups
  '/groups/{groupId} ':
    ' put ':
      summary: Groups
      description: Updates a monitor group.
      operationId: -groups-groupid-
      x-api-path-slug: groupsgroupid-put
      responses:
        200:
          description: OK
      tags:
      - Groups
    ' delete ':
      summary: Groups
      description: Deletes a monitor group by Id.
      operationId: -groups-groupid-
      x-api-path-slug: groupsgroupid-delete
      responses:
        200:
          description: OK
      tags:
      - Groups
  '/groups/{groupId}/checks ':
    ' get ':
      summary: Group Checks
      description: Gets a list of checks assigned to the monitor group.
      operationId: -groups-groupid-checks-
      x-api-path-slug: groupsgroupidchecks-get
      responses:
        200:
          description: OK
      tags:
      - Groups
    ' post ':
      summary: Group Checks
      description: Assigns checks to the monitor group.
      operationId: -groups-groupid-checks-
      x-api-path-slug: groupsgroupidchecks-post
      responses:
        200:
          description: OK
      tags:
      - Groups
    ' delete ':
      summary: Groups Checks
      description: Unassigns checks from the monitor group.
      operationId: -groups-groupid-checks-
      x-api-path-slug: groupsgroupidchecks-delete
      responses:
        200:
          description: OK
      tags:
      - Groups
  '/groups/{groupId}/users ':
    ' get ':
      summary: Groups Users
      description: Gets a list of users assigned to the monitor group.
      operationId: -groups-groupid-users-
      x-api-path-slug: groupsgroupidusers-get
      responses:
        200:
          description: OK
      tags:
      - Groups
    ' post ':
      summary: Groups Users
      description: Assigns users to the monitor group.
      operationId: -groups-groupid-users-
      x-api-path-slug: groupsgroupidusers-post
      responses:
        200:
          description: OK
      tags:
      - Groups
    ' delete ':
      summary: Groups Users
      description: ""
      operationId: -groups-groupid-users-
      x-api-path-slug: groupsgroupidusers-delete
      responses:
        200:
          description: OK
      tags:
      - Groups
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