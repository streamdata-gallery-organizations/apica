---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Scenarios API Scenarios Proxy Sniffer Dictionaries
  version: 1.0.0
  description: Adds Proxy Sniffer scenario custom dictionary.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/scenarios/proxysniffer/dictionaries ':
    ' post ':
      summary: Scenarios Proxy Sniffer Dictionaries
      description: Adds Proxy Sniffer scenario custom dictionary.
      operationId: postScenariosProxysnifferDictionaries
      x-api-path-slug: scenariosproxysnifferdictionaries-post
      responses:
        200:
          description: OK
      tags:
      - Scenarios
      - Proxy
      - Sniffer
      - Dictionaries
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