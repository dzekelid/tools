---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API List Locations
  description: List Locations
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /diagnostic-tools/v1/locations:
    get:
      summary: List Locations
      description: List Locations
      operationId: diagnostictoolsv1locations
      x-api-path-slug: diagnostictoolsv1locations-get
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Locations
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