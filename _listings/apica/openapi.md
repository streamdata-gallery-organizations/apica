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
      summary: Scenarios Proxysniffer Dictionaries
      description: Adds Proxy Sniffer scenario custom dictionary.
      operationId: postScenariosProxysnifferDictionaries
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
      operationId: getScenariosProxysnifferDictionariesDictionaryKey
      x-api-path-slug: scenariosproxysnifferdictionariesdictionary-key-get
      responses:
        200:
          description: OK
      tags:
      - Scenarios
    ' put ':
      summary: Scenarios Proxysniffer Dictionaries {dictionary_key}
      description: Updates Proxy Sniffer scenario custom dictionary.
      operationId: putScenariosProxysnifferDictionariesDictionaryKey
      x-api-path-slug: scenariosproxysnifferdictionariesdictionary-key-put
      responses:
        200:
          description: OK
      tags:
      - Scenarios
---