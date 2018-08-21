---
swagger: "2.0"
x-collection-name: Apica
x-complete: 1
info:
  title: Scenarios API
  version: 1.0.0
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
  '/scenarios/proxysniffer/dictionaries/{dictionary_key} ':
    ' get ':
      summary: Scenarios Proxy Sniffer Dictionaries
      description: Gets a Proxy Sniffer scenario custom dictionary by dictionary key.
        Custom dictionary can contain any data used by Proxy Sniffer scripts which
        needs to be stored separately from scripts.
      operationId: getScenariosProxysnifferDictionariesDictionaryKey
      x-api-path-slug: scenariosproxysnifferdictionariesdictionary-key-get
      responses:
        200:
          description: OK
      tags:
      - Scenarios
      - Proxy
      - Sniffer
      - Dictionaries
    ' put ':
      summary: Scenarios Proxy Sniffer Dictionaries
      description: Updates Proxy Sniffer scenario custom dictionary.
      operationId: putScenariosProxysnifferDictionariesDictionaryKey
      x-api-path-slug: scenariosproxysnifferdictionariesdictionary-key-put
      responses:
        200:
          description: OK
      tags:
      - Scenarios
      - Proxy
      - Sniffer
      - Dictionaries
---