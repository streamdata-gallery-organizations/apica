---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Aggregated Checks API Checks Aggregated?fromUtc={fromUtc}&amp;toUtc={toUtc}&amp;detail_level={detail_level}&amp;scope={scope}
  version: 1.0.0
  description: For all user visible checks - gets aggregated data and SLA between
    two dates.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  "":
    ' get ':
      summary: Checks Aggregated?fromUtc={fromUtc}&amp;toUtc={toUtc}&amp;detail_level={detail_level}&amp;scope={scope}
      description: For all user visible checks - gets aggregated data and SLA between
        two dates.
      operationId: -checks-aggregatedfromutcfromutcamptoutctoutcampdetail-leveldetail-levelampscopescope-
      x-api-path-slug: get
      responses:
        200:
          description: OK
      tags:
      - Aggregated
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