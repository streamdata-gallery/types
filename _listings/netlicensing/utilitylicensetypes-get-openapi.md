---
swagger: "2.0"
x-collection-name: NetLicensing
x-complete: 0
info:
  title: NetLicensing License Types list
  description: Return a list of all license types supported by the service
  termsOfService: https://www.labs64.com/legal/terms-of-service/netlicensing
  version: 2.x
host: go.netlicensing.io
basePath: /core/v2/rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /utility/licenseTypes:
    get:
      summary: License Types list
      description: Return a list of all license types supported by the service
      operationId: licenseTypes
      x-api-path-slug: utilitylicensetypes-get
      responses:
        200:
          description: OK
      tags:
      - Utility
      - LicenseTypes
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