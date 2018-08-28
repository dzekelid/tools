---
swagger: "2.0"
x-collection-name: Zerigo
x-complete: 1
info:
  title: Zerigo
  version: 1.0.0
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
  /api/1.1/tools/public_ipv6.xml:
    get:
      summary: Get the current public IPv6
      description: If you&#8217;re doing development or production with IPv6, it may
        be helpful to check if IPv6 works for you.
      operationId: get-the-current-public-ipv6
      x-api-path-slug: api11toolspublic-ipv6xml-get
      responses:
        200:
          description: OK
      tags:
      - Tools
  /api/1.1/tools/public_ip.xml:
    get:
      summary: Get the current public IP
      description: If you&#8217;re doing development or production behind NAT devices,
        it may be helpful to retrieve your current public IPv4/IPv6 address.
      operationId: get-the-current-public-ip
      x-api-path-slug: api11toolspublic-ipxml-get
      responses:
        200:
          description: OK
      tags:
      - Tools
  header:
    content-type:
      summary: Single page version
      description: Zerigo DNS supports a fairly standard REST API for full creation,
        modification, and deletion of domain (zone) and host records. It is easy and
        straightforward to work with.
      operationId: single-page-version
      x-api-path-slug: header-contenttype
      responses:
        200:
          description: OK
      tags:
      - Tools
---