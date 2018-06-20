---
name: Apica
x-slug: apica
description: Apica???s performance testing and monitoring solutions provide critical
  peak performance data and 24/7 monitoring of applications and sites around the world.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
x-kinRank: "7"
x-alexaRank: "827487"
tags: Apica
created: "2018-06-19"
modified: "2018-06-19"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/apis.md
specificationVersion: "0.14"
apis:
- name: Alerts API Alerts?check_id={check_id}&amp;severity={severity}&amp;enabled={enabled}&amp;target_type={target_type}&amp;target_id={target_id}
  x-api-slug: alerts-api
  description: Gets alerts filtered by set of optional parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://api.serverdensity.io.///alerts?check_id={check_id}&amp;severity={severity}&amp;enabled={enabled}&amp;target_type={target_type}&amp;target_id={target_id} '
  tags: Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertscheck-idcheck-idampseverityseverityampenabledenabledamptarget-typetarget-typeamptarget-idtarget-id-get-openapi.md
- name: Alerts API Alerts {alert_id}
  x-api-slug: alerts-api
  description: Gets alert by Id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://api.serverdensity.io.///alerts/{alert_id} '
  tags: Alerts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsalert-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsalert-id-get-openapi.md
- name: Alerts API Alerts {alert_id}
  x-api-slug: alerts-api
  description: Updates alert.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://api.serverdensity.io.///alerts/{alert_id} '
  tags: Alerts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsalert-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsalert-id-put-openapi.md
- name: Alerts API Alerts {alert_id}
  x-api-slug: alerts-api
  description: Deletes alert by Id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://api.serverdensity.io.///alerts/{alert_id} '
  tags: Alerts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsalert-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsalert-id-delete-openapi.md
- name: Alerts API Alerts {alert_type}
  x-api-slug: alerts-api
  description: Creates a new alert.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://api.serverdensity.io.///alerts/{alert_type} '
  tags: Alerts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsalert-type-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsalert-type-post-openapi.md
- name: Alerts API Alerts Recipients
  x-api-slug: alerts-api
  description: Gets a list of all alert recipient's targets that are visible to you
    as a customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://api.serverdensity.io.///alerts/recipients '
  tags: Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsrecipients-get-openapi.md
- name: Alerts API Alerts Recipients {recipient_id}
  x-api-slug: alerts-api
  description: Gets a information about alert recipient's targets.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://api.serverdensity.io.///alerts/recipients/{recipient_id} '
  tags: Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsrecipientsrecipient-id-get-openapi.md
- name: Alerts API Alerts Recipient {recipient_id}
  x-api-slug: alerts-api
  description: Updates recipient along with sms and email targets associated.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://api.serverdensity.io.///alerts/recipient/{recipient_id} '
  tags: Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsrecipientrecipient-id-put-openapi.md
- name: Alerts API Alerts Recipient
  x-api-slug: alerts-api
  description: Creates a new recipient with one sms and one email target associated.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://api.serverdensity.io.///alerts/recipient '
  tags: Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsrecipient-post-openapi.md
- name: Alerts API Alerts Targets
  x-api-slug: alerts-api
  description: Gets a list of all alert targets that are visible to you as a customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://api.serverdensity.io.///alerts/targets '
  tags: Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertstargets-get-openapi.md
- name: Alerts API Deleting an alert
  x-api-slug: alerts-api
  description: Deleting an alert
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://api.serverdensity.io.///alerts/configs/alertId
  tags: Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsconfigsalertid-delete-openapi.md
- name: Alerts API Listing alerts by subject
  x-api-slug: alerts-api
  description: Get a list of all configured alerts for a specific subject (device
    or service).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://api.serverdensity.io.///alerts/configs/subjectId
  tags: Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertsconfigssubjectid-get-openapi.md
- name: Alerts API Triggered alerts
  x-api-slug: alerts-api
  description: Get a list of all triggered alerts on your account, per subject (device
    or service) or per alert config.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://api.serverdensity.io.///alerts/triggered
  tags: Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/alertstriggered-get-openapi.md
- name: Alerts API
  x-api-slug: alerts-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://api.serverdensity.io./
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Browser Checks API Checks Browser
  x-api-slug: browser-checks-api
  description: Creates a new browser check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/browser '
  tags: Browser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksbrowser-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksbrowser-post-openapi.md
- name: Browser Checks API Checks Browser
  x-api-slug: browser-checks-api
  description: Updates a browser check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/browser/{checkId} '
  tags: Browser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksbrowsercheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksbrowsercheckid-put-openapi.md
- name: Browser Checks API Checks Browser Locations
  x-api-slug: browser-checks-api
  description: Gets a list of all locations that are available for browser checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/browser/locations '
  tags: Browser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksbrowserlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksbrowserlocations-get-openapi.md
- name: Browser Checks API Checks Browser Results {resultId} URLdata?format={format}
  x-api-slug: browser-checks-api
  description: Gets a file that contains browser check result data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///checks/browser/{checkId}/results/{resultId}/urldata
  tags: Browser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksbrowsercheckidresultsresultidurldata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksbrowsercheckidresultsresultidurldata-get-openapi.md
- name: Browser Checks API Checks Browser Results URLdata
  x-api-slug: browser-checks-api
  description: Gets browser check results in json format by result ids.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/browser/{checkId}/results/urldata '
  tags: Browser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksbrowsercheckidresultsurldata-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksbrowsercheckidresultsurldata-post-openapi.md
- name: Browser Checks API
  x-api-slug: browser-checks-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Checks API Checks
  x-api-slug: checks-api
  description: Gets a list of all checks that are visible to you as a user or a customer
    depending on the request context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: 'https://api.pingdom.com////checks '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checks-get-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Gets info about a check, current SLA, last result and its status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckid-get-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Updates a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckid-put-openapi.md
- name: Checks API Checks {checkId}
  x-api-slug: checks-api
  description: Deletes a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: 'https://api.pingdom.com////checks/{checkId} '
  tags: Checks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckid-delete-openapi.md
- name: Checks API Checks {checkId} Lastvalue
  x-api-slug: checks-api
  description: Gets the absolute last value of a specific check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: 'https://api.pingdom.com////checks/{checkId}/lastvalue '
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckidlastvalue-get-openapi.md
- name: Checks API Checks {checkId} Results {millisecondsUtc}?detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets a specific check result by a numeric java timestamp.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: https://api.pingdom.com////checks/{checkId}/results/{millisecondsUtc}
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckidresultsmillisecondsutc-get-openapi.md
- name: Checks API Checks {checkId} Results?mostrecent={mostrecent}&amp;detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets the most recent check results.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: https://api.pingdom.com////checks/{checkId}/results
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckidresults-get-openapi.md
- name: Checks API Checks {checkId} Results?fromUtc={fromUtc}&amp;toUtc={toUtc}&amp;detail_level={detail_level}
  x-api-slug: checks-api
  description: Gets check results between two dates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: https://api.pingdom.com////checks/{checkId}/results
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckidresults-get-openapi.md
- name: Checks API Get Check List
  x-api-slug: checks-api
  description: Returns a list overview of all checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: |-
    https://api.pingdom.com///
        /api/{version}/checks
  tags: Checks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/apiversionchecks-get-openapi.md
- name: Checks API
  x-api-slug: checks-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: https://api.pingdom.com//
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Checks Command API Checks Command
  x-api-slug: checks-command-api
  description: Creates a new Command check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommand-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommand-post-openapi.md
- name: Checks Command API Checks Command V2
  x-api-slug: checks-command-api
  description: Creates a new Command check (version 2).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command-v2 '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandv2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandv2-post-openapi.md
- name: Checks Command API Checks Command V2 {checkId}
  x-api-slug: checks-command-api
  description: Updates a command check (version 2).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command-v2/{checkId} '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandv2checkid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandv2checkid-put-openapi.md
- name: Checks Command API Checks Command {checkId}
  x-api-slug: checks-command-api
  description: Updates a command check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command/{checkId} '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandcheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandcheckid-put-openapi.md
- name: Checks Command API Checks Command Categories
  x-api-slug: checks-command-api
  description: Gets a list of all command check categories that are available for
    you as customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command/categories '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandcategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandcategories-get-openapi.md
- name: Checks Command API Checks Command V2 Categories
  x-api-slug: checks-command-api
  description: Gets a list of all command check (version 2) categories that are available
    for you as customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command-v2/categories '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandv2categories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandv2categories-get-openapi.md
- name: Checks Command API Checks Command Locations
  x-api-slug: checks-command-api
  description: Gets a list of all locations that are available for Command checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/command/locations '
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandlocations-get-openapi.md
- name: Checks Command API Checks Command V2 Locations?protocol={protocol}
  x-api-slug: checks-command-api
  description: Gets a list of all locations that are available for Command checks
    (version 2).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///checks/command-v2/locations
  tags: Checks,Command
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandv2locations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscommandv2locations-get-openapi.md
- name: Checks Command API
  x-api-slug: checks-command-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Checks Job API Checks {checkId} Job
  x-api-slug: checks-job-api
  description: DEPRECATED. Gets the current job status for a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/{checkId}/job '
  tags: Checks,Jobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckidjob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckidjob-get-openapi.md
- name: Checks Job API Checks {checkId} Job
  x-api-slug: checks-job-api
  description: Executes a check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/{checkId}/job '
  tags: Checks,Jobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckidjob-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkscheckidjob-post-openapi.md
- name: Checks Job API
  x-api-slug: checks-job-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Checks Ping API Checks Ping
  x-api-slug: checks-ping-api
  description: Creates a new Ping check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/ping '
  tags: Checks,Pings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksping-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksping-post-openapi.md
- name: Checks Ping API Checks Ping {checkId}
  x-api-slug: checks-ping-api
  description: Updates a Ping check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/ping/{checkId} '
  tags: Checks,Pings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkspingcheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkspingcheckid-put-openapi.md
- name: Checks Ping API Checks Ping Locations
  x-api-slug: checks-ping-api
  description: Gets a list of all locations that are available for Ping checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/ping/locations '
  tags: Checks,Pings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkspinglocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checkspinglocations-get-openapi.md
- name: Checks Ping API
  x-api-slug: checks-ping-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Checks Port API Checks Port
  x-api-slug: checks-port-api
  description: Creates a new Port check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/port '
  tags: Checks,Ports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksport-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksport-post-openapi.md
- name: Checks Port API Checks Port {checkId}
  x-api-slug: checks-port-api
  description: Updates a Port check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/port/{checkId} '
  tags: Checks,Ports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksportcheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksportcheckid-put-openapi.md
- name: Checks Port API Checks Port Locations
  x-api-slug: checks-port-api
  description: Gets a list of all locations that are available for Port checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/port/locations '
  tags: Checks,Ports
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksportlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksportlocations-get-openapi.md
- name: Checks Port API
  x-api-slug: checks-port-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Checks Proxysniffer Checks Proxysniffer
  x-api-slug: checks-proxysniffer
  description: Creates a new ProxySniffer check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysniffer-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysniffer-post-openapi.md
- name: Checks Proxysniffer Checks Proxysniffer {checkId}
  x-api-slug: checks-proxysniffer
  description: Updates a proxy sniffer check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer/{checkId} '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysniffercheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysniffercheckid-put-openapi.md
- name: Checks Proxysniffer Checks Proxysniffer Locations
  x-api-slug: checks-proxysniffer
  description: Gets a list of all locations that are available for ProxySniffer checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer/locations '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysnifferlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysnifferlocations-get-openapi.md
- name: Checks Proxysniffer Checks Proxysniffer {checkId} Results {resultId} URLdata?format={format}
  x-api-slug: checks-proxysniffer
  description: Gets a file that contains ProxySniffer check result data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer/{checkId}/results/{resultId}/urldata?format={format} '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysniffercheckidresultsresultidurldataformatformat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysniffercheckidresultsresultidurldataformatformat-get-openapi.md
- name: Checks Proxysniffer Checks Proxysniffer {checkId} Results URLdata
  x-api-slug: checks-proxysniffer
  description: Gets ProxySniffer check results in json format by result ids.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer/{checkId}/results/urldata '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysniffercheckidresultsurldata-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysniffercheckidresultsurldata-post-openapi.md
- name: Checks Proxysniffer Checks Proxysniffer {checkId} Results {resultId} Errorlog
  x-api-slug: checks-proxysniffer
  description: Gets an error log of the given ProxySniffer check result.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/proxysniffer/{checkId}/results/{resultId}/errorlog '
  tags: Checks,Proxy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysniffercheckidresultsresultiderrorlog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksproxysniffercheckidresultsresultiderrorlog-get-openapi.md
- name: Checks Proxysniffer
  x-api-slug: checks-proxysniffer
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Checks URL Checks URL
  x-api-slug: checks-url
  description: Creates a new URL check (legacy version 1).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurl-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurl-post-openapi.md
- name: Checks URL Checks URL V2
  x-api-slug: checks-url
  description: Creates a new URL check (version 2).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url-v2 '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurlv2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurlv2-post-openapi.md
- name: Checks URL Checks URL {checkId}
  x-api-slug: checks-url
  description: Updates a URL check (legacy version 1).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url/{checkId} '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurlcheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurlcheckid-put-openapi.md
- name: Checks URL Checks URL V2 {checkId}
  x-api-slug: checks-url
  description: Updates a URL check (version 2).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url-v2/{checkId} '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurlv2checkid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurlv2checkid-put-openapi.md
- name: Checks URL Checks URL Locations
  x-api-slug: checks-url
  description: Gets a list of all locations that are available for URL (legacy version
    1) checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url/locations '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurllocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurllocations-get-openapi.md
- name: Checks URL Checks URL V2 Locations
  x-api-slug: checks-url
  description: Gets a list of all locations that are available for URL (version 2)
    checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/url-v2/locations '
  tags: Checks,URL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurlv2locations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/checksurlv2locations-get-openapi.md
- name: Checks URL
  x-api-slug: checks-url
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Customers API Customers {customerId}
  x-api-slug: customers-api
  description: Returns subcustomer by subcustomer's ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///customers/{customerId} '
  tags: Customers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/customerscustomerid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/customerscustomerid-get-openapi.md
- name: Customers API Customers
  x-api-slug: customers-api
  description: Creates customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///customers '
  tags: Customers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/customers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/customers-post-openapi.md
- name: Customers API Customers {customerId} Subscription
  x-api-slug: customers-api
  description: Updates customer's subscription.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///customers/{customerId}/subscription '
  tags: Customers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/customerscustomeridsubscription-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/customerscustomeridsubscription-put-openapi.md
- name: Customers API
  x-api-slug: customers-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Groups API Groups
  x-api-slug: groups-api
  description: Gets a hierarchy of all monitor groups that are visible to you as a
    user or a customer depending on the request context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///groups '
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groups-get-openapi.md
- name: Groups API Groups
  x-api-slug: groups-api
  description: Creates a new monitor group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///groups '
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groups-post-openapi.md
- name: Groups API Groups {groupId}
  x-api-slug: groups-api
  description: Updates a monitor group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///groups/{groupId} '
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupid-put-openapi.md
- name: Groups API Groups {groupId}
  x-api-slug: groups-api
  description: Deletes a monitor group by Id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///groups/{groupId} '
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupid-delete-openapi.md
- name: Groups API Groups {groupId} Checks
  x-api-slug: groups-api
  description: Gets a list of checks assigned to the monitor group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///groups/{groupId}/checks '
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidchecks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidchecks-get-openapi.md
- name: Groups API Groups {groupId} Checks
  x-api-slug: groups-api
  description: Assigns checks to the monitor group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///groups/{groupId}/checks '
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidchecks-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidchecks-post-openapi.md
- name: Groups API Groups {groupId} Checks
  x-api-slug: groups-api
  description: Unassigns checks from the monitor group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///groups/{groupId}/checks '
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidchecks-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidchecks-delete-openapi.md
- name: Groups API Groups {groupId} Users
  x-api-slug: groups-api
  description: Gets a list of users assigned to the monitor group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///groups/{groupId}/users '
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidusers-get-openapi.md
- name: Groups API Groups {groupId} Users
  x-api-slug: groups-api
  description: Assigns users to the monitor group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///groups/{groupId}/users '
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidusers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidusers-post-openapi.md
- name: Groups API Groups {groupId} Users
  x-api-slug: groups-api
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///groups/{groupId}/users '
  tags: Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidusers-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/groupsgroupidusers-delete-openapi.md
- name: Groups API
  x-api-slug: groups-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Messages API Clear a bucket (remove all messages).
  x-api-slug: messages-api
  description: Clear a bucket (remove all messages)..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///buckets/{bucketKey}/messages
  tags: Buckets,BucketKey,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/bucketsbucketkeymessages-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/bucketsbucketkeymessages-delete-openapi.md
- name: Messages API Retrieve a list of messages in a bucket
  x-api-slug: messages-api
  description: Retrieve a list of messages in a bucket.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///buckets/{bucketKey}/messages
  tags: Buckets,BucketKey,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/bucketsbucketkeymessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/bucketsbucketkeymessages-get-openapi.md
- name: Messages API Create a message
  x-api-slug: messages-api
  description: Create a message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///buckets/{bucketKey}/messages
  tags: Buckets,BucketKey,Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/bucketsbucketkeymessages-post-openapi.md
- name: Messages API Retrieve the details for a single message.
  x-api-slug: messages-api
  description: Retrieve the details for a single message..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///buckets/{bucketKey}/messages/{messageId}
  tags: Buckets,BucketKey,Messages,MessageId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/bucketsbucketkeymessagesmessageid-get-openapi.md
- name: Messages API Messages?active={active}&amp;customerId={customerId}
  x-api-slug: messages-api
  description: Gets a list of UI messages. UI messages are used for user notifications
    on announcements/information/warnings.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///messages?active={active}&amp;customerId={customerId} '
  tags: Messages?active=active&amp;customerId=customerId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/messagesactiveactiveampcustomeridcustomerid-get-openapi.md
- name: Messages API Messages
  x-api-slug: messages-api
  description: Creates an UI message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///messages '
  tags: Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/messages-post-openapi.md
- name: Messages API Messages {id}
  x-api-slug: messages-api
  description: Gets an existing UI message by Id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///messages/{id} '
  tags: Messages,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/messagesid-get-openapi.md
- name: Messages API Messages {id}
  x-api-slug: messages-api
  description: Updates an existing UI message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///messages/{id} '
  tags: Messages,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/messagesid-put-openapi.md
- name: Messages API Messages {id}
  x-api-slug: messages-api
  description: Deletes an existing UI message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///messages/{id} '
  tags: Messages,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/messagesid-delete-openapi.md
- name: Messages API
  x-api-slug: messages-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Roles API Get Roles
  x-api-slug: roles-api
  description: Return user roles
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///roles '
  tags: Roles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/roles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/roles-get-openapi.md
- name: Roles API
  x-api-slug: roles-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
- name: Scenarios API Scenarios Proxysniffer Dictionaries
  x-api-slug: scenarios-api
  description: Adds Proxy Sniffer scenario custom dictionary.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///scenarios/proxysniffer/dictionaries '
  tags: Scenarios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/scenariosproxysnifferdictionaries-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/scenariosproxysnifferdictionaries-post-openapi.md
- name: Scenarios API Scenarios Proxysniffer Dictionaries {dictionary_key}
  x-api-slug: scenarios-api
  description: Gets a Proxy Sniffer scenario custom dictionary by dictionary key.
    Custom dictionary can contain any data used by Proxy Sniffer scripts which needs
    to be stored separately from scripts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///scenarios/proxysniffer/dictionaries/{dictionary_key} '
  tags: Scenarios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/scenariosproxysnifferdictionariesdictionary-key-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/scenariosproxysnifferdictionariesdictionary-key-get-openapi.md
- name: Scenarios API Scenarios Proxysniffer Dictionaries {dictionary_key}
  x-api-slug: scenarios-api
  description: Updates Proxy Sniffer scenario custom dictionary.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///scenarios/proxysniffer/dictionaries/{dictionary_key} '
  tags: Scenarios
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/scenariosproxysnifferdictionariesdictionary-key-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/scenariosproxysnifferdictionariesdictionary-key-put-openapi.md
- name: Scenarios API
  x-api-slug: scenarios-api
  description: Apica???s performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Apica
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apica/master/_listings/apica/openapi.md
x-common:
- type: x-blog
  url: https://www.apicasystem.com/blog/
- type: x-blog-rss
  url: https://www.apicasystem.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/apica
- type: x-developer
  url: http://api-wpm.apicasystem.com/v3/help
- type: x-documentation
  url: https://api-wpm.apicasystem.com/v3/Help
- type: x-email
  url: sales@apicasystems.com
- type: x-email
  url: swesales@apicasystems.com
- type: x-email
  url: support@apicasystems.com
- type: x-email
  url: operations@apicasystem.com
- type: x-github
  url: https://github.com/ApicaSystem
- type: x-twitter
  url: https://twitter.com/apicasystems
- type: x-website
  url: https://www.apicasystem.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---