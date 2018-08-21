---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Checks Port API Checks Port {checkId}
  version: 1.0.0
  description: Updates a Port check.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/checks/port ':
    ' post ':
      summary: Checks Port
      description: Creates a new Port check.
      operationId: -checks-port-
      x-api-path-slug: checksport-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Ports
  '/checks/port/{checkId} ':
    ' put ':
      summary: Checks Port {checkId}
      description: Updates a Port check.
      operationId: -checks-port-checkid-
      x-api-path-slug: checksportcheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Ports
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