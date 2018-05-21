---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Checks Command API Checks Command {checkId}
  version: 1.0.0
  description: Updates a command check.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/checks/command ':
    ' post ':
      summary: Checks Command
      description: Creates a new Command check.
      operationId: -checks-command-
      x-api-path-slug: checkscommand-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
  '/checks/command-v2 ':
    ' post ':
      summary: Checks Command V2
      description: Creates a new Command check (version 2).
      operationId: -checks-command-v2-
      x-api-path-slug: checkscommandv2-post
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
  '/checks/command-v2/{checkId} ':
    ' put ':
      summary: Checks Command V2 {checkId}
      description: Updates a command check (version 2).
      operationId: -checks-command-v2-checkid-
      x-api-path-slug: checkscommandv2checkid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
  '/checks/command/{checkId} ':
    ' put ':
      summary: Checks Command {checkId}
      description: Updates a command check.
      operationId: -checks-command-checkid-
      x-api-path-slug: checkscommandcheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Command
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