---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API Translate Error Code
  description: Translate Error Code
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
  /diagnostic-tools/v1/dig:
    get:
      summary: Run dig
      description: Run dig
      operationId: diagnostictoolsv1dighostnamequerytypelocationsourceip
      x-api-path-slug: diagnostictoolsv1dig-get
      parameters:
      - in: query
        name: hostname
        description: the domain name you want to get information about
        type: string
      - in: query
        name: location
        description: Location of Akamai server from which you want to run dig
        type: string
      - in: query
        name: queryType
        description: 'query type for the dig; valid types are:'
        type: string
      - in: query
        name: sourceIp
        description: CDN server IP to run DIG from
        type: string
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Dig
      - Hostname
      - querytype
      - location
      - sourceip
  /diagnostic-tools/v1/mtr:
    get:
      summary: Run mtr
      description: Run mtr
      operationId: diagnostictoolsv1mtrdestinationdomainlocationsourceip
      x-api-path-slug: diagnostictoolsv1mtr-get
      parameters:
      - in: query
        name: destinationDomain
        description: The domain name you want to get information about
        type: string
      - in: query
        name: location
        description: Location of Akamai Server you want to run dig from
        type: string
      - in: query
        name: sourceIp
        description: CDN server IP to run MTR from
        type: string
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Mtr
      - Destinationdomain
      - location
      - sourceip
  /diagnostic-tools/v1/akamaitranslator:
    get:
      summary: Translate Hostname
      description: Translate Hostname
      operationId: diagnostictoolsv1akamaitranslatorhostname
      x-api-path-slug: diagnostictoolsv1akamaitranslator-get
      parameters:
      - in: query
        name: hostname
        description: Hostname for which to retrieve ARL information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Akamaitranslator
      - Hostname
  /diagnostic-tools/v1/errortranslator:
    get:
      summary: Translate Error Code
      description: Translate Error Code
      operationId: diagnostictoolsv1errortranslatorerrorcode
      x-api-path-slug: diagnostictoolsv1errortranslator-get
      parameters:
      - in: query
        name: errorCode
        description: Error code or reference number you want to translate, which typically
          appears on an error page
        type: string
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Errortranslator
      - Errorcode
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