---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Scenarios API Scenarios Proxysniffer Dictionaries {dictionary_key}
  version: 1.0.0
  description: Updates Proxy Sniffer scenario custom dictionary.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/scenarios/proxysniffer/dictionaries ':
    ' post ':
      summary: Scenarios Proxysniffer Dictionaries
      description: Adds Proxy Sniffer scenario custom dictionary.
      operationId: ""
      x-api-path-slug: scenariosproxysnifferdictionaries-post
      responses:
        200:
          description: OK
      tags:
      - Scenarios
  '/scenarios/proxysniffer/dictionaries/{dictionary_key} ':
    ' get ':
      summary: Scenarios Proxysniffer Dictionaries {dictionary_key}
      description: Gets a Proxy Sniffer scenario custom dictionary by dictionary key.
        Custom dictionary can contain any data used by Proxy Sniffer scripts which
        needs to be stored separately from scripts.
      operationId: ""
      x-api-path-slug: scenariosproxysnifferdictionariesdictionary-key-get
      responses:
        200:
          description: OK
      tags:
      - Scenarios
    ' put ':
      summary: Scenarios Proxysniffer Dictionaries {dictionary_key}
      description: Updates Proxy Sniffer scenario custom dictionary.
      operationId: ""
      x-api-path-slug: scenariosproxysnifferdictionariesdictionary-key-put
      responses:
        200:
          description: OK
      tags:
      - Scenarios
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