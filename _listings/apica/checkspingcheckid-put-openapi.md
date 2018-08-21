---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Checks Ping API Checks Ping {checkId}
  version: 1.0.0
  description: Updates a Ping check.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/checks/ping ':
    ' post ':
      summary: Checks Ping
      description: Creates a new Ping check.
      operationId: -checks-ping-
      x-api-path-slug: checksping-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Pings
  '/checks/ping/{checkId} ':
    ' put ':
      summary: Checks Ping {checkId}
      description: Updates a Ping check.
      operationId: -checks-ping-checkid-
      x-api-path-slug: checkspingcheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Pings
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