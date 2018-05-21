---
swagger: "2.0"
x-collection-name: Zerigo
x-complete: 0
info:
  title: Zerigo Get the current public IPv4
  version: 1.0.0
  description: If you&#8217;re doing development or production behind NAT devices,
    it may be helpful to retrieve your current public IPv4 address.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/1.1/tools/public_ipv4.xml:
    get:
      summary: Get the current public IPv4
      description: If you&#8217;re doing development or production behind NAT devices,
        it may be helpful to retrieve your current public IPv4 address.
      operationId: get-the-current-public-ipv4
      x-api-path-slug: api11toolspublic-ipv4xml-get
      responses:
        200:
          description: OK
      tags:
      - Tools
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