---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Checks Command API Checks Command
  version: 1.0.0
  description: Creates a new Command check.
host: api.pingdom.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? '/alerts?check_id={check_id}&amp;severity={severity}&amp;enabled={enabled}&amp;target_type={target_type}&amp;target_id={target_id} '
  : ' get ':
      summary: Alerts
      description: Gets alerts filtered by set of optional parameters.
      operationId: -alertscheck-idcheck-idampseverityseverityampenabledenabledamptarget-typetarget-typeamptarget-idtarg
      x-api-path-slug: alertscheck-idcheck-idampseverityseverityampenabledenabledamptarget-typetarget-typeamptarget-idtarget-id-get
      responses:
        200:
          description: OK
      tags:
      - Alerts
  '/alerts/{alert_id} ':
    ' get ':
      summary: Alerts
      description: Gets alert by Id.
      operationId: -alerts-alert-id-
      x-api-path-slug: alertsalert-id-get
      responses:
        200:
          description: OK
      tags:
      - Alerts
    ' put ':
      summary: Alerts
      description: Updates alert.
      operationId: -alerts-alert-id-
      x-api-path-slug: alertsalert-id-put
      responses:
        200:
          description: OK
      tags:
      - Alerts
    ' delete ':
      summary: Alerts
      description: Deletes alert by Id.
      operationId: -alerts-alert-id-
      x-api-path-slug: alertsalert-id-delete
      responses:
        200:
          description: OK
      tags:
      - Alerts
  '/alerts/{alert_type} ':
    ' post ':
      summary: Alerts
      description: Creates a new alert.
      operationId: -alerts-alert-type-
      x-api-path-slug: alertsalert-type-post
      responses:
        200:
          description: OK
      tags:
      - Alerts
  '/alerts/recipients ':
    ' get ':
      summary: Alerts Recipients
      description: Gets a list of all alert recipient's targets that are visible to
        you as a customer.
      operationId: -alerts-recipients-
      x-api-path-slug: alertsrecipients-get
      responses:
        200:
          description: OK
      tags:
      - Alerts
  '/alerts/recipients/{recipient_id} ':
    ' get ':
      summary: Alerts Recipients
      description: Gets a information about alert recipient's targets.
      operationId: -alerts-recipients-recipient-id-
      x-api-path-slug: alertsrecipientsrecipient-id-get
      responses:
        200:
          description: OK
      tags:
      - Alerts
  '/alerts/recipient/{recipient_id} ':
    ' put ':
      summary: Alerts Recipient
      description: Updates recipient along with sms and email targets associated.
      operationId: -alerts-recipient-recipient-id-
      x-api-path-slug: alertsrecipientrecipient-id-put
      responses:
        200:
          description: OK
      tags:
      - Alerts
  '/alerts/recipient ':
    ' post ':
      summary: Alerts Recipient
      description: Creates a new recipient with one sms and one email target associated.
      operationId: -alerts-recipient-
      x-api-path-slug: alertsrecipient-post
      responses:
        200:
          description: OK
      tags:
      - Alerts
  '/alerts/targets ':
    ' get ':
      summary: Alerts Targets
      description: Gets a list of all alert targets that are visible to you as a customer.
      operationId: -alerts-targets-
      x-api-path-slug: alertstargets-get
      responses:
        200:
          description: OK
      tags:
      - Alerts
  /alerts/configs/alertId:
    delete:
      summary: Deleting an alert
      description: Deleting an alert
      operationId: deleting-an-alert
      x-api-path-slug: alertsconfigsalertid-delete
      parameters:
      - in: path
        name: alertId
        description: The ID of the alert to be deleted
        type: string
      - in: path
        name: token
        description: Your API token
        type: string
      - in: body
        name: token
        description: Your API token
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: token
        description: Your API token
        type: string
      responses:
        200:
          description: OK
      tags:
      - Alerts
  /alerts/configs/subjectId:
    get:
      summary: Listing alerts by subject
      description: Get a list of all configured alerts for a specific subject (device
        or service).
      operationId: listing-alerts-by-subject
      x-api-path-slug: alertsconfigssubjectid-get
      parameters:
      - in: path
        name: subjectId
        description: The ID of the subject e
        type: string
      - in: path
        name: subjectType
        description: The type of the subject - device or service
        type: string
      - in: query
        name: subjectType
        description: The type of the subject - device or service
        type: string
      - in: path
        name: token
        description: Your API token
        type: string
      - in: query
        name: token
        description: Your API token
        type: string
      responses:
        200:
          description: OK
      tags:
      - Alerts
  /alerts/triggered:
    get:
      summary: Triggered Alerts
      description: Get a list of all triggered alerts on your account, per subject
        (device or service) or per alert config.
      operationId: triggered-alerts
      x-api-path-slug: alertstriggered-get
      parameters:
      - in: query
        name: closed
        description: Whether to filter by closed or open alerts - unset = all alerts,
          false = open alerts, true = closed alerts
        type: string
      - in: query
        name: filter
        description: You can provide a JSON encoded hash filter for the search that
          will return items that match the filter
        type: string
      - in: query
        name: subjectType
        description: The type of the subject - device, service, deviceGroup or serviceGroup
          if you also specify the subjectId as part of the URL (see examples below)
        type: string
      - in: query
        name: token
        description: Your API token
        type: string
      responses:
        200:
          description: OK
      tags:
      - Alerts
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
      summary: Checks Browser Results
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
      summary: Checks Browser Results
      description: Gets browser check results in json format by result ids.
      operationId: -checks-browser-checkid-results-urldata-
      x-api-path-slug: checksbrowsercheckidresultsurldata-post
      responses:
        200:
          description: OK
      tags:
      - Browser
  '/checks ':
    ' get ':
      summary: Get Checks
      description: Gets a list of all checks that are visible to you as a user or
        a customer depending on the request context.
      operationId: getChecks
      x-api-path-slug: checks-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  '/checks/{checkId} ':
    ' get ':
      summary: Get Check
      description: Gets info about a check, current SLA, last result and its status.
      operationId: getChecksCheck
      x-api-path-slug: checkscheckid-get
      responses:
        200:
          description: OK
      tags:
      - Checks
    ' put ':
      summary: Update Check
      description: Updates a check.
      operationId: putChecksCheck
      x-api-path-slug: checkscheckid-put
      responses:
        200:
          description: OK
      tags:
      - Checks
    ' delete ':
      summary: Delete Check
      description: Deletes a check.
      operationId: deleteChecksCheck
      x-api-path-slug: checkscheckid-delete
      responses:
        200:
          description: OK
      tags:
      - Checks
  '/checks/{checkId}/lastvalue ':
    ' get ':
      summary: Get Checks Lastvalue
      description: Gets the absolute last value of a specific check.
      operationId: getChecksCheckLastvalue
      x-api-path-slug: checkscheckidlastvalue-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  /checks/{checkId}/results/{millisecondsUtc}:
    ' get ':
      summary: Get Checks Results
      description: Gets a specific check result by a numeric java timestamp.
      operationId: getChecksCheckResultsMillisecondsutcDetailLevelDetailLevel
      x-api-path-slug: checkscheckidresultsmillisecondsutc-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  /checks/{checkId}/results:
    ' get ':
      summary: Get Checks Results
      description: Gets the most recent check results.
      operationId: getChecksCheckResultsMostrecentMostrecent&amp;detailLevelDetailLevel
      x-api-path-slug: checkscheckidresults-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  ? |2-

        /api/{version}/checks
  : ? |2-

          get
    : summary: Get Check List
      description: Returns a list overview of all checks.
      operationId: |2-

        getApiVersionChecks
      x-api-path-slug: apiversionchecks-get
      parameters:
      - in: query
        name: include_tags
        description: Include tag list for each check
        type: <td>boolean</td>
      - in: query
        name: limit
        description: Limits the number of returned probes to the specified quantity
        type: <td>integer</td>
      - in: query
        name: offset
        description: Offset for listing
        type: <td>integer</td>
      - in: query
        name: tags
        description: Tag list separated by commas
        type: <td>string</td>
      responses:
        200:
          description: OK
      tags:
      - Checks
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
basePath: /
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