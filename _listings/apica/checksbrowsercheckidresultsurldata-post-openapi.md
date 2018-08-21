---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Browser Checks API Checks Browser Results URLdata
  version: 1.0.0
  description: Gets browser check results in json format by result ids.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/checks/browser ':
    ' post ':
      summary: Checks Browser
      description: Creates a new browser check.
      operationId: -checks-browser-
      x-api-path-slug: checksbrowser-post
      responses:
        200:
          description: OK
      tags:
      - Browser
  '/checks/browser/{checkId} ':
    ' put ':
      summary: Checks Browser
      description: Updates a browser check.
      operationId: -checks-browser-checkid-
      x-api-path-slug: checksbrowsercheckid-put
      responses:
        200:
          description: OK
      tags:
      - Browser
  '/checks/browser/locations ':
    ' get ':
      summary: Checks Browser Locations
      description: Gets a list of all locations that are available for browser checks.
      operationId: -checks-browser-locations-
      x-api-path-slug: checksbrowserlocations-get
      responses:
        200:
          description: OK
      tags:
      - Browser
  /checks/browser/{checkId}/results/{resultId}/urldata:
    ' get ':
      summary: Checks Browser Results {resultId} URLdata?format={format}
      description: Gets a file that contains browser check result data.
      operationId: -checks-browser-checkid-results-resultid-urldataformatformat-
      x-api-path-slug: checksbrowsercheckidresultsresultidurldata-get
      responses:
        200:
          description: OK
      tags:
      - Browser
  '/checks/browser/{checkId}/results/urldata ':
    ' post ':
      summary: Checks Browser Results URLdata
      description: Gets browser check results in json format by result ids.
      operationId: -checks-browser-checkid-results-urldata-
      x-api-path-slug: checksbrowsercheckidresultsurldata-post
      responses:
        200:
          description: OK
      tags:
      - Browser
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